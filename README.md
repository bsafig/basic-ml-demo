# Basic Machine Learning Demo: Yahoo Finance and Hockey

## Overview

This project demonstrates two practical applications of machine learning using Python and Jupyter Notebooks:

1. **Stock Market Prediction**  
   Predicting future stock prices using historical data from Yahoo Finance.

2. **Stanley Cup Winner Prediction**  
   Predicting the winner of the NHL Stanley Cup using team statistics from past seasons.

The project is implemented in `demo-notebook.ipynb`, which contains all code, explanations, and results. All required CSV files for hockey data are located in the `CSV` folder.

---

## Contents

- `demo-notebook.ipynb`: Main notebook containing all code and analysis.
- `CSV/`: Folder containing NHL team statistics for each season (2000-2005, 2024, 2025).
- `README.md`: This file.

---

## Stock Market Prediction

**Goal:**  
Predict the closing price of a stock (GOOG by default) using linear regression.

**Steps:**
- Download historical stock data using `yfinance`.
- Clean and preprocess the data with `pandas`.
- Split the data into training and testing sets using `scikit-learn`.
- Train a linear regression model.
- Evaluate model performance using Mean Squared Error (MSE).
- Visualize actual vs. predicted prices using `matplotlib`.

**Programming Concepts:**
- Data acquisition and cleaning
- Feature engineering
- Train/test split
- Linear regression modeling
- Model evaluation
- Data visualization

---

## Stanley Cup Winner Prediction

**Goal:**  
Predict the winner of the 2025 Stanley Cup using team statistics from previous seasons.

**Steps:**
- Load team statistics from CSV files for each season.
- Standardize team names to account for relocations/name changes.
- Merge team stats with actual winners for supervised learning.
- Encode categorical variables using `LabelEncoder`.
- Train a Random Forest classifier to predict the winner.
- Apply the model to 2025 season data and output probabilities for each team.
- Evaluate prediction accuracy against the actual winner.

**Programming Concepts:**
- Data aggregation and merging
- Handling missing data and team name changes
- Label encoding for categorical features
- Random Forest classification
- Probability prediction for multi-class outcomes
- Model evaluation and interpretation

---

## How to Run

1. **Install Python (3.8+) and pip.**
2. **Install required packages:**
   ```
   pip install pandas yfinance matplotlib scikit-learn notebook ipykernel
   ```
3. **Open `demo-notebook.ipynb` in VS Code or Jupyter.**
4. **Select the correct Python kernel/interpreter.**
5. **Run all cells to reproduce results.**

---

## Notes

- NHL CSV files must be present in the `CSV` folder.
- The hockey prediction model is for demonstration; real-world sports outcomes are highly unpredictable.
- For more details on CSV creation, see the related project: "txt to csv for hockey predictions".

---

## Programming Concepts Demonstrated

- Data science workflow in Python
- Use of Jupyter Notebooks for interactive analysis
- Machine learning model training and evaluation
- Data visualization
- Handling real-world data issues (missing data, categorical encoding)
- Project organization and reproducibility

---

## Author

Benedikt Safigan
August 2025
