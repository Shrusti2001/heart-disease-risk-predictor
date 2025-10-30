# Heart Disease Prediction Using Machine Learning

## Overview
This project uses real clinical data to predict the presence of heart disease using classic machine learning algorithms. By combining robust data cleaning, exploratory data analysis (EDA), and model building, the analysis shows how data science can improve healthcare decision-making and risk assessment.

## Objectives
- Identify key features linked to heart disease
- Compare popular classification models (Logistic Regression, Decision Tree, Random Forest)
- Communicate findings through charts and plain language interpretation

## Data
- **Source:** UCI Heart Disease Dataset ([link](https://archive.ics.uci.edu/dataset/45/heart+disease))
- Features include age, sex, chest pain, cholesterol, blood pressure, ECG results, and more

## Methodology
- **Data Cleaning:** Removed columns/rows with significant missing data and converted categorical variables for modeling
- **EDA:** Visualized class balance, feature distributions, and feature-target relationships
- **Modeling:** Built and evaluated multiple classifiers using accuracy, precision, recall, and F1-score

## Results

| Model              | Accuracy | Precision (0/1) | Recall (0/1) | F1-score (0/1) |
|--------------------|----------|-----------------|--------------|----------------|
| LogisticRegression |  0.85    | 0.85 / 0.86     | 0.85 / 0.86  | 0.85 / 0.86    |
| DecisionTree       |  0.70    | 0.69 / 0.71     | 0.68 / 0.71  | 0.68 / 0.71    |
| RandomForest       |  0.78    | 0.77 / 0.79     | 0.77 / 0.79  | 0.77 / 0.79    |

- **Top performer:** Logistic Regression achieved 85% accuracy, with balanced precision and recall for both classes.
- **Clinical impact:** The model identifies at-risk patients while minimizing false negatives, supporting doctors in early heart disease detection.

## How to Run
1. Clone the repo and download `heart_disease_uci.csv` to the repo folder.
2. Launch `Heart_Disease_Analysis_Modeling.ipynb` in Jupyter or Colab.
3. Follow the notebook sections. All code is explained with markdown and comments.

## Key Insights
- Classic machine learning models provide robust performance on clinical datasets
- Good data cleaning and feature engineering are essential for model accuracy
- Simple models (Logistic Regression) can outperform more complex ones for tabular health data

## Author
Shrusti Hiremath 
Aspiring Data Analyst, passionate about healthcare and analytics  
Connect with me: www.linkedin.com/in/shrusti-hiremath 
