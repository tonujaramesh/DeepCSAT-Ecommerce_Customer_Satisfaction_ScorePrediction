# 🛒 DeepCSAT–Ecommerce Customer Satisfaction Score Prediction

# 📌 Project Overview

DeepCSAT is a deep learning–based regression model designed to predict Customer Satisfaction (CSAT) scores for an e-commerce platform based on customer support data.
The project combines data cleaning, visualization, feature engineering, and model development to discover the key drivers of customer happiness and enable proactive decision-making.

By leveraging interaction data — such as response time, issue category, product details, and customer feedback — the model predicts satisfaction scores and identifies operational bottlenecks.

# 📦 Dataset Information

* **Dataset :** eCommerce_Customer_support_data.csv

* **Rows :** ~83,000 customer support interactions

* **Columns :** ~40 variables (categorical, numerical, text, datetime)

* **Target :** CSAT Score (1–5 scale)

# **Key Features**

* **Issue_reported at & issue_responded →** timestamps for calculating response time

* **Customer_Remarks →**  free-text feedback for sentiment analysis

* **Product_category, Item_price, Agent_Shift, Tenure_Bucket →** service & agent features

* **CSAT_Score →** numeric satisfaction rating (target variable)

# 🔍 Problem Statement

E-commerce businesses struggle to track and improve customer satisfaction in real time.
Manual survey analysis is slow and reactive.
DeepCSAT solves this by building a predictive model that automatically estimates CSAT from operational metrics, enabling proactive improvements.

# Data Wrangling Highlights

* **Handled missing values →** imputed numeric with median, categorical with “Unknown”.

* **Removed duplicates →** ensured unique ticket records.

* **Encoded categorical variables →** Label + One-Hot Encoding.

* **Scaled numeric features →** standardized for model training.

* **Feature engineered →** calculated response time, handling time, and sentiment flags.

# 🧪 Hypothesis Testing

## Three key hypotheses were tested statistically:

1. **Agent Shift affects CSAT →** ANOVA confirmed significant impact (p < 0.05).

2. **Higher Item Price →** Higher CSAT → Weak correlation, no significance.

3. **Longer Response Time →** Lower CSAT → Strong negative correlation, confirmed.

# 📚 Project Workflow

* Data Collection

* Data Cleaning & Preprocessing

* EDA & Visualization

* Hypothesis Testing

* Feature Engineering

* Deep Learning Model Training

* Evaluation & Validation

* Deployment & Insights Generation

# 🏁 Conclusion

DeepCSAT successfully predicts customer satisfaction using AI-driven insights.
By correlating operational efficiency, issue category, and customer sentiment with satisfaction, this project helps e-commerce businesses transform reactive service models into proactive, data-driven customer experience systems.
