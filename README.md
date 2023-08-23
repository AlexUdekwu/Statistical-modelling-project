# Final-Project-Statistical-Modelling-with-Python

## Project/Goals

To explore the citybikes API within the city of Vancouver and then identify areas of interest around the citybikes located in Vancouver using forusquare API and Yelps APi to identify restaurants and bars assessible by anoyone who visits the citybikes stations in Vancouver.

## Process
My inability to extract data for every bikestation using Api,hence worked with the data generated for one bike station and this also applied for foursquarea and yelps data presented. on this note, was unable to complete the data during the QA process. 
- Getting data from citybike api
- Getting data from foursquare api
- Gettng data from yelps api
- Cleaned all data to ensure duplicates are removed as well as columns with missing data removed.
- Output indicatesthat there are no duplicates on data.
- Cleaned the NAN rows on location and distance columns by replacing NAN rows with mean values.
- Joining of dataframes to identify areas of interest between the three dataframes
- Visualization and explaoration of data analysis using historgram, heatmap.
- Data collected showed low correlation with number of bikes.
- Data model building where p-values was generated to confirm validity of data.

## Results

- A total of 245 citybikes were located with the api and when all dataframes were combined, generated 257 data on 8 columns making sure all data within the three dataframes were displayed on the tables with coreelations in place.
- the adjusted R-squared shows model is fit to explain patterns of data with 0.096, the independent variable can only explain 0.1% of the observed dependent variable 
- with the P-value less than the 0.05 threshold means that these are statistically significant variables
- Eventhough these variables are statistically significant, the number of bikes is still dependent on more significant factors.

## Challenges 

Had challenges trying to set up the stretch of turning the regression model to a classification model.

## Future Goals
- To carry out from cleaning process on the NAN values on the tables
- Further research to understand the process of turning the regression model to a classification   model. 
- Find a way to use API keys to extract location of interests around citybikes locations.