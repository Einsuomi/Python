# Introduction

  This project deals with a real world problem in the big data era and presents a new perspective on how hotels can maintain and improve their online reputation through the use of machine learning techniques to predict the ratings of reservations. The approach involves analysing data that customers provide when booking a room. 

  The project's primary objective is to assess the effectiveness of machine learning in predicting negative instances, a critical factor in managing online reputation. 4 algorithms are used and total 124 models are created to accomplish this goal. 

  This project include all steps of data analysis to handle a real world problem, from idea generation, background research, data collection, data preprocessing, EDA, feature engieering, data modeling and analysis, results interpretation. If you are interested in this topic, please contact me to get the complete version of report. 

# Algorithms
- Logistic regression
- Random forest
- XGBoost
- ANN

# Variables 
- Country: Where the customers come from of a reservation
- Room_type: Which room type the customers book in a reservation
- Nights: How many nights customers book in a researvation
- Check_in_Month : In which month will the customers check in of a researvation
- Travel_Type: The customers travel as a Group, Family, Couple, or Solo.
- Rating: The target variable, How would the customers rate their stay.


### The code of different processes of the project are shown in different ipynb files in this folder.

# Results
  Out of the 124 models generated from the four algorithms under consideration, the 30th ANN model with hyperparameters tuned to {'batch_size': 30, 'epochs': 100, 'num_hidden_layers': 6, 'num_nodes': 6}, exhibites the highest TN_score value of 0.55. This model is designed with a specific set of features consisting of Room_Type, Travel_Type, Check_In_Month, and Nights.

![image](https://github.com/Einsuomi/Python/assets/97128113/d844203a-a73c-44c4-b1f2-4418e214c4e1)


# Conclusion 
  The best performing models achieved a 60% accuracy in classifying negative instances. However, increasing the number of predicted true negative instances also increased the number of false negative instances. This result was primarily due to the unpredictability of customer behaviour, making it difficult to accurately predict ratings. 

  Despite not achieving the desired result, this project still presents a novel direction for future research and provides suggestions for future research ideas. For example, future research could examine mitigating the unpredictability of customer behaviour by collaborating with multiple booking platforms to develop a database that incorporates the historical data of each customer. 

