# Python-Portfolio-Project
This project involves performing a comprehensive data analysis using the dataset provided and presenting the findings to the business. The analysis is designed to support the sales team by uncovering insights about customer behavior, sales patterns, and business performance using Python for data Validation, Exploratory Data Analysis (EDA) et.c.

##  📘 Sales Method Performance Analysis

This repository contains a data analysis project conducted in a Jupyter Notebook, examining the performance of different sales methods for a new product launch. The analysis leverages Python and popular data science libraries to provide data-driven insights and strategic recommendations.

---
## Project Objectives 

The primary objective of this project is to evaluate the effectiveness of three distinct sales methods: "Email," "Call," and "Email + Call." The analysis aims to understand their impact on customer acquisition and revenue generation over a six-week period, ultimately providing actionable insights to optimize future sales strategies.

---
## Data

The analysis is based on a dataset containing 15,000 rows and 8 columns of customer and sales information. The dataset was imported and validated to ensure data quality and integrity. Key columns include:

  - `sales_method`: The sales approach used (Email, Call, or Email + Call).
  - `customer_id`: Unique identifier for each customer.
  - `revenue_as_customer`: Revenue generated from each customer.
  - `nb_of_visits`: Number of website visits by the customer.
  - `state`: The customer's geographical location.
  - `week`: The week of the sales campaign.
---
## 📊 Analysis and Findings

The project includes an in-depth exploratory analysis and key business metrics to track performance.

### 1\. Exploratory Analysis

  - **Customer Distribution:** The analysis reveals the number of customers engaged through each sales method:
      - **Email:** 7,466 customers
      - **Call:** 4,962 customers
      - **Email + Call:** 2,572 customers
  - **Overall Revenue Distribution:** A boxplot and histogram provide a clear visualization of the overall revenue distribution, highlighting the spread and central tendency of the data.
---

### 2\. Business Metrics and Insights

  - **Average Revenue per Customer by Sales Method:** A critical metric, "Average Revenue per Customer per Sales Effort" (ARCPSE), was defined and calculated to compare the efficiency of each method.
      - **Call:** $15.87
      - **Email:** $194.26
      - **Email + Call:** $185.65
  - **Revenue per Customer over Time:** A line plot visualizes the average revenue per customer for each sales method over the six-week period. The `Email + Call` method showed a strong performance trend.
---

## Conclusion and Recommendations

Based on the analysis, the following conclusions and recommendations are drawn:

1.  **Email + Call** is identified as the most effective sales method, generating a significantly higher average revenue per customer compared to the other methods.
2.  The `Email + Call` method exhibits a consistent upward trend in average revenue over the six weeks, indicating its potential for sustained high performance.
3.  The `Call` method, while less effective in terms of revenue, may still be valuable for customer engagement and should not be entirely discarded.
4.  Further analysis and investment in optimizing the `Email` and `Email + Call` campaigns are recommended to maximize customer engagement and revenue generation.
---

## How to View the Project

To view and run this analysis yourself, follow these steps:

1.  Clone this repository to your local machine.
2.  Ensure you have Python and Jupyter Notebook installed.
3.  Install the required libraries:
    ```bash
    pip install pandas matplotlib seaborn
    ```
4.  Open the `[your_notebook_name].ipynb` file in Jupyter Notebook.

-----

## 🛠️ License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and share this project with proper attribution

---

## 📮 Contact

Hi there! I'm **Okoroh Precious**, also known as **DataByPrecious**, I am a Data Analyst on a mission to share knowledge and project materials.
  [GitHub Profile](https://github.com/DataByPrecious)

---


**Note:** Please replace `[your_notebook_name].ipynb` with the actual file name of your Jupyter Notebook. You can also add a "Technologies Used" section if you want to highlight the libraries more prominently.
