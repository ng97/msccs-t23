# msccs-t23
Identify &amp; categorize tweets during emergencies, visualize &amp; analyze data produced by system.

Part of the University of Glasgow Master's Team Project for Data Science students.

### Hierarchy of this project:

- app #Store flask based web application code.

    -- for

    -- static #store static resource
 
    -- templates #Store html templates

 - classifier #store the classfier code
 
    -- data_files_scripts #store database code

 - flask #virtual environment of this project

### To run this project
    in windows, enter msccs-t23-master folder by cmd, type following command.
    >> flask\Scripts\python.exe helpme.py

FELL FREE TO RUN IT IN YOUR OWN ENVIROMENT.

### Database
Database: MongoDB
DatabaseName: Helpme

CollectionName:
"Test"Store testdata.

"Train" Store TrainLabels

"Train_Token" Store Trainingdata.

"func_test" collection for testing functions.

"TweetsData" Store all the TweetsData.
