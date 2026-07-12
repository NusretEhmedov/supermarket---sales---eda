# Supermarket Sales Analysis: Exploratory Data Analysis Report

## 1. Data Cleaning & Methodology
- **Dataset Size:** Contains 1,000 observations across 17 features.
- **Data Integrity:** Inspected utilizing `.isnull().sum()`; zero missing values were discovered, meaning imputation was unnecessary.
- **Dimensional Modifications:** The `Date` and `Time` features were parsed into datetime representations. An explicit `Hour` integer attribute was generated to identify continuous store-traffic volume patterns.

## 2. Key Statistical Findings
- **Branch Parity:** Volume transactions are divided remarkably evenly among the storefront locations, with each site logging roughly ~333 transactions.
- **Customer Breakdown:** The regular consumer base features an evenly matched distribution split: "Member" profiles account for 50.1%, while "Normal" customer profiles handle 49.9%.

## 3. Business Insights
1. **Top Value Generators:** "Food and beverages" ($56k) and "Sports and travel" ($55k) hold the strongest revenue-producing profiles across the company inventory.
2. **Double Peak Traffic Windows:** Customer traffic follows two specific surge blocks: a lunchtime swell peaking at 13:00 (1:00 PM) and a larger evening traffic window hitting its highest levels at 19:00 (7:00 PM).
3. **Equitable Ratings Distribution:** The store-wide rating holds a stable average score of 6.97/10. Satisfaction metrics show minimal variance across individual structural branches, implying uniform service delivery.
4. **Strategic Scheduling Opportunity:** Marketing efforts and workforce floor assignments should strategically scale up immediately prior to 13:00 and 19:00 to adequately cover core shopping windows.
