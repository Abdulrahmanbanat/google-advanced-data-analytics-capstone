#  Employee Attrition Prediction – Capstone Project

This case study showcases the skills I’ve gained from the **Google Advanced Data Analytics Certificate**. I applied these skills to complete the tasks of a data analyst by building a machine learning model to predict which employees are likely to leave a company. The goal is to help HR teams take proactive action and improve employee retention.

---

##  Scenario

A consulting firm is experiencing high employee turnover. The HR department wants to understand what factors influence attrition and predict which employees are at risk of leaving. By analyzing internal HR data and building predictive models, the goal is to identify trends and take steps to reduce voluntary turnover.

---

##  About the Company

The company operates in a fast-paced environment with multiple departments and employees at various performance and satisfaction levels. The HR team provided anonymized employee data, including:

- Satisfaction level  
- Evaluation score  
- Number of projects  
- Monthly working hours  
- Promotion history  
- Department and salary level  

HR wants to understand the drivers of attrition and apply machine learning to support retention strategies.

---

##  Ask

### Business Task
Analyze employee data and build a predictive model that classifies whether an employee will leave. Use the results to deliver actionable recommendations to reduce attrition.

### Stakeholders
- **HR Managers** – Need tools to predict attrition and take action.
- **Team Leaders** – Want to identify overworked or dissatisfied employees.
- **Executives** – Make strategic decisions based on attrition patterns.

---

##  Prepare & Process

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
- Detected outliers
- Prepared final dataset for modeling

---

## 📊 Analyze

Performed Exploratory Data Analysis (EDA) to discover key patterns:
- Low satisfaction and high workload linked to attrition
- Promotions and salary levels had weaker correlations
- Certain departments had higher turnover rates

---

##  Construct – Model Building

### Algorithm
- **Random Forest Classifier**  
- Tuned using **GridSearchCV**

### Performance Metrics
- **Accuracy:** 98%  
- **Precision:** 96%  
- **Recall:** 93%  
- **F1-score:** 94%  
- **AUC:** 96%

### Insights
- Key factors: satisfaction level, number of projects, evaluation score
- Overworked or low-performing employees are more likely to leave

---

### Summary
The model successfully identifies employees at risk of leaving with high precision and recall. It confirms that satisfaction and workload are major predictors.

## Recommendations
ased on these findings, I recommend the company take active steps to improve employee well-being. This could include offering more flexible working hours, mental health support, and reducing excessive workloads. Providing regular training and career development opportunities can boost employee motivation and performance. Additionally, using this model as an ongoing tool will allow managers to identify employees at risk of leaving early and provide targeted support before it’s too late.

## Next Steps 

Moving forward, we should enhance the model by incorporating more detailed data such as contract types and salary breakdowns to gain a more comprehensive understanding. . It is important to keep the model regularly updated with new data and consistently review its fairness to ensure ethical and effective use. From a business perspective, the company should consider capping the number of projects assigned to each employee to prevent burnout and investigate why employees with around four years of tenure show low satisfaction, potentially offering promotions or additional support. Additionally, the company should either reward employees who work overtime or adjust expectations to avoid requiring excessive working hours. Clear communication of overtime pay policies and workload expectations is essential. Furthermore, holding company-wide and team-level discussions can help identify and improve workplace culture. Finally, the performance evaluation system should be reviewed to ensure fair recognition that appropriately reflects employees’ efforts, avoiding bias toward those who work excessive hours.
