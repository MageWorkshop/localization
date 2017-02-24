#Magento 1.x MageWorkshop Detailed Review extension localization

##How to localize?

Copy CSV file(s) from en_US directory to the appropriate local, eg fr_FR related to the French - France. And make a translation line by line.
eg Let's take a string from file MageWorkshop_DetailedReview.csv 

> "Review Text","Review Text"

and translate it to the french, should be something like below
 
>"Review Text","Réviser le texte"

Put localization directory with files to the appropriate directory of Magento by the path {project_root}app/locale/.

##Were added localization files for a few locale.
1. de_DE, Deutsch - German locale. Contains not a full translation. Starting from line 412, the text didn't translate but we recommend check all files.    
2. he_IL, Hebrew - Israel locale. Contains not full translation. Starting from line 93, the text didn't translate but we recommend check all files.    
3. nl_NL, Dutch - Netherlands locale. Contains not full translation. Starting from line 50, the text didn't translate but we recommend check all files.    
4. ru_RU, Russian - Russian locale. Contains not full translation. Starting from line 90, the text didn't translate but we recommend check all files.    
