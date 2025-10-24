# 🛒 DeepCSAT–Ecommerce Customer Satisfaction Score Prediction

DeepCSAT is a deep learning–based regression model designed to predict Customer Satisfaction (CSAT) scores for an e-commerce platform based on customer support data.
The project combines data cleaning, visualization, feature engineering, and model development to discover the key drivers of customer happiness and enable proactive decision-making.

By leveraging interaction data — such as response time, issue category, product details, and customer feedback — the model predicts satisfaction scores and identifies operational bottlenecks.

# 📦 Dataset Information

* **Dataset :** eCommerce_Customer_support_data.csv

* **Rows :** ~83,000 customer support interactions

* **Columns :** ~40 variables (categorical, numerical, text, datetime)

* **Target :** CSAT Score (1–5 scale)

**#Key Features**

Issue_reported at & issue_responded → timestamps for calculating response time

Customer_Remarks → free-text feedback for sentiment analysis

Product_category, Item_price, Agent_Shift, Tenure_Bucket → service & agent features

CSAT_Score → numeric satisfaction rating (target variable)
