# Customer Spend Prediction & Platform Optimization

## Predicting Annual Customer Spending Using Machine Learning

### Executive Summary

Understanding the factors that influence customer spending is essential for improving customer retention, increasing customer lifetime value, and optimizing marketing investments. This project develops a machine learning regression model to predict annual customer spending using customer engagement and behavioral data.

Beyond predicting customer spending, the analysis identifies the key drivers of revenue and provides business recommendations to support customer retention and platform optimization. The project follows a structured analytics workflow, from exploratory data analysis and feature evaluation to model development, validation, and business interpretation.

---

## Business Context

An e-commerce company seeks to determine whether improving its mobile application or website experience would have a greater impact on increasing customer spending. With limited resources available for platform improvements, management requires evidence-based insights to prioritize investments that maximize customer value and long-term revenue growth.

---

## Business Objective

The objectives of this project are to:

* Predict annual customer spending using historical customer behavior data.
* Identify the factors that most strongly influence customer spending.
* Evaluate the predictive performance of a regression model.
* Translate analytical findings into actionable business recommendations.

---

## Dataset Overview

The dataset contains approximately **500 customer records**, with each record representing an individual customer's engagement and spending behavior.

### Features

* Average Session Length
* Time on App
* Time on Website
* Length of Membership

**Target Variable**

* Yearly Amount Spent

---

## Methodology

The project follows a structured data analytics workflow:

1. Data Exploration
2. Data Cleaning and Preparation
3. Exploratory Data Analysis (EDA)
4. Correlation Analysis
5. Feature Selection
6. Regression Model Development
7. Model Evaluation
8. Residual Analysis
9. Business Interpretation

---

## Key Insights

The analysis revealed several important business insights:

* **Length of Membership** is the strongest predictor of annual customer spending, highlighting customer retention as a major driver of revenue.
* **Time on App** demonstrates a stronger relationship with customer spending than **Time on Website**, suggesting that mobile engagement contributes more to customer value.
* Customer retention appears to have a greater influence on long-term revenue than platform usage alone, indicating that retaining existing customers may generate higher returns than focusing exclusively on interface improvements.

---

## Model Performance

The regression model achieved strong predictive performance:

| Metric                         | Result     |
| ------------------------------ | ---------- |
| R² Score                       | **≈ 0.99** |
| Mean Absolute Error (MAE)      | **≈ 7.23** |
| Root Mean Squared Error (RMSE) | **≈ 8.93** |

Residual analysis indicates that prediction errors are reasonably well distributed, providing additional confidence that the model generalizes effectively to the observed data.

---

## Business Recommendations

Based on the findings, the following recommendations are proposed:

* Prioritize customer retention initiatives, as membership duration has the strongest influence on annual spending.
* Continue investing in the mobile application experience, given its stronger relationship with customer value compared to website engagement.
* Use predictive spending models to identify high-value customers for personalized marketing and retention campaigns.
* Incorporate predictive analytics into customer relationship management strategies to support data-driven decision-making.

---

## Repository Structure

```text
customer-spend-prediction/
│
├── notebooks/
│   └── customer_spend_prediction.ipynb
│
├── reports/
│   └── customer-spend-analysis.pdf
│
├── README.md
│
└── requirements.txt
```

---

## Project Assets

* 📓 Jupyter Notebook: `notebooks/customer_spend_prediction.ipynb`
* 📄 Project Report: `reports/customer-spend-analysis.pdf`

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Skills Demonstrated

* Predictive Analytics
* Regression Modeling
* Exploratory Data Analysis (EDA)
* Data Visualization
* Feature Analysis
* Model Evaluation
* Business Intelligence
* Customer Analytics
* Data-Driven Decision Making

---

## Conclusion

This project demonstrates how machine learning can support customer analytics by predicting annual customer spending and identifying the behavioral factors that drive long-term customer value. The findings suggest that customer retention, particularly membership duration, plays a more significant role in revenue generation than platform usage alone. These insights can help organizations make informed decisions about customer engagement strategies, marketing investments, and long-term business growth.
