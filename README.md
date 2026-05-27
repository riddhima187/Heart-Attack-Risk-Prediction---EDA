# ❤️ Heart Attack Risk Prediction — Exploratory Data Analysis

A comprehensive **Exploratory Data Analysis (EDA)** project on a heart attack risk dataset. This notebook dives deep into patient health metrics, lifestyle factors, and clinical indicators to uncover patterns and risk factors associated with heart attacks.

---

## 🔍 Project Overview

Using a structured patient dataset (`heart_attack_prediction_dataset.csv`), this project answers 26 analytical questions through data wrangling, statistical analysis, and rich visualizations — covering everything from demographic distributions to correlations between lifestyle habits and cardiac risk.

---

## 📋 Key Questions Explored

| # | Question |
|---|---|
| 1–3 | Dataset shape, columns, and null value check |
| 4–9 | Average age, gender distribution, cholesterol, BMI, diabetes prevalence |
| 10–11 | Dietary habits and alcohol consumption distribution |
| 12–13 | Heart attack risk by diabetes status and gender |
| 14 | Country-level analysis (United States) |
| 15–16 | Stress levels and previous heart problems vs. risk |
| 17 | Correlation between stress and sedentary hours |
| 18–19 | Sleep deprivation and cardiac risk |
| 20 | Heart attack risk by age group |
| 21–22 | Feature engineering — Active Lifestyle flag, Alcohol Status label |
| 23–24 | Smoker distribution and overall risk distribution (pie charts) |
| 25–26 | Sleep hours histogram, blood pressure vs. age scatter plot |

---

## 📊 Visualizations Included

- **Bar charts** — Diet habits, alcohol consumption, previous heart problems vs. risk, stress levels, age-wise risk
- **Pie charts** — Smokers vs. non-smokers, heart attack risk distribution
- **Scatter plot** — Age vs. Systolic Blood Pressure colored by risk
- **Histogram** — Sleep hours distribution with KDE
- **Correlation bar chart** — Top features correlated with heart attack risk

---

## 🛠️ Tech Stack

| Library | Purpose |
|---|---|
| `pandas` | Data loading, wrangling, feature engineering |
| `numpy` | Numerical operations |
| `matplotlib` | Custom plotting |
| `seaborn` | Statistical visualizations |

---

## 📦 Installation

```bash
pip install pandas numpy matplotlib seaborn
```

---

## ⚙️ Usage

1. Place `heart_attack_prediction_dataset.csv` in the same directory as the notebook
2. Open and run `heart_attack_risk_prediction.ipynb` cell by cell

---

## 📁 Project Structure

```
Heart_Attack_Risk_Prediction/
│
├── heart_attack_risk_prediction.ipynb      # Main EDA notebook
├── heart_attack_prediction_dataset.csv     # Dataset (required)
└── README.md
```

---

## 🔢 Dataset Features

The dataset includes the following patient attributes:

- **Demographics** — Age, Sex, Country, Continent, Hemisphere
- **Clinical** — Cholesterol, Blood Pressure, BMI, Heart Rate, Diabetes, Previous Heart Problems
- **Lifestyle** — Smoking, Alcohol Consumption, Diet, Physical Activity Days/Week, Sedentary Hours/Day, Sleep Hours/Day
- **Psychosocial** — Stress Level
- **Target** — `Heart Attack Risk` (0 = No, 1 = Yes)

---

## 💡 Key Findings

- Patients with **previous heart problems** show significantly higher cardiac risk
- **Stress levels** have a measurable correlation with sedentary behavior
- **Sleep deprivation** (< 6 hrs) is associated with elevated risk compared to 7+ hours
- **Gender** and **diabetes status** both influence heart attack risk probability

---

## 📌 Notes

- Categorical columns (`Sex`, `Diet`, `Country`, etc.) are encoded numerically for correlation analysis
- Blood Pressure is split into Systolic and Diastolic for granular analysis
- This project is for **educational purposes** and does not constitute medical advice

---

## 🙋 Author

Built as a data analysis project to explore clinical and lifestyle risk factors associated with heart attacks using real-world structured health data.
