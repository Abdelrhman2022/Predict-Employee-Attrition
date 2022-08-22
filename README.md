# Predict Employee Attrition
**Employee Attrition** is a huge problem across industries and generally costs the company a lot for hiring, retraining, productivity and work loss for each employee who leaves. Price and Waters, a boutique data science consulting firm, is looking to build a Machine Learning model to predict whether an Employee might quit. Using this model, they might plan human intervention to alleviate the issues faced by the employee. The firm is also interested in specific features that are highly indicative of attrition. The company in a pilot program, recorded employee data. The company collected employee performance data for some of the months randomly for each employee to understand it in the context of attrition. The company wants you to predict whether an employee would quit in the near future, given the data and to discover features indicative of attrition.

I perform turnover analysis project by using Python’s Scikit-Learn library. We use Logistic Regression, Random Forest, and Support Vector Machine as classifier for employee attrition and measure the accuracy of models that are built.

# Dataset Description
The dataset consists of 25491 obseravtions and 10 variables. Each row in dataset represents an employee; each column contains employee attributes:

* satisfaction_level (0–10)
* last_evaluation (Time since last evaluation in years)
* number_projects (Number of projects completed while at work)
* average_monthly_hours (Average monthly hours at workplace)
* time_spend_company (Time spent at the company in years)
* Work_accident (Whether the employee had a workplace accident)
* left (Whether the employee left the workplace or not (1 or 0))
* promotion_last_5years (Whether the employee was promoted in the last five years)
* Department (in which they work for)
* salary (Relative level of salary)

# Results & Conclusion

**Random Forest is the best classfier for predicting employee attrition for our dataset. Some of the most important factors on which employee attrition depends are:**


* Satisfaction Level: **55.35%**
* Time since last evaluation: **37.73%**
* Work Accident: **2.47%**
* Low Salary: **1.18%**
* High Salary: **0.93%**
* Career Advancement ( If Promoted in last five years or not): **0.50%**


After Tuning Model Found Best Score is **95.68%** 

Hyperparameters: 
**['n_estimators': 1000,
 'min_samples_split': 2,
 'min_samples_leaf': 1,
 'max_features': 'sqrt',
 'max_depth': 25]**



After Tuning Model Found Best Score is **96.55%** 

Hyperparameters: 
**['max_depth': 25,
 'max_features': 'sqrt',
 'min_samples_leaf': 1,
 'min_samples_split': 2,
 'n_estimators': 1000]**


