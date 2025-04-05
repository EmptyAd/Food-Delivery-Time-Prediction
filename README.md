# 🛵 Food Delivery Time Prediction

This project aims to predict food delivery times using various machine learning algorithms. The objective is to identify the most accurate model for estimating delivery durations based on several real-world features like distance, weather, traffic, and courier experience.

## 📌 Dataset

The dataset includes the following features:
- Distance (in km)
- Weather conditions
- Traffic level
- Time of day
- Courier experience (in years)
- Vehicle type
- Preparation time
- Target: Delivery time (in minutes)

## 🔍 Exploratory Data Analysis (EDA)

EDA was conducted to understand the relationships between features and delivery time using:
- Distribution plots
- Boxplots
- Heatmaps
- Countplots

## ⚙️ Models Trained

The following models were implemented and evaluated:
- **Linear Regression**
- **Random Forest Regressor**
- **LightGBM Regressor**
- **XGBoost Regressor**

Each model's performance was assessed using **Mean Absolute Error (MAE)**, and hyperparameter tuning was done using **GridSearchCV**.

## 🏆 Results

| Model              | MAE (Lower is Better) |
|-------------------|------------------------|
| **Linear Regression** | ⭐ **Best** |
| Random Forest     | Good                   |
| LightGBM          | Good                   |
| XGBoost           | Good                   |

**Linear Regression** outperformed all other models, indicating a strong linear relationship in the data.

## 📈 Visualizations

- Actual vs Predicted plots for each model  
- Bar chart comparing MAE across all models

## 📎 Kaggle Notebook

🔗 [View Full Notebook on Kaggle](https://www.kaggle.com/code/arsri1/food-delivery-time-prediction)

## 🧾 Conclusion

> After extensive modeling and tuning, **Linear Regression** emerged as the top performer with the lowest MAE. Despite testing more complex models, the simplicity of Linear Regression proved most effective for this dataset.

---

