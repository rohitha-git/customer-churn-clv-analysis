# Customer Churn & Lifetime Value Analytics

## Project Overview
This project focuses on analyzing customer purchasing behavior to identify churn risk, estimate Customer Lifetime Value (CLV), and segment customers using RFM analysis. The objective is to help businesses improve customer retention and reduce revenue loss through data-driven insights.

The project combines data cleaning, exploratory data analysis (EDA), feature engineering, customer segmentation, machine learning, and Power BI visualization to provide actionable business recommendations.

---

## Business Problem
Businesses often struggle to answer important questions such as:

- Which customers are most valuable?
- Which customers are likely to churn?
- How much revenue is at risk?
- Which customers should retention teams target?

Customer churn directly impacts revenue and profitability. Identifying at-risk customers early allows businesses to improve retention strategies.

---

## Objectives
- Perform customer behavior analysis using transaction data
- Segment customers using RFM analysis
- Calculate Customer Lifetime Value (CLV)
- Predict customer churn using machine learning
- Estimate revenue at risk due to churn
- Build an interactive dashboard for business insights

---

## Dataset
Dataset used: Online Retail Dataset

Dataset contains transactional records with the following columns:

- InvoiceNo
- StockCode
- Description
- Quantity
- InvoiceDate
- UnitPrice
- CustomerID
- Country

---

## Technologies Used
### Programming & Analysis
- Python
- Pandas
- NumPy

### Visualization
- Matplotlib
- Seaborn
- Power BI

### Machine Learning
- Scikit-learn
- Logistic Regression
- Random Forest Classifier

---

## Project Workflow

### 1. Data Cleaning
- Removed missing Customer IDs
- Removed duplicate records
- Removed invalid quantities and prices
- Converted date columns into datetime format

### 2. Exploratory Data Analysis
Analyzed:
- Revenue distribution
- Country-wise revenue
- Customer purchase trends
- Monthly sales behavior

### 3. Feature Engineering
Created:
- Revenue column
- Year / Month features
- Customer-level analytical features

### 4. RFM Analysis
Customers were segmented using:

- Recency
- Frequency
- Monetary Value

Customer segments:
- Champions
- Loyal Customers
- Potential Loyalists
- At Risk
- Lost Customers
- Need Attention

### 5. Customer Lifetime Value (CLV)
Calculated CLV to estimate long-term customer value and identify high-value customers.

### 6. Churn Prediction
Created churn labels based on inactivity threshold and trained ML models to predict customer churn.

Models used:
- Logistic Regression
- Random Forest

### 7. Dashboard Development
Built Power BI dashboard to visualize:

- Total Customers
- Churn Rate
- Revenue at Risk
- Average CLV
- Customer Segments
- CLV Distribution

---

## Key Insights
- Approximately 33.4% customers were identified as churned
- Revenue at risk due to churn exceeded 1M
- Loyal customers formed the largest customer segment
- Recency was the most important feature in churn prediction
- High-value churned customers represented significant business risk

---

## Business Impact
This project helps businesses:

- Reduce churn
- Improve retention strategies
- Prioritize high-value customers
- Minimize revenue loss
- Improve marketing effectiveness

---

## Results
The project successfully identified customer segments, estimated lifetime value, predicted churn risk, and provided actionable insights through analytics and visualization.

---

## Repository Structure
```bash
customer-churn-clv-analysis/
│
├── customer_churn_dashboard.csv
├── customer_churn_analysis.ipynb
├── dashboard.pbix
├── README.md
```

---

## Future Improvements
- Deploy churn prediction model as web app
- Improve model using XGBoost
- Add real-time customer monitoring
- Integrate automated retention alerts
