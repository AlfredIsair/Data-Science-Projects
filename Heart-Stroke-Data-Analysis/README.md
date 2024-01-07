# Predicting Stroke Risk with Machine Learning

This repository explores the use of machine learning to predict the risk of stroke based on health and lifestyle factors. We'll analyze a dataset named `healthcare-dataset-stroke-data` containing information on various patient characteristics and their stroke status.

**Libraries Used:**

* **numpy:** For numerical computations and array operations.
* **matplotlib.pyplot:** For creating visualizations and plots.
* **pandas:** For data manipulation and analysis.
* **seaborn:** For advanced statistical visualizations.
* **scikit-learn:** For machine learning algorithms implementation (Logistic Regression, KNN, SVM).

**Data Overview:**

The dataset consists of the following columns:

* **id:** Unique identifier for each patient.
* **gender:** Gender of the patient.
* **age:** Age of the patient in years.
* **hypertension:** Whether the patient has hypertension (yes/no).
* **heart_disease:** Whether the patient has heart disease (yes/no).
* **ever_married:** Whether the patient is ever married (yes/no).
* **work_type:** Type of work the patient performs (e.g., Government Job, Private).
* **Residence_type:** Type of residence the patient has (e.g., Urban, Rural).
* **avg_glucose_level:** Average glucose level of the patient.
* **bmi:** Body mass index of the patient.
* **smoking_status:** Smoking status of the patient (yes/no/former).
* **stroke:** Target variable indicating whether the patient has stroke (yes/no).

**Machine Learning Models:**

We'll train and compare three popular machine learning algorithms for predicting stroke risk:

* **Logistic Regression:** A linear model that predicts the probability of an event occurring.
* **K-Nearest Neighbors (KNN):** Classifies data points based on the k most similar data points in the training set.
* **Support Vector Machine (SVM):** Finds a hyperplane that best separates the data points into different classes.

**Analysis Workflow:**

1. **Data Loading and Exploration:** Load the dataset using pandas and analyze its characteristics like distribution of features and correlation between them.
2. **Data Preprocessing:** Clean and prepare the data for model training by handling missing values, encoding categorical features, and scaling numerical features.
3. **Feature Selection (Optional):** Identify the most relevant features for predicting stroke risk using methods like correlation analysis or feature importance measures.
4. **Model Training and Evaluation:** Split the data into training and testing sets, train each model on the training set, and evaluate their performance on the testing set using metrics like accuracy, precision, recall, and F1-score.
5. **Model Comparison and Selection:** Compare the performance of different models and choose the one that performs best on the testing set.
6. **Interpretation and Insights:** Analyze the model's predictions to understand how different factors influence the risk of stroke and identify potential risk factors.

**Expected Outcome:**

This analysis aims to develop a machine learning model that can accurately predict the risk of stroke based on readily available patient information. This can potentially help healthcare professionals identify individuals at high risk of stroke and implement preventive measures to improve patient outcomes.




