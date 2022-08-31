# Bike Sharing Platform

In this project, I will perform tasks faced by a data analyst working with data from a bike sharing platform (’bike data.csv’). Your job is to build a predictive   model to estimate demand for bicycles at different locations using the following information (one row in the data is for one day of the year):

• **season**: the season of the observaton (1: winter, 2: spring, 3: summer, 4: fall)

• **month** : the year of the month (1 to 12, from January to December)

• **holiday** : whether the day is holiday or not (0 or 1)

• **day**: day of the month (1-31)

• **weekday** : day of the week (1 to 7)

• **workingday** : 1, if day is neither weekend nor holiday is 1, and 0 otherwise

• **weather**: weather conditions (1: clear, partly cloudy; 2: cloudy, light rain; 3: thunderstorm, light snow)

• **temp** : temperature in Celsius

• **hum**: humidity

• **wind**: wind speed

• **registered**: total number of registered users checking the platform app within the day

• **cnt**: count of total rental bikes during the day <br />


***I will perform the following tasks***:<br />

• Exploratory data analysis: try to understand the different variables in the data. Identify the variables, based on exploratory data analysis methods, that you think have an effect on the count of rental bikes needed. As part of this exploratory analysis, create visualizations that show the relationship between ’cnt’ and the other variables (create at least 4 plots, you are free to create more if you think it can help in understating the problem), perform aggregation (check how average ’cnt’ varies across months, days, working days, and holidays), calculate correlation of the variables.

• Develop a regression model that the company can use to predict the count of total rental bikes. Start with all the variables included in the data file, then follow the process suggested in the lectures to remove variables as long as you still find the model performance acceptable.

• By looking at the coefficients of my final model, would you say that, for example, the company willneed more bikes on a day when temperature is 20 or on a day when temperature is 25?
