# 🏠 House Price Predictor

A machine learning project that predicts residential home sale prices using the Kaggle Ames Housing dataset.

## 📊 Results
| Attempt | Model | R² Score | Kaggle RMSLE |
|---|---|---|---|
| 1 | Gradient Boosting | 92.01% | 0.13532 |
| 2 | XGBoost | 92.01% | 0.13226 ✅ Best |

**Leaderboard: Top 1,800+ submissions out of 4,000+**

## 🔍 Project Overview
Using 79 features describing nearly every aspect of a home, this project:
- Explores what drives house prices through EDA
- Engineers meaningful features from raw data
- Compares 5 regression models
- Achieves 92% R² with a Kaggle RMSLE of 0.13226

## 🛠️ Tools & Libraries
- Python, Jupyter Notebook
- pandas, numpy, matplotlib, seaborn
- scikit-learn, XGBoost

## 📁 Project Structure
- Data cleaning & missing value handling
- Exploratory Data Analysis (EDA)
- Feature Engineering (15 features created)
- Model Comparison (Linear, Ridge, Lasso, Random Forest, Gradient Boosting, XGBoost)
- Kaggle submission

## 📈 Key Insights
1. **Overall Quality** is the strongest predictor of sale price
2. **Total Square Footage** matters more than above-ground area alone
3. **Neighborhood** accounts for up to $150K difference in median price
4. **Garage Area** is a surprisingly strong predictor

## 🚀 How to Run
1. Clone this repo
2. Download `train.csv` from [Kaggle](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data)
3. Install dependencies: `pip install numpy pandas matplotlib seaborn scikit-learn xgboost jupyter`
4. Run `house_price_predictor.ipynb` top to bottom
