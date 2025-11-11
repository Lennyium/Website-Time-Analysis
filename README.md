# 🕒 Website User Time Analysis

This project analyzes how different factors—specifically **user age** and **web browser type**—affect the amount of time users spend on a website.  
It uses **linear regression modeling** and **visual diagnostic checks** to assess relationships and assumptions.

---

## 📊 Features

- Reads and inspects data from `website.csv`
- Visualizes relationships between:
  - `age` and `time_seconds`
  - `browser` and `time_seconds`
- Fits **Ordinary Least Squares (OLS)** regression models:
  - Model 1: Predicts `time_seconds` based on `age`
  - Model 2: Predicts `time_seconds` based on `browser`
- Checks regression assumptions:
  - Normality of residuals (histogram)
  - Homoscedasticity (scatter plot of residuals vs fitted values)
- Predicts time on website for a **40-year-old user**
- Compares **average time spent** between Chrome and Safari users

---

## ⚙️ Requirements

Make sure the following Python libraries are installed:

```bash
pip install pandas numpy matplotlib statsmodels
