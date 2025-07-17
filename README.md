# Insurance Data Analysis
# Overview
This project involves analyzing insurance claim data to derive insights related to customer demographics, claim status, policy types, and active/inactive policyholders. The goal is to present a business-intelligent dashboard that helps stakeholders understand premium collection, claim distribution, and demographic impact.
The project begins with importing raw data into SQL Server for structured storage and querying. It is then loaded into Power BI for interactive data profiling, advanced visualizations, and dashboard creation. Visuals include slicers, cards, ribbon charts, bar graphs, donut charts, matrix views, and more.
# 🛠 Tools & Technologies
* Microsoft SQL Server – For data import and management
- Power BI – For visualization and dashboard creation
- Excel – Initial data exploration and preprocessing
# 🎯 Objective:
- To analyze insurance data and identify key patterns in customer claims.
- To visualize and interpret claim distribution by status, gender, and policy type.
- To monitor premium collection and coverage amount across different age groups.
- To assess the activeness of policyholders.
- To provide a clear and interactive dashboard for decision-making.
# 🧾 Data Description
The dataset includes the following features:
| Column Name    | Description                                   |
| -------------- | --------------------------------------------- |
| PolicyNumber   | Unique identifier for each policy             |
| ClaimNumber    | Unique claim identification number            |
| CustomerID     | Customer ID                                   |
| Gender         | Gender of the policyholder                    |
| AgeGroup       | Age group classification (Adult, Elder, etc.) |
| PolicyType     | Type of insurance policy (Auto, Health, etc.) |
| PremiumAmount  | Amount paid for the policy premium            |
| CoverageAmount | Insurance coverage amount                     |
| ClaimAmount    | Amount claimed by the customer                |
| ClaimStatus    | Status of the claim (Pending, Rejected, etc.) |
| PolicyStatus   | Active or Inactive         

# 📈 Power BI Visualization
Key features from the dashboard:
- Gender Distribution: Equal representation of male and female customers.
- Claim Status: Categorized into Rejected, Settled, and Pending.
- Premium by Policy Type: Travel and Health policies have the highest premiums.
- Claim Amount by Age Group: Adults claim the highest amounts.
- Policy Activeness: 58% policies are active, 42% inactive.
- Summary Cards: Shows total PremiumAmount, CoverageAmount, and ClaimAmount.
## Dasboard
<img width="1373" height="728" alt="Insurance Data Analysis" src="https://github.com/user-attachments/assets/ce0d434c-10c6-469d-a0da-48d879a750c3" />

<img width="1377" height="728" alt="Insurance Data Analysis1" src="https://github.com/user-attachments/assets/3bbbccbb-77da-411d-9b13-a172538e5076" />

# 📬 Conclusion
- This analysis enables insurance companies to:
- Understand claim behavior across different demographics.
- Optimize premium pricing and claim settlement strategies.
- Identify inactive policyholders and re-engage them.


