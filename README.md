<img width="621" height="424" alt="image" src="https://github.com/user-attachments/assets/7f665e5c-154c-4b22-a1f3-f8460289e5b1" />
<img width="625" height="434" alt="image" src="https://github.com/user-attachments/assets/a588106b-a0ca-4680-a573-356088096571" />
<img width="649" height="422" alt="image" src="https://github.com/user-attachments/assets/7218304c-d7d0-4417-9244-89904da469b2" />
<img width="723" height="432" alt="image" src="https://github.com/user-attachments/assets/a571b302-f67d-4eb7-81e9-cf78d970e4b6" />

 Overview:

Customer churn refers to customers who stop using a company’s services. This project focuses on analyzing customer behavior using synthetic data to understand why customers leave.

Instead of using machine learning, this project mainly uses **Exploratory Data Analysis (EDA)** to identify patterns, trends, and factors affecting churn.

Synthetic data is generated using Faker to simulate real-world customer details.

 Dataset:

The dataset is generated artificially using Faker and contains 1,00,000 customer records.

 Features:

* Customer_ID – Unique ID
* Age – 18 to 70
* Gender – Male / Female
* Tenure – 0 to 10 years
* Balance – 0 to 2,00,000
* CreditScore – 300 to 900
* EstimatedSalary – 10,000 to 1,50,000
* NumOfProducts – 1 to 4
* IsActiveMember – 0 / 1
* Churn – 0 (No), 1 (Yes)

---

 Objectives:

* Generate synthetic customer dataset
* Perform data preprocessing
* Analyze customer behavior using EDA
* Identify patterns and churn factors
* Visualize insights using charts

---

 Project Highlights:

* Synthetic data generation using Faker
* Data cleaning and preprocessing
* Detailed Exploratory Data Analysis
* Graph-based insights
* Identification of churn patterns

---
 1. Data Preprocessing

* Checked missing values (no missing data found)
* Verified data types
* Converted Gender into numerical format
* Removed unnecessary columns like Customer_ID
* Prepared dataset for analysis

---

 2. Exploratory Data Analysis (EDA)

EDA helps to understand the data visually and statistically.

Key Analysis:

* Churn distribution (count of churn vs non-churn)
* Age vs Churn comparison
* Balance vs Churn comparison
* Active vs inactive users
* Number of products vs churn

---

Churn Behavior Insights:

* Inactive customers have higher churn rate
* Customers with low balance are more likely to churn
* Customers with low credit score tend to leave
* Customers using fewer products are more likely to churn

---

 Visualization:

Various graphs are used:

* Bar chart – Churn count
* Box plot – Age & Balance comparison
* Histogram – Distribution of features
* Heatmap – Correlation between variables

---

 Tools and Technologies:

* Python
* Google Colab
* Faker
* Pandas & NumPy
* Matplotlib & Seaborn

---

 Results:

* Successfully generated synthetic dataset
* Identified key churn patterns using EDA
* Found major factors affecting churn:

  * Low balance
  * Inactive membership
  * Low credit score

---

 Pipeline Usage:

1. Data Generation
2. Data Cleaning
3. Data Analysis (EDA)
4. Visualization
5. Insight Extraction

---

 Generating Insights:

* Businesses can identify high-risk customers
* Helps improve customer retention strategies
* Useful for decision making without complex models

---

 Future Improvements:

* Use real-world dataset
* Add dashboard (Power BI / Tableau)
* Perform advanced statistical analysis
* Integrate real-time monitoring

---


