# 🚕 Maximizing Revenue for Taxi Cab Drivers through Payment Type Analysis

A statistical data analysis project using descriptive statistics, hypothesis testing, and regression to uncover how payment methods (card vs cash) affect fare amounts and revenue for NYC taxi cab drivers.

---

## 📝 Project Summary

This project explores whether the **type of payment** made by passengers influences the **fare amount**, and how that relationship can be leveraged to **maximize revenue for taxi drivers**.

We used a real-world dataset from **NYC Taxi Trip Records**, focusing on relevant variables like payment method, fare amount, passenger count, trip duration, and distance. The findings are backed by **statistical testing and regression analysis**, providing actionable recommendations for stakeholders.

---

## ⚙️ Tech Stack

- 🐍 **Python** – For data cleaning, analysis, and visualization
- 📈 **Pandas, NumPy** – Data manipulation and summarization
- 📊 **Seaborn, Matplotlib** – Visualization of trends and distributions
- 🧠 **SciPy / Statsmodels** – T-test and regression analysis
- 📄 **Jupyter Notebook** – Exploratory and statistical workflow
- 📁 **PDF Summary** – Final business presentation/report

---

## 📂 Dataset Overview

**Source**: NYC Taxi Trip Records  
**Relevant columns used**:
- `fare_amount`
- `payment_type` (card or cash)
- `trip_distance` (miles)
- `duration` (minutes, calculated from pickup and dropoff)
- `passenger_count`

> Data was cleaned and filtered to focus on the most relevant columns for this statistical analysis.

---

## 🔍 Research Question

> **Is there a significant relationship between total fare amount and the payment type used?**

If so, can taxi services nudge customers toward **higher-revenue payment methods** without compromising customer satisfaction?

---

## 📊 Methodology

### 1. Descriptive Analysis
- Compared mean and standard deviation of fare amount by payment type.
- Explored the relationship between trip distance and payment type.
- Analyzed the distribution of payment types and passenger counts.

### 2. Hypothesis Testing
- **Null Hypothesis (H₀)**: No difference in average fare between card and cash payments.
- **Alternative Hypothesis (H₁)**: A significant difference exists in average fare by payment method.
- Performed an **independent two-sample T-test**.

### 3. Regression Analysis
- Built a **linear regression model** to evaluate how trip duration affects fare amount.

---

## 📈 Key Findings

- **Card-paying customers** have slightly **higher average fares** and longer trip distances than cash payers.
  - Avg Fare: Card – $13.7 | Cash – $12.25  
  - Avg Distance: Card – 3.23 mi | Cash – 2.8 mi
- **Card payments dominate** at 67.5% of all transactions.
- **Single-passenger trips** make up the largest share in both payment types.
- **Hypothesis test result**:  
  - T-statistic: 165.5  
  - P-value: < 0.05  
  → **Reject H₀** → There is a **significant difference** in fare amount by payment type.

---

## 💡 Business Insights & Recommendations

- **Encourage card payments** with incentives or small discounts to increase revenue potential.
- **Highlight seamless payment options** (e.g., NFC, app-based payment) to boost card usage.
- Since higher fare and distance correlate with card usage, **train drivers** to suggest cards for longer trips.
- Use insights on **passenger count** to target offers (e.g., solo passengers most likely to use cards).

---

## 🧠 Skills Demonstrated

✅ Data Cleaning  
✅ Statistical Analysis  
✅ Hypothesis Testing (T-test)  
✅ Linear Regression  
✅ Data Visualization  
✅ Business Recommendation Writing  
✅ Real-World Dataset Handling

---

## 📄 Final Presentation

A polished PDF presentation summarizing:

- Problem Statement  
- Data Overview  
- Key Statistics  
- Hypothesis Testing  
- Regression Results  
- Business Recommendations  

👉 [View PDF Report](https://github.com/avantikaaa2001/fare-vs-payment-analysis/blob/main/omsGeFBKDwGkb4gL1hoyon.pdf)

---


