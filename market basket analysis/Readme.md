#  Market Basket Analysis

## Dataset Description

The dataset includes shopping data, with additional info on the period of day and whether the transaction happened on a weekday or during the weekend.

The dataset has several rows for each transaction, one row for each item.

The dataset is like: 

![image](https://user-images.githubusercontent.com/97128113/201421744-7d9f082f-2122-4006-b30d-0bd12d7941a5.png)


## Research Questions

1. Do the extracted rules seem to contain useful information or only trivial observations (do you mostly see the items that are the most frequent in general)?

3. What would you recommend to a person (i.e. what is the consequent in association rules terminology) when you know that in the basket there is already 
 
   - (i) Eggs, and the purchase is in the morning, 
 
   - (ii) Coke and Juice, and the purchase is in the afternoon, 
   
   - (iii) Toast, either in the morning or in the afternoon?


## Solutions

I will try to perform the analysis two times in order to discover some patterns or differences in customers’ purchase behaviour in the mornings and in the afternoons. 

First I will focus on transactions that took place in the mornings, transform the data into transactional format, extract frequent item-sets and create association rules. 

Then perform the same steps with the data of transaction in the afternoons. 

Before I create the association rules, I want to check what are the most frequently sold items, and try to find out are the most frequent items the same on a weekday and in the weekend? What 
about afternoons and mornings?


## Interesting Findings

1. Something people won't buy in the morning. 

![image](https://user-images.githubusercontent.com/97128113/201423542-66f8860a-7174-4e8c-9d7f-8071198b69c8.png)

2. One transaction may have two same items

![image](https://user-images.githubusercontent.com/97128113/201423695-28d8c96b-125b-4c7c-a4d0-5de1162520b9.png)


