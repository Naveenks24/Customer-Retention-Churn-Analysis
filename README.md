# Customer Retention & Churn Analysis 📊

## 🎯 Project Objective
This project analyzes a dataset of over 7,000 customers to uncover the core drivers of customer churn. The goal is to act as a data analyst advising a subscription-based business on *who* is leaving, *when* they are leaving, and *why*, ultimately providing actionable recommendations to reduce revenue leakage.

## 🛠️ Tools & Technologies Used
* **Python:** Data manipulation and analysis.
* **Pandas:** Data cleaning, cohort analysis, and cross-tabulation.
* **Matplotlib & Seaborn:** Statistical data visualization and business storytelling.
* **Jupyter Notebook (VS Code):** Development environment.

## 💡 Key Business Insights

1. **The Baseline Leak:** The company is currently experiencing an overall customer churn rate of **26.6%**.
2. **The "Churn Cliff":** Analysis of customer tenure reveals a massive spike in churn within the very first 1 to 3 months. Customers are abandoning the service almost immediately after signing up.
3. **Contract Type Matters:** Users on Month-to-Month contracts churn at a staggering **42.7%**, compared to just **11.3%** for One-Year and **2.8%** for Two-Year contracts.
4. **Price Sensitivity:** A box plot analysis confirmed that the median monthly charge for customers who leave (~$80) is significantly higher than those who stay (~$65).

## 🚀 Actionable Recommendations
* **Revamp the Onboarding Experience:** Since the vast majority of drop-off happens in months 1-3, the business must immediately focus on showing immense value during the first 30 days.
* **Incentivize Annual Contracts:** The data clearly shows that locking users into longer contracts practically eliminates churn. The company should heavily subsidize or discount the first year to transition users away from month-to-month billing.

## 📂 Repository Contents
* `task2.ipynb`: The complete Python source code and visualizations.
* `cleaned_telco_data.csv`: The cleaned dataset used for this analysis.

---
*Completed as part of the Data Science & Analytics internship task by Future Interns.*
