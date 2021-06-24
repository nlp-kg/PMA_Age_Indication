# PMA_Age_Indication
This repository hosts preprocessing and analysis of manually annotated Premarket approval statements (PMA).

Clean_PMA_Analysis notebook has the code surrounding preprocessing, analyzing, and visualizing the number of devices available across age.
This notebook uses annotation data downloaded from PubAnnotation which has been provided in the data folder under the "Age_blah" folder.
This script produces ageAnnot.csv which is used for analysis. This csv has been provided in the data folder.
ageAnnot.csv provides detailed information on the annotations for each approval statement.

Query_PMAs notebook has code that queries the FDAOpen API for device metadata using the PMAs.
This script produces openFDAPMA.csv which is used for analysis in the Clean_PMA_Analysis notebook. This csv has been provided in the data folder.
openFDAPMA.csv provides device metadata on each PMA including location, advisory committee description, device class, product code, and more.
This csv is used later on in the Clean_PMA_Analysis analysis to characterize the types of devices available.

AgeIndication_Gap notebook has code surrounding the lag time in approval between generic device categories (Product code)

Annotations from PubAnnotation can be found here: http://pubannotation.org/projects/consensus_PMA_Age_Indications
https://jamanetwork.com/journals/jamanetworkopen/fullarticle/2781217
https://jamanetwork.com/journals/jamanetworkopen/fullarticle/2781221

