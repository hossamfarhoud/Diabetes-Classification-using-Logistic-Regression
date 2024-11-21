# Diabetes-Classification-using-Logistic-Regression
Overview
This project is a Machine Learning-based classification system to predict whether an individual is diabetic or not using the PIMA Indians Diabetes Dataset. The implementation demonstrates the use of Logistic Regression and explores various aspects of data preprocessing, visualization, and model evaluation.

Key Features:
Exploratory Data Analysis (EDA) to understand the dataset structure and distributions.
Feature engineering, including standardization using StandardScaler.
Implementation of Logistic Regression for classification.
Visualization of feature distributions, correlations, and outcome balance.
Evaluation of the model's performance using metrics like precision, recall, and accuracy.
Predictive analysis on new input data.
Visualization of feature importance based on Logistic Regression coefficients.
Dataset
The dataset used for this project is the PIMA Indians Diabetes Dataset. It contains the following columns:

Pregnancies: Number of pregnancies
Glucose: Plasma glucose concentration
BloodPressure: Diastolic blood pressure (mm Hg)
SkinThickness: Triceps skinfold thickness (mm)
Insulin: 2-hour serum insulin (mu U/ml)
BMI: Body mass index (weight in kg/(height in m)^2)
DiabetesPedigreeFunction: Diabetes pedigree function (genetic predisposition)
Age: Age in years
Outcome: Target variable (0: Non-diabetic, 1: Diabetic)
Project Workflow
1. Importing Libraries
Essential libraries like Pandas, NumPy, Matplotlib, and Scikit-learn are used for data manipulation, visualization, and model building.

2. Loading the Dataset
The dataset is loaded into a Pandas DataFrame for analysis and manipulation.

3. Data Exploration
Checked for missing values and data types.
Visualized the distribution of features and the target variable (Outcome).
4. Data Preprocessing
Features were standardized using Scikit-learn's StandardScaler to normalize data for better model performance.
Dataset split into training and testing sets (80:20).
5. Model Implementation
Logistic Regression was applied as the primary classifier.
Model training and prediction steps were performed.
6. Model Evaluation
Evaluated the model using accuracy, precision, and recall metrics.
Plotted a bar chart to visualize the balance of the Outcome variable.
7. Feature Importance
Visualized feature importance using the absolute values of Logistic Regression coefficients.
8. Prediction on New Input
Demonstrated prediction for a single input using the trained model.
Results
Achieved a robust classification system capable of predicting diabetes with high accuracy.
Provided insights into feature importance and their contributions to model predictions.
Visualizations
The project includes:

Correlation Heatmap to explore relationships between features.
Feature Distributions to understand data variability.
Outcome Balance to visualize target variable distribution.
Feature Importance Plot highlighting the influence of each feature on model predictions.
Usage
Clone this repository.
Install required libraries using pip install -r requirements.txt.
Run the Jupyter Notebook or Python script to execute the model.
Future Enhancements
Explore other machine learning algorithms like Random Forest and SVM.
Experiment with hyperparameter tuning to further improve model performance.
Use additional datasets to enhance the generalizability of the model.
