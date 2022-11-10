# Students Performance Prediction


## Project Description
The data was collected from a fully online nine-week-long course on machine learning.

The goal of this project is to use two classification models to predict students’ final grade in an online course, and compare the two models' performance, finally, optimize the models to get a better prediction.

To accomplish this goal, I did the following steps:
- Descriptive analysis
- Exploratory data analysis
- Split data into train dataset and test dataset
- Train two models (Logistic regression and Random forest) and Performance Evaluation
- Optimize Random Forest Model
- Determine the most important features (predictors)

## Data Description

The dataset contained anonymized information relating to 107 enrolled students. 

The data included students’ grades (from 3 mini projects, 3 quizzes and 3 peer reviews and the final overall grade) as well as the course logs. The deadline for the three mini projects fell within 
weeks 3, 5 and 8 of the course, whereas the deadline for the quizzes fell within weeks 2, 4 and 8.

- **Status0**: course / lectures / content related (Course module viewed, Course viewed, Course activity completion updated, Course module instance list viewed, Content 
page viewed, Lesson started, Lesson resumed, Lesson restarted, Lesson ended)
- **Status1**: assignment related (Quiz attempt reviewed, Quiz attempt submitted, Quiz attempt summary viewed, Quiz attempt viewed, Quiz attempt started, Question 
answered, Question viewed, Submission re-assessed, Submission assessed, Submission updated, Submission created, Submission viewed)
- **Status2**: grade related (Grade user report viewed, Grade overview report viewed, User graded, Grade deleted, User profile viewed, Recent activity viewed, User report 
viewed, Course user report viewed, Outline report viewed)
- **Status3**: forum related (Post updated, Post created, Discussion created, Some content 
has been posted, Discussion viewed)
- **9 grades** (Week2_Quiz1, Week3_MP1, ... Week7_MP3)
- **36 logs** (Week1_Stat0, Week1_Stat1, Week1_Stat2, Week1_Stat3, ... Week9_Stat0, Week9_Stat1, Week9_Stat2, Week9_Stat3)

## Final confution matrix

After optimizing the random forest model with all predictors, I get a prediction model with an accuracy of 86%, and the confution matrix is as below.


![image](https://user-images.githubusercontent.com/97128113/201198160-4be7e673-4200-46a2-88e4-770845315647.png)


