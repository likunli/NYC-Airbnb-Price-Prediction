## Airbnb Price Prediction - Team 11

### Dataset Introduction
Airbnb Listing Data from Airbnb Offical Website, post on 10/05/2020
http://data.insideairbnb.com/united-states/ny/new-york-city/2020-10-05/visualisations/listings.csv

|Columns | Remark |
| --- | --- |
| id | Listing ID|
|name| Listing Title|
| host_id | ID of Host|
| host_name | Name of Host|
| neighbourhood_group | Borough that contains listing|
| neighbourhood | Name of neighbourhood that listing is in|
| latitude | latitude of listing|
| longitude |longitude of listing|
| room_type | Type of public space that is being offered|
| price | price per night, USD|
| minimum_nights | minimum number of nights required to book listing|
| number_of_reviews | total number of reviews that listing has accumulated|
| last_review | date in which listing was last rented|
| reviews_per_month | total number of reviews divided by the number of months the listing is active|
| calculated_host_listings_count | amount of listing per host|
| availability_365 | number of days per year the listing is active|

### Problem Statement

Over the last decades, Aribnb shares the most popluar rental properties. By given this dataset describes the listing activity and metric in New York City, 2020, we decided to do the analysis on the dataset, to dig out more information, such as the type of room, price, and their distribution, etc. At the meantime, in addition to data analysis, we build three models (Liner Regression, Random Forest, Decision Tree) to to predict the price of NYC Airbnb rentals based on the data provided.

### Importance and Impact

1. Through the analysis of the 2020 NYC Aribnb listing dataset, We could have a macro understanding of Aribnb in New York and can find more details in the data set, such as the distribution of prices and room types, etc.  
2. Airbnb pricing is important, particularly in big cities like New York where there is a lot of competition and small differences in prices will make a huge difference. It is a trade-off problem and which is pretty hard to do correctly. 
3. With price prediction model, Airbnb home provider could get a proper price to optimize profit and affordability



### Conclusion
By applying data to three ML Algorithms, which are Liner Regression, Random Forest Regression and Decision Tree Regression, we found that the Random Forest Regression has the best performance. Random Forest has the highest R-squared score and lowest MSE score. In terms of works in the future, there are two directions, firstly, we could consider finding the relationship between Aribnb Naming and its price. Secondly, instead of predicting a specific price, we could turn it into a classification problem, predicting a price bucket, which will show Airbnb home provider a lowest suggest price and a highest suggest price. By doing so, accuracy may very well increase and this model would be more useful from a practical standpoint.

