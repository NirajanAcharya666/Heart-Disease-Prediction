# Heart-Disease-Prediction
The steps and analysis performed in the project:

1. Importing necessary libraries: 

  The script starts by importing the required Python libraries, such as numpy, pandas, matplotlib, seaborn, and warnings. It also sets up the Jupyter notebook to display matplotlib plots inline.

2. Importing and understanding the dataset: 

  The script loads the heart disease dataset from a CSV file named "heart.csv" using pandas. It then prints out basic information about the dataset, including its shape, first few rows, and a sample of 5 rows. The script verifies that there are no missing values in the dataset.

3. Analysing the 'target' variable:

   The script analyzes the target variable 'target', which indicates the presence or absence of heart disease. It prints the counts and percentages of patients with and without heart problems.

4. Exploratory Data Analysis (EDA):
5. 
     The script performs EDA on various features like 'sex', 'cp' (chest pain type), 'fbs' (fasting blood sugar), 'restecg' (resting electrocardiographic results), 'exang' (exercise-induced angina), 'slope', 'ca' (number of major vessels colored by flourosopy), and 'thal'. It uses bar plots and count plots to visualize the distribution of these features concerning the presence or absence of heart disease.

6. Train-Test Split:

    The dataset is split into training and testing sets using the 'train_test_split' function from scikit-learn. The predictors (features) are separated from the target variable.

7. Model Fitting:
   The script fits several machine learning models to the data and evaluates their accuracy on the test set:

   

Logistic Regression: Achieves an accuracy score of approximately 85.25%.


Naive Bayes: Achieves an accuracy score of approximately 85.25%.

Support Vector Machine (SVM): Achieves an accuracy score of approximately 81.97%.

K-Nearest Neighbors (KNN): Achieves an accuracy score of approximately 67.21%.

Decision Tree: Achieves an accuracy score of approximately 81.97%.

Random Forest: Achieves the best accuracy score of approximately 95.08%.

XGBoost: Achieves an accuracy score of approximately 85.25%.

Neural Network: Achieves an accuracy score of approximately 80.33% (with 300 epochs).



Output Final Scores: The script prints the accuracy scores achieved by each algorithm and visualizes the results using a bar plot.
