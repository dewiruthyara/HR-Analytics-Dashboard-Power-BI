# HR Analytics Dashboard | Power BI

## 1. Project Overview

This project focuses on analyzing employee data to gain insights into workforce composition, employee attrition, and termination patterns. Using Microsoft Power BI, an interactive HR Analytics Dashboard was developed to transform employee data into meaningful visualizations that support workforce monitoring and data-driven decision-making.

### Problem Statement

Employee turnover is an important indicator of workforce stability. However, without a comprehensive view of employee demographics, employment status, and termination patterns, organizations may find it difficult to identify potential issues related to employee retention.

### Objectives

- Analyze workforce composition based on demographic and employment characteristics.
- Monitor employee attrition by identifying the proportion of active and terminated employees.
- Identify the most frequently reported reasons for employee termination.
- Explore factors associated with voluntary employee termination.
- Present actionable insights through an interactive dashboard.

## 2. Data Source

The dataset used in this project is available on Google Drive:

[HR Analytics Dataset – Google Drive](https://drive.google.com/drive/folders/19oQkbd7WIVKlTq1DV0fk_POPvGxtI6EA)

The dataset contains employee-related information, including:
- Employee demographics (sex, date of birth, citizenship, and marital status).
- Employment information (department, position, and date of hire).
- Employee status and termination reasons.
- Salary information.

## 3. Analysis Workflow

The analysis was conducted through the following steps:

1. **Data Understanding**  
   Reviewed the dataset structure and identified relevant variables for workforce and attrition analysis.

2. **Data Preparation**  
   Prepared employee data for analysis and visualization in Power BI.

3. **Key Performance Indicator (KPI) Development**  
   Established key HR metrics, including total employees, average salary, active employees, terminated employees, and attrition rate.

4. **Exploratory Data Analysis (EDA)**  
   Analyzed workforce distribution based on demographics, departments, age groups, and employment status.

5. **Attrition Analysis**  
   Examined employee turnover patterns, termination reasons, and yearly attrition trends.

6. **Termination Factor Analysis**  
   Utilized Power BI's Key Influencers visual to explore factors associated with voluntary employee termination.

7. **Dashboard Development**  
   Designed an interactive dashboard consisting of four main sections: Overview, Attrition, Termination Insights, and Employee Details.

## 4. Dashboard Preview

### Overview
Provides a general overview of workforce composition, including total employees, average salary, attrition rate, and employee demographics.

![HR Dashboard Overview](<img width="996" height="576" alt="HR Dashboard Overview" src="https://github.com/user-attachments/assets/cd2ae36c-c20e-4f79-b40c-4e8848dc6630" />
)

### Attrition
Highlights employee turnover metrics, active versus terminated employees, attrition trends, and the distribution of termination reasons.

![HR Dashboard Attrition](<img width="996" height="576" alt="HR Dashboard Attrition" src="https://github.com/user-attachments/assets/0c83681d-6ccb-428e-a794-311096676fce" />
)

### Termination Insights
Uses Power BI's Key Influencers visual to identify termination reasons associated with a higher likelihood of voluntary termination.

![HR Dashboard Termination Insights](<img width="996" height="576" alt="HR Dashboard Termination Insights" src="https://github.com/user-attachments/assets/82a29266-8d0e-4ea4-b6be-d86cc02f72b0" />
)

### Employee Details
Displays employee-level information with interactive filters for more detailed exploration.

![HR Dashboard Employee Details](<img width="996" height="576" alt="HR Dashboard Employee Details" src="https://github.com/user-attachments/assets/1769369b-4da9-4fbb-a68f-15b740499db0" />
)

## 5. Key Insights

**1. Employee Attrition Reached 50.24%**

Out of 311 employees, 104 were recorded as terminated, while 207 remained active. The attrition rate of 50.24% indicates a substantial level of employee turnover within the dataset.

**2. Career Opportunities and Employee Satisfaction Are the Leading Termination Reasons**

The most frequently reported termination reasons were:
- Another position: 20 employees
- Unhappy: 14 employees
- More money: 11 employees

These findings highlight career opportunities, employee satisfaction, and compensation as important areas to investigate in understanding employee turnover.

**3. Career Movement Is the Strongest Influencer of Voluntary Termination**

According to Power BI's Key Influencers analysis, the likelihood of voluntary termination increases by:
- 4.28x when the termination reason is *Another position*.
- 4.01x when the termination reason is *Unhappy*.
- 3.90x when the termination reason is *More money*.

These results indicate associations identified by the analytical model and should not be interpreted as evidence of causation.

## 6. Tools & Technologies

- **Microsoft Power BI Desktop:** Data visualization, interactive dashboard development, and Key Influencers analysis.

---

*This project was developed as part of a data analytics portfolio to demonstrate skills in exploratory data analysis, HR analytics, and business intelligence visualization.*
