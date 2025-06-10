
# 🌍 Carbon Footprint Estimator (Regression Task)

Estimate a person's *weekly carbon footprint* (in kilograms of CO₂) based on their *diet, **transport habits, and **electricity usage*.

---

## 🚀 Project Overview

This machine learning project is a regression task that predicts weekly CO₂ emissions using lifestyle-based features. The goal is to provide an estimate of an individual's carbon footprint and raise awareness about their environmental impact.

---

## 📌 Features

- 🔍 *Inputs*:
  - Diet: vegan, vegetarian, or omnivore
  - Transport: car, bike, public transport, or walk
  - Electricity usage: kWh per week
  
- 📤 *Output*:
  - Estimated CO₂ emissions in *kg/week*

- 🧠 *Model*:
  - Random Forest Regressor (can be switched with Linear or Tree-based models)

- 📈 *Evaluation*:
  - Mean Squared Error (MSE)
  - Actual vs Predicted graph for performance visualization

---

## 🛠 Tech Stack

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

---

## 📊 Sample Results

- *Mean Squared Error (MSE)*: ~25–40 kg²/week (varies with random seed)
- *Graph*: Displays a scatterplot comparing actual vs predicted CO₂ values

---

## 🧪 How It Works

1. *Simulated data* is generated for 300 individuals.
2. Each record includes:
   - Dietary choice
   - Transport mode
   - Electricity usage
3. CO₂ emissions are calculated using estimated emission factors.
4. The model learns patterns and predicts the CO₂ footprint for new users.
5. Evaluation is done using *MSE* and a *scatter plot* to compare actual and predicted values.

---
