# 💼 Employee Attrition Prediction – Capstone Project

This case study showcases the skills I’ve gained from the **Google Advanced Data Analytics Certificate**. I applied these skills to complete the tasks of a data analyst by building a machine learning model to predict which employees are likely to leave a company. The goal is to help HR teams take proactive action and improve employee retention.

---

## 🧠 Scenario

A consulting firm is experiencing high employee turnover. The HR department wants to understand what factors influence attrition and predict which employees are at risk of leaving. By analyzing internal HR data and building predictive models, the goal is to identify trends and take steps to reduce voluntary turnover.

---

## 🏢 About the Company

The company operates in a fast-paced environment with multiple departments and employees at various performance and satisfaction levels. The HR team provided anonymized employee data, including:

- Satisfaction level  
- Evaluation score  
- Number of projects  
- Monthly working hours  
- Promotion history  
- Department and salary level  

HR wants to understand the drivers of attrition and apply machine learning to support retention strategies.

---

## 📌 Ask

### Business Task
Analyze employee data and build a predictive model that classifies whether an employee will leave. Use the results to deliver actionable recommendations to reduce attrition.

### Stakeholders
- **HR Managers** – Need tools to predict attrition and take action.
- **Team Leaders** – Want to identify overworked or dissatisfied employees.
- **Executives** – Make strategic decisions based on attrition patterns.

---

## 🧹 Prepare & Process

### Data Source
- Internal HR dataset (CSV format)
- No personally identifiable information (PII) included

### Tools Used
- Python (Pandas, NumPy, Scikit-learn)
- Jupyter Notebook

### Data Preparation Steps
- Removed missing and duplicate values  
- Encoded categorical features (e.g., salary, department)  
- Engineered new features where necessary  
- Detected and removed outliers (e.g., extreme working hours)  
- Prepared final dataset for modeling

---

## 📊 Analyze

Performed Exploratory Data Analysis (EDA) to discover key patterns:
- Low satisfaction and high workload linked to attrition
- Promotions and salary levels had weaker correlations
- Certain departments had higher turnover rates

---

## 🤖 Construct – Model Building

### Algorithm
- **Random Forest Classifier**  
- Tuned using **GridSearchCV**

### Performance Metrics
- **Accuracy:** ~98%  
- **Precision:** ~96%  
- **Recall:** ~93%  
- **F1-score:** ~94%  
- **AUC:** ~96%

### Insights
- Key factors: satisfaction level, number of projects, evaluation score
- Overworked or low-performing employees are more likely to leave

---

## 🚀 Execute – Business Recommendations

### Summary
The model successfully identifies employees at risk of leaving with high precision and recall. It confirms that satisfaction and workload are major predictors.

### Recommendations
- Introduce flexible work hours and mental health programs  
- Reduce overloading employees with too many projects  
- Provide training and support to improve performance  
- Use the model continuously to monitor employee risk levels

---

## 🔄 Next Steps

- Add more features (e.g., salary breakdown, contract type)  
- Automate retraining with new data  
- Ensure fairness and avoid bias in predictions

---

## 🔐 Ethical Considerations

- Respect employee privacy  
- Do not use model results to unfairly penalize staff  
- Use predictions to **support**, not control, employees

---

## 📁 Deliverables

- **Notebook**: Data cleaning, analysis, and model training  
- **Model File**: Trained Random Forest saved as a `.pkl` file  
- **Report**: Summary of findings and recommendations  
- **Dataset**: Cleaned HR dataset used in the project
