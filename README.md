 Bank Customer Churn Analysis

 Project Overview  
This project analyzes **bank customer churn patterns** using demographic, financial, and engagement data. The goal is to uncover key churn drivers and propose actionable strategies for improving retention.  
Analysis was performed in **Python (Jupyter Notebook)** with visual insights created using **Matplotlib** and **Seaborn**.


## Dataset  

The dataset consists of **two sheets** (merged on a common customer key):  

1. **Customer Data** – Name, Customer ID, Age, Gender, Geography, Tenure, etc.  
2. **Account Data** – Credit Score, Balance, Products Held, IsActiveMember, Estimated Salary, etc.  

**Target Variable:**  
- `Exited` — `1` if the customer left the bank (churned), `0` if retained.

**Source Files:**  
- `Bank_Churn_Messy.xlsx` — Raw dataset with two sheets.  
- `Bank_Churn_Data_Dictionary.csv` — Field descriptions.


## Key Insights  

1. **Geography Matters** – Certain regions have churn rates up to **30% higher**.  
2. **Age Impact** – Middle-aged customers (40–50) churn more frequently.  
3. **Active Membership** – Inactive members are **twice as likely to churn**.  
4. **Tenure Influence** – Shorter-tenure customers are more likely to exit.  
5. **Products Held** – Low product ownership is linked to higher churn.


## Visual Findings  

- **Correlation Heatmap** – Highlights the relationship between age, tenure, and churn.  
- **Churn by Geography** – Regional churn disparities.  
- **Active Membership vs. Churn** – Strong engagement-churn relationship.  

>  *Plots and figures are available in the analysis notebook.*

## ✅ Recommendations  

- **🎯 Target High-Churn Regions** – Localized offers and relationship managers.  
- **🔄 Re-Engage Inactive Members** – Rewards, exclusive benefits, and gamified features.  
- **💳 Strengthen Onboarding** – Incentives for new customers in first 2 years.  
- **📈 Predictive Churn Alerts** – Machine learning models to flag at-risk customers.  
- **💬 Enhance Service Experience** – Faster support, personalization, and loyalty perks.



##  Repository Structure

Bank Customer Churn Analysis.ipynb # Jupyter Notebook with full analysis
 Bank_Churn_Messy.xlsx # Raw dataset
Bank_Churn_Data_Dictionary.csv # Field descriptions

