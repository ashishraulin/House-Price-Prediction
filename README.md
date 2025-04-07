# 🏠 California House Price Prediction using Machine Learning

This project predicts house prices in California using various features like population, average income, and more. We use the **California Housing dataset** from `sklearn.datasets` and apply **Linear Regression** for building the model.

## 📌 Objective

To create a regression model that can estimate median house values in different districts of California using census data.

## 🧠 Technologies Used

- Python
- Scikit-learn
- Pandas
- NumPy
- Matplotlib / Seaborn
- Google Colab

## 📊 Dataset

The **California Housing Dataset** is available via `sklearn.datasets.fetch_california_housing()` and contains 20,640 observations with 8 numerical features and a target variable:

### 🔹 Features:
- **MedInc**: Median income in block group
- **HouseAge**: Median house age in block group
- **AveRooms**: Average number of rooms
- **AveBedrms**: Average number of bedrooms
- **Population**: Block group population
- **AveOccup**: Average house occupancy
- **Latitude**
- **Longitude**

### 🎯 Target:
- **MedHouseValue**: Median house value for California districts (in $100,000s)

## 🔍 Exploratory Data Analysis (EDA)

Performed EDA to understand correlations, distributions, and outliers using:
- Heatmaps
- Pair plots
- Histograms

## 🤖 Model Used

- **Linear Regression**

## 📈 Evaluation Metrics

- **R² Score**: ~0.60 (can vary)
- **Mean Squared Error (MSE)**



![Predicted vs Actual](images/predicted_vs_actual.png)

```python
# Code used to generate the sample output (optional)
plt.scatter(y_test, y_pred, alpha=0.5)
plt.xlabel("Actual Prices")
plt.ylabel("Predicted Prices")
plt.title("Actual vs Predicted House Prices")
