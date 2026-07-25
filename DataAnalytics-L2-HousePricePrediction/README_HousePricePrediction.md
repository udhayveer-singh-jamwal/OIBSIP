# 🏠 Predicting House Prices with Linear Regression

**Track:** Data Analytics (Oasis Infobyte SIP)
**Level:** Level 2 — Task 1
**Author:** Udhayveer Singh Jamwal

## 🎯 Objective
Build and evaluate a linear regression model that predicts house prices based on features such as area, location, number of rooms, and age. Develop end-to-end skills from data cleaning through to model interpretation.

## 🛠️ Tech Stack
- Python
- Pandas
- Scikit-learn (LinearRegression, Ridge, Lasso)
- Matplotlib
- Seaborn
- Jupyter Notebook

## 📂 Dataset
**Ames Housing Dataset** — 2,930 residential property sales in Ames, Iowa, with 82 raw features covering size, quality, condition, location, and sale details.

## 🔍 What's Inside
- EDA — null check, descriptive stats, distribution of `SalePrice`
- Feature selection — 12 interpretable predictors covering size, rooms, age, quality, and location
- Missing value handling (median imputation) + One-Hot Encoding for `Neighborhood`
- Correlation heatmap — identifying features most correlated with price
- Train/test split (80/20)
- Linear Regression model training
- Evaluation — MSE, RMSE, R² Score
- Actual vs Predicted scatter plot
- Residual plot (checking for random error distribution)
- Coefficient analysis — which features drive price up/down the most
- **Bonus:** Ridge & Lasso regularised model comparison

## 📈 Key Insights
1. **Overall Quality** and **Above-Ground Living Area** are the strongest predictors of sale price.
2. **Neighborhood/location** has a significant impact — certain neighborhoods command a large price premium even after controlling for size and quality.
3. Regularised models (Ridge/Lasso) help stabilize coefficients given the correlated dummy variables introduced by one-hot encoding location.

## 🚀 How to Run
1. Open `House_Price_Prediction.ipynb` in Jupyter Notebook, VS Code, or Google Colab.
2. Ensure `AmesHousing.csv` is in the same directory (or uploaded alongside, if using Colab).
3. Run all cells sequentially.

## ✅ Deliverables
- `House_Price_Prediction.ipynb` — full analysis & modeling notebook
- `AmesHousing.csv` — dataset used
- `README.md` — this file

---
*Submitted as part of the Oasis Infobyte Data Analytics SIP.*
