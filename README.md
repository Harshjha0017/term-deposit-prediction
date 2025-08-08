Term Deposit Subscription Prediction

Problem Statement

A Portuguese bank launched multiple telemarketing campaigns to promote a long-term **term deposit product**. Customers were contacted via telephone or cellular calls—sometimes repeatedly. Despite considerable effort, the **conversion rate remained low**, leading to wasted resources and a poor customer experience.

Business Objective

The bank aimed to:
1. Identify key factors** influencing a customer's decision to subscribe.
2. Predict which customers are likely to subscribe using demographic and interaction features.
3. Improve campaign targeting by focusing on high-potential leads while reducing over-contacting.

---

Analytical Goals

- Perform exploratory data analysis (EDA) to uncover patterns in subscription behavior.
- Analyze campaign effectiveness across duration, contact method, timing, and past outcomes.
- (Optionally) Build a classification model to predict if a client will subscribe (`yes`/`no`).
- Provide actionable recommendations to:
  - Optimize calling strategy  
  - Lower marketing costs  
  - Improve conversion efficiency

Business Value

- **Increased term deposit conversions**
- **Lower operational and marketing costs**
- **Improved customer experience**
- **Data-driven campaign strategy**

---

Key Insights from Analysis & Dashboard

You developed a Power BI dashboard (see: `Dashboard.pdf`) that visualizes the campaign results:

Highlights:
- **Conversion Rate**: **11.7%** overall
- **Top Performing Contact Method**:  
  - **Cellular**: 82.6% of successful conversions  
  - **Telephone** and **Unknown** underperformed significantly

- **Best Performing Age Groups**:
  - **46–60 years** and **36–45 years** showed higher conversion rates
  - **Under 25** had the lowest conversion

- **Education Effectiveness**:
  - Customers with **tertiary education** converted more than others
  - **Primary education** showed the lowest response rate

- **Balance Trends**:
  - Clients who subscribed had a significantly **higher average balance**

- **Timing by Month**:
  - Campaigns in **May** saw the highest conversion volume
  - **January** and **December** had the lowest activity

- **Occupation Segments**:
  - **Management** and **retired** customers converted best
  - **Blue-collar** had high volume but low conversion rate

---

Tools Used

- 🐍 **Python (Pandas, NumPy, Matplotlib)** for data wrangling and EDA
- 📊 **Power BI** for interactive visual dashboards
- 📁 CSV for data exchange and `.pbix` for report files
