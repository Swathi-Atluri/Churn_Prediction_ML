# **Telecom Customer Churn Prediction**  

## **Overview**  
This project predicts customer churn in a telecom company using machine learning models. The dataset includes customer demographics, subscription details, and billing information to identify factors contributing to churn.  

## **Dataset**  
- **Source**: `/kaggle/input/telecom-customer-churn-insights-for-analysis/customer_churn_data.csv`  
- **Contains**:  
  - Customer demographics  
  - Subscription details  
  - Churn labels  

## **Steps**  

### 1. Problem Scoping  
- Define objectives, business problems, and key metrics.  

### 2. Data Collection & Preparation  
- Load data and clean it.  
- Handle missing values and encode categorical variables.  
- Split data into training and testing sets.  

### 3. Exploratory Data Analysis  
- Generate statistical summaries.  
- Visualize key relationships and patterns.  

### 4. Modeling & Evaluation  
- Train models: **Random Forest, XGBoost, Neural Network**, etc.  
- Tune hyperparameters using **GridSearchCV**.  
- Evaluate models using **F1-score** and other metrics.  

## **Hyperparameter Tuning**  
- **GridSearchCV**: Applied to Random Forest, XGBoost, and Neural Network models.  
- **Cross-Validation**: 5-fold used to optimize **F1-score**.  

## **Evaluation Metrics**  
- **Accuracy**  
- **Precision**  
- **Recall**  
- **F1-score**  
- **Confusion Matrix**  

## **Results**  
- The best-performing model is selected based on the **highest F1-score**.  
