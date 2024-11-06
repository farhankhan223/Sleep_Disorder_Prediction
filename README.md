# Sleep_Disorder_Prediction
This project aims to predict the presence and type of sleep disorders (Insomnia, Sleep Apnea, or None) based on various lifestyle and health factors such as age, BMI, physical activity, sleep duration, stress levels, and blood pressure.
# Prerequisites:
Before running the code, make sure you have the following libraries installed:
numpy
pandas
matplotlib
seaborn
scikit-learn
warnings
To install them, you can use pip:
bash
pip install numpy pandas matplotlib seaborn scikit-learn
# Key Features:
 Dataset: The Sleep Health and Lifestyle dataset contains 400 rows and 13 columns, including variables like gender, age, occupation, sleep quality, BMI, heart rate, and daily steps.
Analysis: Exploratory data analysis (EDA) identified key factors affecting sleep disorders: gender, occupation, and BMI. Males are more prone to Insomnia, while females experience more Sleep Apnea. Overweight and obese individuals are at a higher risk of sleep disorders.

# Models Used:
Decision Tree Classifier: Achieved 88% accuracy with an F1 score of 0.83.
Random Forest Classifier: Outperformed the Decision Tree with 89% accuracy, offering better prediction performance.
# Steps:
Data Preprocessing: Handled missing values, encoded categorical variables, and split the dataset into training and testing sets.
Model Building: Used Decision Tree and Random Forest classifiers to predict sleep disorders.
Evaluation: Evaluated the models using confusion matrix, classification reports, and visualizations.
# Key Findings:
Gender-based Differences: Females are more likely to suffer from Sleep Apnea, while males are more prone to Insomnia.
Occupation Impact: Nurses are at a higher risk for Sleep Apnea, while Sales Representatives show a higher incidence of Insomnia.
BMI Influence: Overweight and obese individuals have a higher likelihood of experiencing sleep disorders.

# Conclusion:
The Random Forest Classifier demonstrated better accuracy and predictive performance (89%) compared to the Decision Tree Classifier (88%). The analysis showed that lifestyle factors like gender, occupation, and BMI have a significant impact on sleep disorders. This model can be used for predicting sleep disorders based on lifestyle and health data, providing valuable insights for healthcare professionals in early detection and prevention.
