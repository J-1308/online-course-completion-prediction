# Predicting Online Learning Progress

This project explores whether learner demographics, engagement behaviour, and platform-related features can be used to predict progress in online learning.

Two binary targets were created from course completion rates:

- **ModerateProgress**: 50% or more completed
- **MeaningfulProgress**: 75% or more completed

The analysis included:
- exploratory data analysis (EDA)
- target engineering
- dummy-variable encoding
- logistic regression and decision tree models
- evaluation using accuracy, confusion matrices, precision, recall, and F1-score

## Main takeaway
Some features, especially `Education_Level`, `Field_of_Study`, `Device_Used`, and `Platform_Used`, showed useful signal, but simple baseline models had limited predictive power overall.

## Tools used
- Python
- pandas
- Matplotlib
- Seaborn
- scikit-learn
