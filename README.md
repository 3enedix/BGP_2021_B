# BGP_2021_B
Big Geodata Processing -2021 - Group B

Group project with the goal to predict the observer intensity (defined as the number of observers per 1km^2-block and per hour/per week) in time or in space, based the Citizen Science project waarneming.nl.

The data was retrieved from the following data base: \
host: gip.itc.utwente.nl\
port: 5434\
database: c211\
user: sxxxxxx\
password: xxxxxx\

### Instructions
1. Folder 1_data_preparation: The three notebooks *daily_observer_intensity*, *weekly_observer_intensity* and *monthly_observer_intensity* prepare the original datasets. Each one of the notebooks creates a new single table with all the fields required for further processing in the indicated temporal resolution.
2. Folder 2_data_exploration: The notebook *expl_data_statistics* performs some exploratory analysis on the data from the tables creating in step 1). The notebook *Map* creates a map showing the spatial distribution of observer intensity in the Netherlands.
3. Folder 3_modeling: The notebook *ML* models the observer intensity using a supervised machine learning algorithm (random forest regression) in several configurations, using the data created in step 1).

