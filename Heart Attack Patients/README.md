# Heart Attack Patients

In this project, I will work with the data in the file ’patients.csv’, that contains some measurements about patients, who experienced angina, which can typically be a symptom of coronary
artery disease. You can find the following variables in the data:

• **age**: age of the patient

• **gender**: gender of the patient (0 - female, 1 - male)

• **pain**: intensity of the chest pain (integer value, 0-3)

• **blood pressure**: blood pressure of the patient

• **cholesterol**: cholesterol in blood, mg/dl

• **blood sugar**: indicating whether the blood sugar level is normal or not (1 when it is above 120 mg/dl, and 0 otherwise)

• **heart rate**: maximum heart rate

• **exercise**: whether the chest pain was induced by some physical exercise or not (1 or 0)

• **outcome**: 1 for patients with heart attack, and 0 for patients who did not have heart attack


**I will perform K-Means clustering on the dataset and perform the following steps:**

• Scale all the variables.

• Determine the optimal number of clusters using the elbow method, and perform k-means clustering with the chosen value (set random state = 0).

• Identify the average of each variable in each cluster (the original, not the scaled variables), and try to analyze each cluster.

• Perform k-means clustering now with k=2. Compare the created two clusters to the ’outcome’ column. Try to determine if the created clusters separate patients who had heart attack from the other patients, or are the two clusters a mix of unhealthy (have heart attack) and healthy (no heart attack) patients.
