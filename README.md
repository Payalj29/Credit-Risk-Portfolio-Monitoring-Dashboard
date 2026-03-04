📊 Credit Risk Portfolio Monitoring Dashboard
📌 Project Overview

This project presents a Credit Risk Portfolio Monitoring Dashboard built using Power BI.

The objective is to analyze customer repayment behavior, credit utilization patterns, and portfolio exposure to identify high-risk segments and support risk-based decision-making.

The dashboard simulates a real-world banking/NBFC credit risk monitoring scenario.

🎯 Business Objective

Financial institutions must continuously monitor:

Default risk levels

Repayment behavior

Exposure concentration

High-risk customer segments

This dashboard helps stakeholders:

Identify early delinquency signals

Detect high-risk segments

Quantify financial exposure

Support proactive credit control decisions

📂 Dataset Description

The dataset contains customer-level credit information including:

Credit Limit (LIMIT_BAL)

Demographics (AGE, SEX, EDUCATION, MARRIAGE)

Repayment Status (PAY_0 to PAY_6)

Bill Amounts (BILL_AMT1 to BILL_AMT6)

Payment Amounts (PAY_AMT1 to PAY_AMT6)

Default Indicator (0 = No Default, 1 = Default)

Additional derived fields were created for business segmentation:

Age Group

Gender

Credit Utilization

Utilization Band

Delay Category

Total Bill

Total Payment

Payment Ratio

Risk Category

📈 Key KPIs

The dashboard tracks the following metrics:

Total Customers

Default Rate (%)

Average Credit Limit

Average Credit Utilization (%)

Total Portfolio Exposure

High-Risk Customer %

📊 Dashboard Segmentation
1️⃣ Demographic Risk Analysis

Default Rate by Age Group

Default Rate by Gender

2️⃣ Behavioral Risk Analysis

Default Rate by Delay Category

Default Rate by Utilization Band

3️⃣ Exposure Analysis

Total Exposure by Delay Category

Exposure by Risk Category

4️⃣ Portfolio Overview

Default Distribution (Default vs Non-Default)

🔎 Key Insights

Customers with 3+ repayment delays show significantly higher default rates.

High credit utilization (>70%) is associated with elevated default risk.

Exposure is concentrated in the “No Delay” segment, reducing immediate portfolio stress.

Older age segments show slightly higher risk trends.

🛠 Tools & Technologies Used

Power BI (Data Modeling, DAX, Dashboarding)

DAX (Measures & Calculated Columns)

Data Cleaning & Feature Engineering

Risk Segmentation Logic

🧠 Analytical Approach

Data Cleaning & Labeling

Creation of derived risk indicators

Segmentation into behavioral and demographic categories

Calculation of portfolio-level KPIs

Visualization for executive decision support

💼 Business Use Case

This dashboard can help:

Risk teams monitor delinquency trends

Credit teams adjust limits for high-risk customers

Collections teams prioritize recovery efforts

Management assess portfolio health

🚀 Future Enhancements

Predictive default model (Machine Learning)

Time-series delinquency trend analysis

Probability of Default (PD) scoring

Stress testing simulation
