# Data-Section

We are going to find all the postcodes of London through eight sources/pages from wikipedia. These sources will be used for text mining and creation of the original dataframe of London. In the dataframe, we will include the variables of PostCode(e.g. N1C),Name of the Neighborhood(e.g. Kings Cross Central), Area(e.g. Camden) & Area Category(e.g. North). In "area category" we are going to flag the 8 areas of London. 

We are going to proceed to the necessary data cleansing(e.g. non geolocation postcodes) and add for each neighborhood the latitude and longitude information from geocoder.

We are going to use Foursquare location data to extract the venues information for the areas of interest.We are going to create dummies for these categories in order to determine the best London area category based on the smallest frequencies of food restaurants. 

Based on these Foursquare location data we are going to group the neighborhoods in 5 clusters.Based on cluster's characteristics we are going to choose the neighborhood group that satisfies criteria of building a Greek restaurant such as type of other venues nearby(e.g. theaters,cinemas,parks etc.), if there are other restaurants that could be damaging for our business(e.g. a lot of ethnic restaurants) etc.

Finaly, during several steps of the project, we are going to use folium library to create the necessary maps in order to give a visual view to the investors of our actions & logic.
