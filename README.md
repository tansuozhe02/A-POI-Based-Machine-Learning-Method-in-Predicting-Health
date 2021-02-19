# Finding-Healthy-Community-Design-Criteria-with-AI
Analysis of health data from CDC and POI data from OpenStreetMap with machine learning to find design criteria for a healthy community.

The main idea is get the number of POI data from different categories and join them spatially with the health evaluation data from CDC. 

The first step of the project is feature selection. We have tested 52 features from categories like food, health, transport, community, leisure, tourism, building and nature for the area of California. After running PCA, we found that 12 of the features have bigger impacts on the variation. 

The second step is to a regression with the selected features and the health data. We get a pretty good accuracy using various regression models. 

The third step is test the model on a larger dataset. We use the CDC health data for 500 most populated cities in the US to test our feature selection. Hopefully we will get a better result than the smaller data. This is still in progress.

The last step would be using this method to predict the health status of other cities in the world and give data-supported urban planning suggestions. 
