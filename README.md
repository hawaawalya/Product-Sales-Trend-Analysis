# Product-Sales-Trend-Analysis

📊 This project focuses on analyzing product sales trends using modern data analysis techniques.  
The aim is to understand **patterns, seasonality, and anomalies** in retail sales data while applying structured analytical frameworks.

## 🔍 Project Overview
This repository contains the workflow and methodology used to analyze product sales trends.  
Rather than focusing only on the final results, the emphasis here is on the **frameworks, methods, and tools** that can be applied to similar datasets.

## 🛠️ Methodology & Frameworks
### 1. Data Understanding & Preparation
- Cleaning missing values & anomalies.
- Handling duplicates.
- Standardizing categorical values (e.g., product categories, city names).
- Ensuring time-series consistency.

### 2. Exploratory Data Analysis (EDA)
- Descriptive statistics (mean, median, distribution).
- Segmentation by product, city, and time period.
- Outlier detection and anomaly checks.

### 3. Trend & Seasonality Analysis
- Time series decomposition.
- Rolling averages.
- Identifying demand cycles.

### 4. Visualization
- Power BI dashboards.
- Comparative charts (line, bar, pie).
- Scatter plots for correlations.

## 🧑‍💼 Business Analysis (Technical Test Style)
This section frames the analysis **from the perspective of a stakeholder or store manager**, focusing on *practical business questions*.

### A. Data Understanding & Cleaning
1. **Are there any errors or anomalies in the Excel file?**  
   - Example 1: Negative quantity values → should be corrected or removed.  
   - Example 2: Wrong date format (e.g., text instead of date) → convert to proper date field.
     
2. **Are there any duplicate records?**  
   - If duplicates exist, count them and keep only unique transaction IDs.  
   - Example: Out of 10,000 records, 120 might be duplicates → remove them to avoid revenue inflation.



### B. Descriptive Analysis
3. **Total Revenue (Jan–Mar 2024):**  
   - Sum of `Quantity × Price` across all products in this period.  

4. **Most Frequently Purchased Product & City:**  
   - Identify the product with the highest sales count.  
   - Break down by city to see geographic concentration.  

5. **Most Frequently Used Payment Method:**  
   - Check mode distribution (e.g., Credit Card, E-wallet, Cash).  

6. **Top 5 Customers by Purchase Value:**  
   - Rank customers by total spending.  

7. **Month with Highest Revenue:**  
   - Example: March shows peak revenue.  
   - Possible reasons: promotional campaign, seasonal demand, or school holidays.  

---

### C. Problem Solving & Business Insight
8. **Which product to promote next month?**  
   - Choose based on:  
     - High demand but low margin → upsell/cross-sell.  
     - Or high margin but under-promoted → maximize profitability.  

9. **Interesting Purchasing Pattern:**  
   - Example: Bundling pattern → customers often buy Product A with Product B.  
   - Recommendation: Offer bundle discounts to boost sales.  

10. **2 Key Metrics to Monitor Monthly:**  
   - **Revenue Growth %** → track overall business health.  
   - **Repeat Purchase Rate** → measure customer loyalty and retention.  

## 📈 Analytical Frameworks Used
**1. CRISP-DM (Cross Industry Standard Process for Data Mining)**

## Daboard View
<img width="1158" height="645" alt="Image" src="https://github.com/user-attachments/assets/a1ec15d9-1a4a-4e4e-8182-fe485e8c8699" />

## Complete Report


## 🧰 Tools & Technologies
- **Power BI** → dashboards & storytelling.  
- **Excel** → raw exploration & validation.  

## 🚀 Key Learnings
- Sales trend analysis combines **statistics + business context**.  
- Outlier detection avoids misleading results.  
- Using a question-driven framework (like the Technical Test above) ensures relevance for decision makers.  


