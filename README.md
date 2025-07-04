# Price Surge Detection (Mini ML Project)

This project is a machine learning pipeline designed to detect and analyze **price surge patterns** using simulated data. It was created as part of a mini project to demonstrate proficiency in data preprocessing, feature engineering, model building, and evaluation.


## Project Objective

To analyze and predict price surge behavior in the instant product delivery sector using simulated data representing platforms like Blinkit, Zomato, and Zepto.
The project focuses on identifying surge patterns based on date, discount percentage, platform, and categorical product features, and building a regression model to predict the final price under surge conditions.


## Skills Demonstrated

- **Feature Engineering**: Created new variables that capture demand intensity, day-of-week trends, and location-based insights.
- **Modeling**: Trained multiple ML models like Random Forest, Logistic Regression, and Decision Tree to classify surge vs. no-surge events.
- **Evaluation**: Compared model performance using accuracy, precision, recall, and F1-score. Tuned hyperparameters for improved generalization.
- **Interpretability**: Analyzed feature importances to explain model behavior and business relevance.


## Observations & Insights

- **Surge patterns** are more prominent during **weekends and festival days**.
- A **7-day rolling average** helped smooth out short-term fluctuations and reveal long-term trends in final pricing.
- The platform with the **highest price spike** was highlighted using peak annotation in the trend chart.
- **Random Forest Regressor** was used to predict final prices with the following metrics:
  Mean Absolute Error (MAE): 22.00
  Root Mean Squared Error (RMSE): 30.45
  R² Score: 0.87


## Interpretation

These findings can support:
- Better **dynamic pricing strategies** by identifying when and where price surges typically occur.
- Enhanced **transparency** for customers by anticipating price changes.
- Smarter **demand forecasting** by recognizing patterns in pricing data over time.


## Tech Stack

- **Language**: Python (Jupyter Notebook)
- **Libraries**: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`
- **Approach**: Supervised binary classification


## Notebook

The full implementation, from data loading to final model evaluation, can be found in the [`mpp2.ipynb`](./mpp2.ipynb) notebook.
Check out the notbook for visualizations.
