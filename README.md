# 🧠 NLP Sentiment Analysis on Financial News & S&P 500 Prediction

This project leverages Natural Language Processing (NLP) to extract sentiment from Reddit financial news headlines and predict the next-day movement of the S&P 500 index using machine learning models.

---

## 📌 Project Overview

- Extract sentiment scores from financial news using the VADER sentiment analyzer.
- Merge sentiment data with historical S&P 500 returns.
- Train classification models to predict whether the S&P 500 will go **up or down** the next day.
- Evaluate and compare performance using Logistic Regression and Random Forest.
- Visualize results, correlations, and feature importance.

- ---

## 🛠️ Tech Stack

- **Language:** Python
- **Libraries:** Pandas, NLTK, Scikit-learn, Seaborn, Matplotlib
- **Models:** Logistic Regression, Random Forest
- **Sentiment Tool:** VADER (Valence Aware Dictionary and sEntiment Reasoner)

---
## 📈 Results

- **Random Forest** outperformed Logistic Regression by capturing nonlinear patterns.
- Feature importance showed **Lagged Sentiment** and **Lagged Return** as the most predictive features.
- Sentiment alone showed weak correlation, but combining historical data improved accuracy.

---

## 📊 Visuals

- Regression plot: Sentiment vs. Next-Day Return
- Confusion matrices for model predictions
- Bar chart of feature importances from Random Forest

---

## 📚 Learnings & Takeaways

- Single-day sentiment is noisy and weak alone.
- Historical trends (lag features) significantly improve prediction power.
- Tree-based models outperform linear models when relationships are not obvious.

---
