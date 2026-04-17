# 📈 Sales Prediction using Python

> **CodeAlpha Data Science Internship — Task 4**



![Python](https://img.shields.io/badge/Python-3.8+-blue?style=flat-square&logo=python)




![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML-orange?style=flat-square&logo=scikit-learn)




![Status](https://img.shields.io/badge/Status-Completed-success?style=flat-square)



---

## 📌 Overview
This project predicts **future sales** based on advertising spend across
**TV, Radio, and Newspaper** platforms using regression models.
The analysis also delivers actionable insights on which advertising
channel has the strongest impact on sales outcomes.

---

## 📊 Model Results
| Model | R² Score | MAE |
|-------|----------|-----|
| Linear Regression | 0.8994 | 1.4608 |
| Random Forest | 0.9813 | o.6207 |
| Gradient Boosting | 0.9831| 0.6181 |

> ✅ **Best Model: Gradient Boosting** with the highest R² score

---

## 🔍 Key Insights
- 📺 TV advertising has the strongest correlation with sales; Business insight : TV ads drive the most sales impact.
- 📻 Radio has a moderate positive impact on sales
- 📰 Newspaper spend has the weakest influence on sales
- 💡 Reallocating budget from Newspaper → TV/Radio is likely to boost sales
- 🤖 Gradient Boosting delivered the best predictive performance

- Best model : Gradient Boosting
- Best R² score : 0.9831
- Best MAE : 0.6181 units
- TV correlation : 0.7822 ← strongest predictor
- Radio correlation : 0.5762
- Newspaper corr. : 0.2283 ← weakest predictor
- Avg sales : 14.02 units
- Max sales : 27.00 units
---

## 📷 Visualizations


![Spend vs Sales](plot2_spend_vs_sales.png)




![TV Impact Simulation](plot7_tv_impact_simulation.png)




![Actual vs Predicted](plot5_actual_vs_predicted.png)



---

## 🛠 Libraries Used
- `Pandas` — data cleaning & manipulation
- `Scikit-learn` — model building, evaluation & cross-validation
- `Matplotlib` & `Seaborn` — data visualization
- `NumPy` — numerical operations

---

## 👤 Author
**Samuel Okoosi**
CodeAlpha Data Science Intern
[LinkedIn](https://linkedin.com/in/thesamokoosi) • [GitHub](https://github.com/thesamokoosi)
