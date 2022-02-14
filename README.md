# capstone-project : Implementation the Spatial Item Recommender System (LCARS) based on Latent Dirichlet Allocation (Hongzhi YIN et Al, 2014)


Newly emerging location-based and event-based social network services, such as Foursquare provide us with a new platform to understand users preferences based on their activity history, and thus, we are able to recommend event or/and venues based on the users preferences.
For this capstone data science project i decided to implement a recommender system. There many different algorithm to do this,on of the most used are traditional collaborative filtering-based recommender systems. But, this method is limited since a user can only visit a limited number of venues/events and most of them are within a limited distance range, so the user-item matrix is very sparse.The problem becomes more challenging when people travel to a new city where they have no activity history.
LCARS can alleviate these problems by considering both user preferences and local preferences into recommendation.


The Two important notebooks are : 
LCARS-Data-PreProcesssing.ipynb : Contains the code for processing raw input data collected from the foursquare API (venues informations and  users check-in data) necessary to the production of the cleaned data set that will be the input data of the LCARS to produce its recommendations.
LCARS-LCA-LDA.ipynb : Contains the code the that implements the LCA-LDA model, it includes experimental results



