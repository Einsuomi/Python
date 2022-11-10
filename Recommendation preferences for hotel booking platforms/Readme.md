# Recommendation Preferences for hotel booking platforms

## Description
In this project, I scraped data from 3 websites which are booking.com, expedia.com and hotels.com.

This project is about exploratory analyze the data of hotel information of a specific stay period and a specific location and let users can interact with the data.

Furthermore, I will try to find out each website’s Recommendation Preferences, such as which website used to recommend more expensive hotels or which website recommend higher review score hotel first.
So, When scraping the data, I did not filter the hotels, such as by price ascending or by hotel stars, which means it is all the default recommendations of each website. It gives me a 
chance to explore the recommendations preferences.

## To accomplish this goal, I did the following steps:

• Data Scraping (by using BeautifulSoup)

• Data Processing 

• Exploratory data analysis (Visualization)

• Interaction with the user


## 
It is worth mentioning that The specific stay period and a specific location I chose are from 2022.12.23 to 2022.12.25 in Venice, Italy. 
Dataset of three websties are also uploaded.

## Interesting Findings
- **The relationship between source and the mean of average price:** the recommendation hotels from booking.com has the highest mean of average price, maybe either booking.com wants to recommend more expensive hotel to users or their hotel price is higher than other websites. Hotels.com has the lowest average price.

- **The relationship between source and the average hotel rating:** Hotels.com has the lowest average hotel rating. Considering the lowest mean of average price, maybe hotels.com wants to default recommend lower price hotels to users, so the hotel rating is relatively lower.

- More Findings and code can be seen in the Jupyter Notebook.
