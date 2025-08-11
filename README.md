# Predicting employees likely to quit
The main objective of this project is to analyze a dataset in depth and develop a predictive model that supports the HR department in reducing employee turnover.

## Overview
High turnover and disengagement cost businesses time, money, and morale. The fictional company Sailifort Motors wants to identify key factors contributing to employee turnover and take some initiatives to improve employee satisfaction levels. The HR department have the following question: what’s likely to make the employee leave the company? The goals in this project is to analyze the data collected by the HR department and to build a model that identifiy the key factors contirubtin gto employee turnover. 

## Objectives 
-How workload and tenure affect employee well-being and output?
-Whether key outcomes such as hours work or salary tier from other attributes can be predicted?
-How insights can guide management decisions to reduce turnover? 
 
## Dataset used **https://www.kaggle.com/datasets/giripujar/hr-analytics**
The primary data source used for this project is the Kaggle dataset. 

## Business Understanding
- Employee performance and retention are critical drivers of organizational success. High-performing employees contribute to productivity, innovation, and revenue growth, while high
  turnover can lead to significant recruitment, training, and opportunity costs. It is important to understand what factors lead to employee turnover.
   
  **Business Goals** 
- Identify what factors most influence employee satisfaction  
  Access work load to detirmine optimal number of projects or monthly hours that supports both high performance and satisfaction?
- Understand the impact of promotion on employee satisfaction and rention. 
- Compare departmental performance and satisfaction trends to target improvements
- Which departments have the most turnover?
- 
  ## Data Understanding
  The dataset represents employee records from an HR system, containing a mix of numerical and categorical variables. These attributes describe satisfaction, performance,                   workload,tenure, and compensation, providing the basis for both exploratory and predictive analysis.

  **Dataset Structure**
  In this dataset, there are 14,999 rows, 10 columns. 

  **Cleaned Data**
  -Gathered descriptive statistics about the data
  -Renamed columns
  -Checked missing values
  -Checked duplicates
  -Checked ouliers
  
  **Exploratory Data Analysis**
  -Investigate and summarize data using descriptive statistics and visualization

 <img width="748" height="508" alt="image" src="https://github.com/user-attachments/assets/5ab44d8e-c4cb-4e80-a89e-b7f37ef63b8e" />

  The correlation heatmap confirms that the number of projects, monthly hours, and evaluation scores all have some positive correlation with each other, and whether an employee leaves is   negatively correlated with their satisfaction level.

  ## Modeling and Evaluation
  -A random forest model comprising 100 decision trees was used to determine feature importances for employee leaving. The below plot shows that last evaluation, number of projects, tenure and overworked had the highest importance for employees leaving. The overall model performed with 86% accuracy and 72% precision.

<img width="686" height="388" alt="image" src="https://github.com/user-attachments/assets/77aa7df8-4855-45b1-865a-5bb849c6ef7e" />

   ## Conclusion
   Employees are leaving the company as a result of poor management. Employees leaving is tied to longer working hours, many projects, and lower satisfaction levels. Working long hours      and not receiving promotions or good evalations scores makes employees dissatisfied.

   **Recommendations**
   -Cap the number of projects that employees can work on.
   -Consider promoting employees who have been with the company for atleast four years, or conduct further investigation about why four-year tenured employees are so dissatisfied.
   -Either reward employees for working longer hours, or don't require them to do so.
   -If employees aren't familiar with the company's overtime pay policies, inform them about this. If the expectations around workload and time off aren't explicit, make them clear.
   -Hold company-wide and within-team discussions to understand and address the company work culture, across the board and in specific contexts.
   -High evaluation scores should not be reserved for employees who work 200+ hours per month. Consider a proportionate scale for rewarding employees who contribute more/put in more          effort. 

  
   

  

  
  

  
