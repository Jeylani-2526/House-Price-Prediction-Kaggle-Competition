# 🏡 House Price Prediction – Kaggle Competition

This repository contains my end-to-end workflow for the Kaggle [House Prices: Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques) competition.

## 🚀 Project Overview

This project tackles the classic regression problem of predicting final sale prices for homes in Ames, Iowa, based on a rich set of features describing each property.  
I built a complete data science pipeline—from raw data to leaderboard submission—using Python and popular libraries like pandas, scikit-learn, and XGBoost.

---

## 📚 Contents

- **notebooks/**: Main analysis notebook (`house_price_notebook.ipynb`)
- **src/**: (Optional) Scripts for feature engineering and modeling
- **outputs/**: Example submission and generated figures
- **data/**: (Placeholder) Not included for licensing reasons; see Kaggle for original datasets
- `requirements.txt`: Dependencies for running the code
- `README.md`: This file

---

## 🛠️ Main Steps

1. **Data Cleaning**: Handled missing values, removed outliers, ensured consistent data types.
2. **Exploratory Data Analysis (EDA)**: Visualized target and key predictors, explored feature relationships.
3. **Feature Engineering**: Created composite, ratio, and presence features (e.g., `TotalSF`, `TotalBath`, `QualCond`, `HasFireplace`).
4. **Model Selection**: Compared Linear Regression, Random Forest, and XGBoost; tuned hyperparameters for tree-based models.
5. **Model Training**: Achieved best performance with Linear Regression (public LB RMSE: ~0.14725).
6. **Submission**: Generated and submitted predictions to the Kaggle leaderboard.

---

## 🏆 Results

- **Best Model:** Linear Regression
- **Leaderboard Score (RMSE, log scale):** `0.14725` (public leaderboard)
- **Top Features:** `TotalSF`, `OverallQual`, `QualCond`, `LotArea`, `TotalBath`, and presence flags like `HasFireplace`

---

## 💻 How to Run

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/house-price-prediction.git
    cd house-price-prediction
    ```

2. Set up a virtual environment and install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Download the competition data from [Kaggle](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data) and place it in the `data/` folder.

4. Run the notebook in `notebooks/` to reproduce the analysis and results.

---

## 📝 Notes

- **No data is included in this repo** (per Kaggle rules). Use scripts and notebooks with your downloaded copy.
- Feature engineering was the key driver of performance in this project!
- The workflow is easily adaptable for similar tabular regression problems.

---

## 📬 Contact

If you have any questions, feel free to reach out via [LinkedIn](https://www.linkedin.com/in/abdullahi-jeylani-1a7b83278/) or by email at abdallamuhammed07@gmail.com.

---

## 🤝 Acknowledgments

- Kaggle community for inspiring discussions and kernels
- [House Prices: Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques) competition organizers

---

