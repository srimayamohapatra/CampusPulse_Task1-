CampusPulse Project – Task 1: Relationship Prediction from Student Lifestyle Data
This project is part of the CampusPulse initiative at IIT Guwahati. The goal is to explore student lifestyle, academic performance, and behavioral data to understand and predict romantic relationship likelihood using machine learning.

📌 Objective
Use a student survey dataset to:

Clean and preprocess the data

Uncover patterns and correlations using Exploratory Data Analysis (EDA)

Identify anonymized features based on statistical behavior

Build and evaluate classification models

Interpret predictions using SHAP for transparency

Match visual decision boundaries to classifiers

📁 Structure of the Notebook
The notebook is organized into clearly labeled sections:

Level 1: Variable Identification Protocol
Analyzes Feature_1, Feature_2, and Feature_3 using histograms, correlation heatmaps, and scatter plots

Guesses the original identity of anonymized features based on data behavior

Level 2: Data Integrity Audit
Checks for missing values

Applies appropriate imputation techniques with justifications

Level 3: Exploratory Insight Report
Asks and answers five insightful EDA questions about student life (e.g., impact of absences on grades)

Uses plots (bar charts, violin plots, etc.) with clear captions

Level 4: Relationship Prediction Model
Trains and evaluates classifiers (Logistic Regression, Decision Tree, Random Forest, Naive Bayes)

Compares their accuracy and confusion matrices

Level 5: Model Reasoning & SHAP Interpretation
Visualizes feature importance using SHAP summary plots

Shows local SHAP force plots for individual students

Explains which features most influence predictions

Bonus Level: Decision Boundary Matching
Matches unlabeled decision boundary plots to the correct ML model

Explains visual characteristics that distinguish classifiers

🛠️ How to Run
Open CampusPulse_Task1.ipynb in Jupyter Notebook or VS Code.

Run cells sequentially.

Install missing libraries with pip if needed (e.g., shap, seaborn, matplotlib).

📊 Libraries Used
pandas, numpy

matplotlib, seaborn

scikit-learn

shap


