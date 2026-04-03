📊 Workforce Intelligence & Attrition Risk Dashboard
Strategic HR Analytics using Excel | Kaggle HR Dataset
 
 
 
📌 Project Overview
This project provides a comprehensive analysis of workforce dynamics, focusing on employee retention, performance, and attrition risk. By utilizing the Kaggle HR Dataset, I developed two interactive dashboards that allow HR leaders to identify "High Risk" employees before they leave and understand the financial impact of salary distributions across departments.
🚀 Key Features
1. Attrition & Risk Intelligence Dashboard
•	Risk Scoring Model: A custom formula-based logic to identify "High Risk" employees based on performance, engagement, and satisfaction scores.
•	Termination Pareto Analysis: Visualizes the primary reasons for turnover, identifying that "Another Position" and "Unhappy" are the top drivers.
•	Talent Attrition Flow: A funnel visualization showing the transition from total headcount to active high performers.
•	Predictive KPIs: Real-time tracking of Retention Rate (32.3%) and Yearly Retention (0.64).
2. Workforce Intelligence Dashboard
•	Salary Distribution: A histogram showing the concentration of staff in the $50k–$70k bracket.
•	Engagement vs. Performance: Box plots and scatter plots analyzing the correlation between pay, employee engagement, and output.
•	Departmental Deep-Dive: Combo charts showing headcount vs. turnover rate by department (Production being the highest headcount).
📈 Key Insights from the Data
•	High Turnover Alert: The current turnover rate is 33.32%, which indicates a need for targeted retention strategies in the Production and Sales departments.
•	Engagement Gap: Using the Engagement vs. Turnover Box Plot, we observed that lower engagement scores directly correlate with higher termination counts.
•	Risk Factor: Identified 31 employees currently in the "High Risk" category who require immediate intervention/engagement plans.
🛠️ Technical Skills Used
•	Advanced Excel Formulas: LET, COUNTIFS, SUMPRODUCT, and nested IF statements for risk categorization.
•	Data Cleaning: Handling null values in termination dates and standardizing department names.
•	Data Modeling: Created a star-schema-like structure using Excel Power Pivot.
•	Dynamic Visuals: Implementation of Slicers (Department, Hire Year, Salary Band) for interactive reporting.
📂 Project Structure
text
├── Data/
│   └── HRDataset_v14.csv       # Original Kaggle Dataset
├── Dashboard/
│   └── HR_Intelligence_Final.xlsx # Interactive Excel Dashboard
└── README.md
📸 Dashboard Preview
Workforce Overview	Attrition Risk
 	 
Note: Replace your_screenshot_link with the actual image links once you upload them to your GitHub repository.
🛠️ How to Use
1.	Download the .xlsx file from the Dashboard folder.
2.	Open in Microsoft Excel (2019 or later recommended for full feature support).
3.	Use the Filter Pane on the left to slice data by Year, Department, or Performance ID
