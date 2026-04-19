#  Employee Performance Analysis & Prediction

##  Overview

This project analyzes employee data from **INX Future Inc.** to identify the key factors affecting employee performance and build predictive models for performance rating.

The company observed a **decline in employee performance and client satisfaction**, and this project aims to provide **data-driven insights and actionable recommendations** without negatively impacting employee morale.

---

##  Business Problem

* Decline in employee performance index
* Drop in client satisfaction (~8%)
* Need to identify **non-performing employees** without harming overall morale
* Need a **data-driven hiring and evaluation system**

---

##  Objectives

1. Analyze **department-wise performance trends**
2. Identify **top factors influencing employee performance**
3. Build a **machine learning model to predict performance rating**
4. Provide **recommendations to improve performance**

---

##  Dataset Details

* Format: Excel (`.xls`)
* Total Features: **24**
* Target Variable: **PerformanceRating (2, 3, 4)**

###  Key Features

* Age
* Department
* Job Role
* Job Satisfaction
* Environment Satisfaction
* Work-Life Balance
* Training Times Last Year
* Experience (Total & Role-based)
* Salary Hike Percentage
* Attrition, Overtime, Travel Frequency

---

##  Exploratory Data Analysis (EDA)

* Univariate analysis of all features
* Target distribution analysis
* Department-wise performance comparison
* Correlation analysis to identify important features

---

##  Feature Engineering

* Converted ordinal categorical features properly
  (e.g., Job Satisfaction, Work-Life Balance, etc.)
* Encoded categorical variables
* Feature scaling using **StandardScaler**

---

##  Machine Learning Models Used

### Models Implemented

* Logistic Regression
* Random Forest Classifier
* Support Vector Machine (SVM)
* XGBoost Classifier
* Gradient Boosting

### Model Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1 Score (Macro & Weighted)

---

##  Model Training Pipeline

1. Data preprocessing & encoding
2. Train-test split (stratified)
3. Feature scaling
4. Model training
5. Hyperparameter tuning (GridSearchCV)
6. Performance evaluation

---

##  Key Insights

* Employee performance is strongly influenced by:

  * Job Satisfaction
  * Environment Satisfaction
  * Work-Life Balance
  * Training frequency
* Lack of promotions and low training exposure correlate with lower performance
* Some departments consistently outperform others

---

##  Business Recommendations

* Increase **training programs** for employees
* Improve **work-life balance policies**
* Focus on **employee satisfaction metrics**
* Provide **regular promotions and growth opportunities**
* Use predictive model for **better hiring decisions**

---

##  Project Structure

```bash
├── Employee_performance_analysis.ipynb
├── Employee_Performance_Data.xls
├── README.md
```

---

##  How to Run

```bash
# Clone the repository
git clone https://github.com/hridhya92/employee-performance-analysis-IABAC-project.git

# Navigate to project folder
cd employee-performance-analysis-IABAC-project

# Run notebook
jupyter notebook
```

---

##  Tech Stack

###  Language

* Python

###  Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost

###  Tools

* Jupyter Notebook

---

##  Future Improvements

* Deploy as a **Streamlit dashboard**
* Add **real-time employee monitoring system**
* Improve model performance with advanced tuning
* Build **HR recommendation engine**

---

##  Author

**Hridhya E K**
---

##  Conclusion

This project demonstrates how **data analytics + machine learning** can solve real-world HR problems by identifying performance drivers and enabling predictive decision-making.

---
