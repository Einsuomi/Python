# New York Airbnb

## Dataset Description

The dataset includes information about hosts, geographical availability, and different metrics available from Airbnb places in New York City. 

The list of available variables is as follows:


- **id:** listing ID
- **name:** listing Title
- **host id:** ID of Host
- **host name:** fame of Host
- **neighbourhood group:** name of location that contains listing
- **neighbourhood:** name of neighbourhood that listing is in
- **latitude:** latitude of listing
- **longitude:** longitude of listing
- **room type:** type of public space that is being offered
- **price:** price per night, USD
- **minimum nights:** minimum number of nights required to book listing
- **number of reviews:** total number of reviews that listing has accumulated
- **last review:** date in which listing was last rented
- **reviews per month:** total number of reviews divided by the number of months the listing is active
- **calculated host listings count:** amount of listing per host
- **availability 365:** number of days per year the listing is active

## Goals

I will analyse the dataset from different perspectives, with the main focus on understanding what are the most important variables that determine the price of a listing.

## Solutions

- Perform some descriptive analysis to get a picture of the data. 
- Build a prediction model for predicting price using the variables of choice with random forest regression.
- Finally, I will try to understand the impact of the review name on the price.
  - Generate 10 most frequent words that appear in the listing column.
  - General and remove stopwords. ( English stopwords and other expressions I need to exclude to get some meaningful results)
  - Finally, test whether the regression model that I created in the previous step can be improved by including these 10 new columns as predictors.


## Results

The prediction model with 10 most frequent words has a better performance.

![image](https://user-images.githubusercontent.com/97128113/201638498-dc14da47-b1e7-4094-9c7d-4a6964d80c27.png)
