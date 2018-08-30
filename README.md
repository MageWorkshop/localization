#Magento 1.x, MageWorkshop, the localization of the Detailed Product Review extension

##How to localize? Copy the CSV file(s) from the “en_US” directory to the appropriate locale, eg., “fr_FR”, related to French, should be copied to “France.” 

Make the line by line translation. For example, Let's take a string which reads "Review Text" from the “MageWorkshop_DetailedReview.csv” file

> "Review Text", "Review Text" 

and translate it into French. It should be something like in the example, below: 
 
>"Review Text","Réviser le texte"

Put the localization directory with files to the appropriate Magento directory by the following path {project_root}app/locale/

##New localization files have been added to a few locales:
1. “de_DE, Deutsch” has been added to the “German” locale. It contains an incomplete translation: starting from the line 412, the text comes in its original language. However, we recommend to check all files.    
2. “he_IL, Hebrew” has been added to the “Israel” locale. It contains an incomplete translation: starting from the line 93, the text comes in its original language. However, we recommend to check all files.    
3. “nl_NL, Dutch” has been added to the “Netherlands” locale. It contains an incomplete translation: starting from the line 50, the text comes in its original language. However, we recommend to check all files.   
4. “ru_RU, Russian” has been added to the “Russian” locale. It contains an incomplete translation: starting from the line 90, the text comes in its original language. However, we recommend to check all files.
