# Main-Project-
HR Analytics- Predict Employee Attrition

## HR ANALYTICS – PREDICT EMPLOYEE ATTRITION
This project analyzes employee attrition using classification models and explains the driving factors behind resignations using SHAP. It also provides visual insights using Power BI.

## OBJECTIVE
Identify key factors influencing employee resignation. Build machine learning models to predict attrition. Interpret predictions using SHAP. Create interactive dashboards in Power BI. Recommend actionable strategies to prevent future attrition.

## TOOLS AND TECHNOLOGIES
Python: Pandas, Scikit-learn, SHAP, Seaborn
Power BI: Data visualizations & slicing
SHAP (for model explainability)
Colab: Model development
Excel: Input dataset
GitHub: Version control

## EDA (Exploratory Data Analysis)
Identified key factors affecting attrition
Analyzed department-wise trends and salary-level impact
Visualizations done using Seaborn and Power BI

## MODEL BUILDING
Model Used: Logistic Regression
Feature engineering: Label encoding for categorical columns
Train-test split applied

## EVALUATION
Classification Report: classification_report.csv
Confusion Matrix: confusion_matrix.png
Accuracy, Precision, Recall, and F1-score computed
Project structure
hr_analytics_attrition_dataset.xlsx

## DATASET
File: hr_analytics_attrition_dataset.xlsx
Contains features like:
Satisfaction Level
Last Evaluation
Number of Projects
Average Monthly Hours
Time Spent at Company
Work Accident
Promotion in Last 5 Years
Department
Salary
Attrition Label (Left)

## NOTEBOOK
HR_Analytics_Attrition_Model.ipynb
Python notebook (Logistic & Decision Tree)

Accuracy model report+confusion matrix.pdf
Accuracy, Confusion Matrix, SHAP insights

## PDF 
attrition_prevention_suggestions.pdf

## Prevention strategies
classification_report.csv

## Model performance metrics
confusion_matrix.png

## Presentation slides
model metrics summary slide.pptx

## Slide with classification metrics
Attrition_Analysis

## POWER BI DASHBOARD
File: HR_Attrition_Analysis.pbix

## INTERACTIVE VISUALS
Attrition by department
Salary vs. attrition
Time spent at company vs. attrition
Slicer to filter employee left/stayed

##  SHAP ANALYSIS
Used SHAP to explain model predictions
Identified key influencers like satisfaction level, monthly hours, and promotion status

## README.md
for project documentation

## PROJECT REPORT.PDF 
HR Analytics - Predict Employee Attrition

## HOW TO RUN(LOCALLY) 
Clone the repository
Install dependencies:
pip install pandas seaborn scikit-learn streamlit joblib shap

## INSIGHTS AND RECOMMENDATIONS
 1.Employees with low satisfaction and no promotions in the last 5 years are at higher risk of leaving.

2.Departments with higher workloads should be monitored.

3.Increasing employee engagement and internal mobility may reduce attrition.
