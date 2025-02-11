# 🚗 Car Price Analysis and Prediction

This project involves **Exploratory Data Analysis (EDA)** and **Predictive Modeling** on a car price dataset. The objective is to uncover key insights about car price trends and develop machine learning models to predict car prices based on various features.

## 📊 Exploratory Data Analysis (EDA)

- **Price Distribution:** Car prices are right-skewed, indicating a majority of cars are priced in the lower range with fewer high-priced vehicles.
- **Correlation Heatmap:** Strong positive correlation between car price and features like **Year** and **Engine Size**. In contrast, **Mileage** shows a negative correlation with price, indicating higher mileage reduces car value.
- **Average Price by Brand:** Premium brands (e.g., *Mercedes, BMW, Audi*) tend to have higher average prices compared to economy brands.
- **Price vs. Mileage:** A clear inverse relationship exists; as mileage increases, car price tends to decrease. Different fuel types show slight variations in this trend.
- **Transmission Type Distribution:** Manual transmissions are slightly more common than automatic ones in this dataset.
- **Price Trends Over the Years:** Car prices have shown an increasing trend over the years, likely due to inflation, technological advancements, and evolving market demands.

---

## 🤖 Predictive Modeling

Two regression models were built to predict car prices:

1. **Linear Regression Model**
   - **Mean Squared Error (MSE):** 1,137,443.86
   - **R² Score:** 0.8762
   - Performs well, capturing linear relationships effectively.

2. **Decision Tree Regressor**
   - **Mean Squared Error (MSE):** 2,523,674.37
   - **R² Score:** 0.7253
   - Captures non-linear patterns but tends to overfit compared to linear regression.

---

## 🚀 Key Takeaways

- **Year of Manufacture**, **Engine Size**, and **Mileage** are significant predictors of car prices.
- The **Linear Regression Model** outperformed the **Decision Tree Regressor** in terms of accuracy.
- Data preprocessing, such as handling missing values and duplicates, played a crucial role in model performance.

---

## 📁 Technologies Used

- **Python**
- **Pandas & NumPy** (Data Manipulation)
- **Matplotlib & Seaborn** (Data Visualization)
- **Scikit-learn** (Machine Learning Models)

---

## 📢 Conclusion

This analysis highlights important factors influencing car prices and demonstrates how simple machine learning models can predict prices with high accuracy. Future improvements could include using advanced models like **Random Forests** or **Gradient Boosting** and incorporating more features.

---

