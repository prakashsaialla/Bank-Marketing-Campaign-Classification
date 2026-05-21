# Bank Marketing Campaign Classification Using Supervised Learning Models

## Project Overview
This project focuses on predicting whether a customer will subscribe to a bank term deposit product using supervised machine learning techniques. The objective was to improve marketing campaign efficiency by identifying high-probability customers for targeted outreach and conversion optimization.

The project combines exploratory data analysis (EDA), predictive analytics, feature engineering and classification modeling to generate actionable business insights for customer targeting and campaign strategy optimization.

---

## Business Problem
Traditional bank marketing campaigns often result in high acquisition costs and low conversion rates due to inefficient customer targeting.

This project aims to:
- Predict customer subscription likelihood
- Improve campaign targeting efficiency
- Reduce customer acquisition costs
- Optimize marketing resource allocation
- Identify high-impact customer behavior patterns

---

## Dataset Information
- Dataset Size: 10,000+ customer records
- Data Type: Banking marketing campaign dataset
- Target Variable:
  - `y_binary`
    - 1 = Customer subscribed
    - 0 = Customer did not subscribe

### Features Used
#### Numerical Variables
- Age
- Campaign
- Previous
- Pdays
- Euribor3m
- Nr.employed

#### Categorical Variables
- Job
- Marital Status
- Housing
- Loan
- Poutcome

---

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Excel
- XLMiner
- Matplotlib
- Machine Learning
- Predictive Analytics

---

## Project Workflow

### 1. Data Preprocessing
- Random sampling of 10,000+ records
- Missing value analysis
- Feature selection
- Data cleaning and transformation
- Correlation analysis

### 2. Exploratory Data Analysis (EDA)
- Customer behavior analysis
- Campaign trend analysis
- Correlation heatmaps
- Histograms and scatterplots
- Feature importance evaluation

### 3. Machine Learning Models
Implemented and compared multiple supervised learning models:

- Logistic Regression
- Neural Network Classification
- Decision Tree Classification
- K-Nearest Neighbors (KNN)

---

## Model Evaluation Metrics
The models were evaluated using:
- Accuracy
- Precision
- Sensitivity (Recall)
- F1-Score
- ROC-AUC
- Classification Threshold Optimization

---

## Key Results

### Best Performing Model
✅ Classification Tree

### Performance Highlights
- Achieved 91%+ classification accuracy
- Classification Tree ROC-AUC: ~0.846
- Neural Network ROC-AUC: ~0.827
- Improved customer targeting capability
- Identified key subscription drivers and campaign patterns

---

## Key Business Insights
- Customers with positive previous campaign outcomes had higher conversion probability.
- Economic indicators significantly influenced subscription behavior.
- Longer customer interaction duration increased conversion likelihood.
- Cutoff threshold optimization improved marketing effectiveness and lead capture.

---

## Business Recommendations
- Deploy Classification Tree model for campaign targeting
- Focus outreach on high-likelihood customer segments
- Optimize classification thresholds for better recall
- Continuously monitor model drift and campaign performance

---


## Future Improvements
- Random Forest Classification
- XGBoost Implementation
- Ensemble Learning Models
- Real-Time Prediction Pipeline
- Deployment using Flask or Streamlit

---

## Author
Prakash Sai Alla

MS Business Analytics  
University of Massachusetts Amherst
