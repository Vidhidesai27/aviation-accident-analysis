# ✈️ Aviation Accident Analysis & Predictive Modeling
![Python](https://img.shields.io/badge/Language-Python-blue?logo=python)
![Scikit-Learn](https://img.shields.io/badge/Model-Logistic%20Regression-orange)
![Weather](https://img.shields.io/badge/Feature-Weather%20Condition-lightgrey)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

This project analyzes over 88,000 aviation accident records from the United States using real-world data from the NTSB Accident Database. It explores spatial, temporal, and environmental patterns and uses logistic regression to predict accident severity based on weather conditions.

## 📊 Project Highlights

- 🗺️ **Geographic Trends**: Identified US states and countries with highest accident counts (California leads).
- 📈 **Time Trends**: Strong downward trend in accident frequency from 1982–2023 (R² = 0.90).
- 🌦️ **Weather Analysis**: Poor weather (IMC) significantly increases the likelihood of fatal injuries.
- 🚨 **Phase Analysis**: Landing and takeoff phases account for the highest fatal injury rates.
- 🧠 **Predictive Modeling**: Built a logistic regression model (Sklearn) predicting injury severity based on weather, with ~78% accuracy.

## 🔍 Key Questions Answered

1. Which countries and US states are most prone to accidents?
2. What injury types are most common by region?
3. Are certain flight phases more dangerous?
4. How does seasonality impact accident frequency?
5. How do weather and aircraft characteristics correlate with severity?

## 🛠️ Technologies Used

- **Python**
- **Pandas**, **Matplotlib**, **Seaborn**, **Scikit-learn**, **Statsmodels**
- Logistic Regression (statsmodels + sklearn)
- Correlation analysis & heatmaps
- Confusion matrix for model evaluation

## 🧪 Model Performance

- **Final Model**: Logistic Regression
- **Target**: Injury Severity (Fatal vs. Non-fatal)
- **Feature**: Weather Condition (IMC vs. VMC)
- **Accuracy**: 78.4%
- **Insights**:
  - Odds of fatal injury decrease ~83.5% in good weather (VMC)
  - High false negatives highlight need for model refinement

## 📁 Files Included

- `Group 2_Merged_ISYS812_final_project.ipynb` – Main notebook (EDA + modeling)
- `Group 2_Project Report_ISYS812.pdf` – Full project report with visualizations
- *(Optional)* `aviation_data.csv` – Include only if public and under 100MB

## 🧠 Lessons Learned

- Handling large real-world datasets and cleaning inconsistencies
- Working with time-series and categorical encodings
- Modeling real risk patterns using domain-relevant features
- Evaluating imbalanced binary classification problems with logistic regression

## 📬 Contact

Vidhi Desai  
[LinkedIn](https://www.linkedin.com/in/Vidhidesai27)
