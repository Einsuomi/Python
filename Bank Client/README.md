  # Bank Client
  
  **In this project, my job is to create a classification model that can predict whether a client of a bank will positively respond to a marketing campaign and invest some amount of money. The data is in the file ’bank.csv’, and contains the following information about the client:**
  
• **age**: age of the client in years

• **job**: type of job of the client, 11 possible categories

• **marital**: marital status, 3 possible categories

• **education**: highest level of education, 6 possible categories

• **balance**: average yearly balance

• **housing**: whether the client has housing loan (1 or 0)

• **loan**: whether the client has personal loan (1 or 0)

• **day**: day of month when the client was contacted the last time about the campaign

• **month**: month when the client was contacted the last time about the campaign, values 1-12

• **duration**: the duration of the last contact by phone, in seconds

• **contact count**: number of contacts performed during this campaign for the client

• **previous**: number of contacts performed in a previous campaign for the client

• **outcome**: whether the client has invested in the product advertised in the current campaign

***I try to perform the following tasks:***

• Perform one-hot encoding on the categorical columns job, marital and education.

• Check the histograms of the columns balance, duration and contact count. If there are outliers in the data, remove them.

• Build a logistic regression classification model with ’outcome’ column as the target, and using all other variables as predictors. Divide the data set into training (75 %) and test set (25 %), use random state= 0, and follow the process of building a classification model.

• Create the confusion matrix, calculate classification performance measures. Identify the accuracy of the model on the test set?

• Some Findings. e.g.Does the model perform similarly for the two possible categories of ’outcome’, i.e. for positive and negative class? If not, do you think it is a problem? How many false negatives do you find, i.e.
clients who would invest in the advertised product but the model predicts that they would not?
