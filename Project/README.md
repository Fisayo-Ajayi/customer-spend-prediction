# Customer Spend Prediction & Platform Optimization

## 1. Business Context

An e-commerce company seeks to determine whether to prioritize improvements in its mobile app or website experience to increase customer spending.

---

## 2. Objective

To model and predict yearly customer spending and identify the key drivers influencing revenue.

---

## 3. Dataset

- ~500 customer records
- Features include:
  - Avg. Session Length
  - Time on App
  - Time on Website
  - Length of Membership
- Target: Yearly Amount Spent

---

## 4. Key Insights

- **Length of Membership is the strongest predictor of spending**
- Time on App shows more impact than Website usage
- Customer retention has a greater influence on revenue than platform usage alone

---

## 5. Model Performance

- R² ≈ 0.99
- MAE ≈ 7.23
- RMSE ≈ 8.93

The model demonstrates strong predictive accuracy with well-distributed residuals.

---

## 6. Business Recommendation

Rather than focusing solely on App vs Website improvements, the company should prioritize:

- Customer retention strategies
- Membership growth and engagement

---

## 7. Project Assets

- 📄 Report: `reports/customer-spend-analysis.pdf`
- 📓 Notebook: `notebooks/customer_spend_prediction.ipynb`

---

## 8. Tools

- Python (Pandas, NumPy)
- Scikit-learn
- Seaborn, Matplotlib