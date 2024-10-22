# Employee Attrition Analysis


## Objective:
The primary objective of this project was to identify the key predictors of employee attrition, allowing HR departments to craft strategies for improving employee retention. By leveraging data analytics and machine learning, we aimed to reveal the factors most strongly associated with employees leaving the company.

---

## Steps Involved:

### 1. Data Collection & Preprocessing:
- The dataset contained various employee features such as age, job role, monthly income, job satisfaction, business travel, work-life balance, and more.
- We performed data cleaning, handled missing values, and encoded categorical variables to make the data suitable for analysis.

### 2. Exploratory Data Analysis (EDA):
- Used visualizations like bar plots, histograms, and pie charts to understand the distribution of key variables.
- Investigated how variables such as age, overtime, monthly income, and job satisfaction differ between employees who stayed and those who left.

### 3. Correlation Analysis:
- Conducted correlation analysis to understand the relationships between different variables and attrition.
- Notable findings include higher attrition among employees who work overtime and those with lower job satisfaction.

### 4. Predictive Modeling:
- Built a Logistic Regression model to predict the likelihood of attrition based on employee data.
- Evaluated model performance using metrics like accuracy, precision, recall, and F1-score.

### 5. Key Insights:
- **Overtime** and **Marital Status** (single employees) were strong predictors of attrition.
- **Job Satisfaction** and **Work-Life Balance** showed negative correlations with attrition, meaning employees with lower satisfaction or poor balance were more likely to leave.
- **Business Travel** and **Distance from Home** were also contributing factors.

### 6. Model Evaluation:
- The model achieved an **accuracy of 86.62%**, indicating a strong predictive capability for employee attrition.
- Used confusion matrix and classification reports to assess performance and areas for improvement.

---

## Conclusion:
Through this analysis, we identified significant factors influencing employee attrition, such as **overtime**, **job satisfaction**, **work-life balance**, and **monthly income**. These insights can guide HR departments in taking proactive measures to retain employees, such as improving work-life balance, reducing excessive overtime, and ensuring competitive salaries.

---

## Tools Used:
- **Python:** For data manipulation, analysis, and modeling (libraries like Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn).
- **Machine Learning:** Logistic Regression for predicting employee attrition.
- **Data Visualization:** Used pie charts, bar plots, and box plots to visualize trends and patterns in the data.
