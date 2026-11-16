---
layout: page
title: "Predict Future Sales"
description: "Forecasts next month's sales for a Kaggle competition."
importance: 34
category: ai and data
related_publications: false
---

**Code:** [GitHub](https://github.com/mishraShilpa-28/predict-future-sales) · **Tech:** Python, pandas, scikit-learn, XGBoost

## The problem

Shops need to know how much of each item they will sell next month.

## What it does

- **Feature engineering** on daily sales: monthly totals, lags and item and shop statistics.
- **Gradient-boosting model** (XGBoost) with tuning.

## What I learned

- Time-series features, and why you must never train on the future.
