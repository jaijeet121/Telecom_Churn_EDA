# 📉 Telecom Customer Churn: Exploratory & Diagnostic Analysis

## 📌 Project Overview
Customer churn is one of the most expensive problems in the subscription-driven telecom industry. Acquiring a new customer costs far more than retaining an existing one. 

This project performs an in-depth Exploratory Data Analysis (EDA) on a dataset of 7,043 telecom customers to diagnose who is churning, why they are leaving, and how the business can identify high-risk segments early enough to intervene.

## 🛠 Tools & Libraries Used
* **Python:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Environment:** Google Colab

## 📊 Key Business Insights
Based on the diagnostic analysis of the resolved customer base (Overall Churn Rate: 28.37%), the following high-risk factors were identified:

1. **The "Early Month" Danger Zone:** The vast majority of customer churn occurs within the first 1 to 6 months of service. Retention efforts must be heavily focused on the onboarding phase.
2. **Contract & Offer Vulnerability:** Customers on Month-to-Month contracts are highly unstable, with a churn rate exceeding 51%. Furthermore, promotional "Offer E" is significantly underperforming and drives the highest volume of cancellations.
3. **Internet vs. Phone Dependency:** Subscribing to internet services is a major risk factor (33.48% churn rate) compared to customers without internet (8.41%). Phone service alone does not heavily influence churn.
4. **Household Signals:** Customers who are single, have no dependents, and have not made any referrals are significantly more likely to leave.
5. **The Competitor Threat:** The top specific reasons for leaving are directly related to competitors offering better plans, devices, and offers, closely followed by frustration with customer support attitude.

## 📂 Repository Contents
* `telecom_churn.ipynb`: The primary Jupyter Notebook containing data cleaning, type optimization, and visual diagnostic analysis.
* `telecom_customer_churn.csv`: The raw dataset used for this analysis.

## 🚀 How to Run
1. Clone this repository to your local machine.
2. Ensure you have the required libraries installed (`pip install pandas numpy matplotlib seaborn`).
3. Open `telecom_churn.ipynb` in Jupyter Notebook or Google Colab and run all cells.
