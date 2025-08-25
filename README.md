# Online Sales Analysis & Prediction

Online sales represent a critical revenue stream for businesses, and due to their digital nature, every transaction can be recorded and analyzed to uncover insights about products, customers, and business processes.  

This project explores an organization’s online transactions spanning **December 1, 2009 – December 12, 2011**, covering sales, returns, shipping fees, banking fees, errors, tests, and promotional discounts.  

---

## Data Challenges & Preprocessing
- Processed **1M+ raw transactions** to ensure quality and usability.  
- Addressed issues with missing data, inconsistencies, and duplicates.  
- Applied data wrangling techniques to prepare the dataset for analysis.  

---

## Exploratory Data Analysis (EDA)
- Analyzed customer purchasing behavior and return rates.  
- Investigated product performance and country-level sales distribution.  
- Identified seasonal trends and anomalies in online sales.  

---

## Predictive Modeling
- **Product Returns Prediction**:  
  - Trained a **Logistic Regression** model using Customer ID, product stock code, quantity, and country of purchase.  

- **Sales Forecasting**:  
  - Built a **Vector Autoregressor (VAR)** model to forecast future sales quantities and revenue trends.  

- **Recommender System**:  
  - Developed a **cosine similarity–based recommendation engine** to suggest products aligned with customer preferences and historical purchases.  

---

## Customer Lifetime Value (CLV) Modeling
- Applied **Beta-Geometric/Negative Binomial Distribution (BG/NBD)** to estimate:  
  - Probability of repeat purchases  
  - Expected purchase frequency  

- Integrated with a **Gamma-Gamma model** to predict **customer lifetime value (CLV)**.  
- Provided insights for **retention strategies** and **marketing investments**.  

---

## Key Outcomes
- Built a robust pipeline for analyzing and predicting customer behavior.  
- Delivered actionable insights into sales performance, product returns, and customer retention.  
- Developed tools for forecasting, recommendations, and customer value prediction.  
