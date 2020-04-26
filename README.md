# INTRODUCTION
Airbnb is an online marketplace that connects people who want to rent out their homes with people who are looking for accommodations in that locale. It currently covers more than 81,000 cities and 191 countries worldwide. The company's name comes from "air mattress B&B.”
Since 2008, guests and hosts have used Airbnb to expand on traveling possibilities and present more unique, personalized way of experiencing the world.

NYC is the most populous city in the United States and also one of the most popular tourism and business place in the world.
Airbnb NYC 2019 data contains listing activity and metrics.

# In this project, I would like to choose the best prediction model for price.

AirBnB acts as a broker between listing owners and customers. It sets up prices of listing according to multiple parameters and provides independence to listing owners to decide their own prices. However, with growing business , it would be a better idea if AirBnB can help new owners registering into portal with estimating prices that could enable them more customers and also provide affordable accomodation options to customers. We will build up a model which on basis of past pattern sets up smart pricing mechanism.



* id: listing ID
* name: name of the listing
* host_id: host ID
* host_name: name of the host
* neighbourhood_group: location
* neighbourhood: area
* latitude: latitude coordinates
* longitude: longitude coordinates
* room_type: listing space type
* price: price in dollars
* minimum_nights: amount of nights minimum
* number_of_reviews: number of reviews
* last_review: latest review
* reviews_per_month: number of reviews per month
* calculated_host_listings_count: amount of listing per host
* availability_365: number of days when listing is available for booking


# What can be derived from this data?

*What type of model can be assigned to this dataset? Ans. Regression model for predicting the prices.

*What kind of evaluation metrics will you use for this model? Ans. Since, it is a linear model regression problem, we will use explained variance score,mean-squared-error, and R^2 score for evaluation .

*How will this predictive model help the client? Ans. The client can predict prices according to location and condition of facility and negotiate with host with a range of prices. This will help in building a better and affordable listing for customers and set right expectations for customers at affordable prices. If prices are set high by host, then it would be a loss outcome for all-host,airbnb and customer.
