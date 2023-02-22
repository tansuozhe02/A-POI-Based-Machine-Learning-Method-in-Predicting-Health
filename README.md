# Finding-Healthy-Community-Design-Criteria-with-AI

This is a work about using data to validate urban planning theories. Urban planning theories suggest that community connections, healthy eating and physical activity are the three most important factors for a healthy city. But how to prove that from a data point of view? What does it suggest for healthy city planning?

The idea is to analyze health data from CDC and POI data from OpenStreetMap with machine learning methods to find the relations. 

The first step is to get the number of POI data from different categories and join them spatially with the health evaluation data from CDC. We use the spacial unit of 'place' in the United States, which is a locally recognized concentration of population which has a name.

The second step is feature selection. We have tested 50 features from categories like food, health, transport, community, leisure, tourism, building and nature for the area of five most populous states in America. We have also studied the correlation between those features. 

The third step is to do a regression with the selected features and the health data. We get a pretty good accuracy using various regression models. 

The fourth step is to understand the feature importance. After categorizing the features, we have validated the theory that community connections, healthy eating and physical activity can best predict the health status of residents in a place. It informs decision makers that to pay more attention to these areas. 

In the last step, we make a new prediction on the health status of the residents after adjusting some key features. 

In conclusion, urban features related to healthy living has a great influence on residents' health. This project showcases that by validating the theory with data, urban planner can better prove their suggestions and achieve a better consensus from all parties. 

Full paper available: https://www.researchgate.net/publication/364653326_A_POI-Based_Machine_Learning_Method_in_Predicting_Health
