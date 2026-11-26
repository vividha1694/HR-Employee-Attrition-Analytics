# HR Employee Attrition & Workforce Analytics

## Project Overview

An end-to-end HR analytics project focused on understanding employee attrition patterns, identifying workforce segments with higher turnover rates, and generating actionable employee retention recommendations.

The project uses KNIME for data preparation and exploratory analysis, Power BI for interactive dashboards, and Gemini AI for business insights.

## Project Objectives

- Analyze overall employee attrition.
- Identify departments and job roles with higher attrition.
- Examine attrition by age, gender, salary and tenure.
- Understand the relationship between overtime and employee attrition.
- Analyze job satisfaction, environment satisfaction and work-life balance.
- Develop data-driven employee retention recommendations.

## Tools & Technologies

- **KNIME:** Data cleaning, transformation and exploratory data analysis.
- **Power BI:** Data visualization, DAX measures and interactive dashboards.
- **Gemini AI:** AI-assisted business analysis and recommendations.
- **Excel / CSV:** Dataset handling.

## Dataset Overview

- Dataset: IBM HR Analytics Employee Attrition & Performance
- Total employee records: 1,470
- Employees who left: 237
- Overall attrition rate: 16.12%
- Average employee age: 36.9 years

**Note:** This is a synthetic/fictitious dataset and does not represent verified employee records from IBM.

## Key Business Insights

| Analysis | Key Finding |
|---|---|
| Department | Sales has the highest attrition at 20.63%. |
| Job Role | Sales Representatives have the highest attrition at 39.76%. |
| Overtime | Employees working overtime have 30.53% attrition. |
| Salary | Low Salary group has 28.61% attrition. |
| Tenure | Employees with 0–2 years of tenure have 29.28% attrition. |
| Age | Employees below 25 have 39.18% attrition. |
| Job Satisfaction | Level 1 has 22.84% attrition. |
| Work-Life Balance | Level 1 has 31.25% attrition. |
| Environment Satisfaction | Level 1 has 25.35% attrition. |

## Power BI Dashboard

## Dashboard Preview

### HR Overview
![HR Overview](screenshots/HR_Overview.png)

### Employee Insights
![Employee Insights](screenshots/Employee_Insights.png)


The interactive dashboard includes:

- Workforce KPI cards
- Department-wise attrition
- Job role-wise attrition
- Gender-wise attrition
- Overtime analysis
- Salary band analysis
- Tenure group analysis
- Age group analysis
- Job satisfaction analysis
- Work-life balance analysis
- Environment satisfaction analysis

## Data Preparation with KNIME

The KNIME workflow includes:

- CSV data import
- Duplicate and missing-value checks
- Removal of unnecessary columns
- Creation of Attrition_Flag
- Salary band classification
- Tenure group classification
- Age group classification
- Group-wise attrition analysis

## Business Recommendations

1. Improve onboarding and employee support during the first two years.
2. Review overtime distribution and workload.
3. Investigate compensation for employees in the low salary band.
4. Improve work-life balance and workplace satisfaction.
5. Conduct targeted retention reviews for high-attrition job roles.

## Project Limitations

- The dataset is synthetic.
- Findings show associations, not proven causes of attrition.
- Further analysis using multiple variables together would help validate the findings.

## Project Deliverables

- KNIME data preparation workflow
- Cleaned employee dataset
- Power BI interactive dashboard
- HR attrition analysis report

## Conclusion

This project demonstrates how data preparation, business intelligence and AI-assisted analysis can transform employee data into meaningful workforce insights and practical retention recommendations.