# california-housing-prediction
A machine learning project that predicts median house prices in California using demographic, economic, and geographic features. It includes data preprocessing, visualization, model training (Linear Regression), and evaluation with future scope for model improvement.

![anatolii-nesterov-Fiq341OZyMk-unsplash](https://github.com/user-attachments/assets/6eaf3413-e35b-48f5-86a4-77c60dc45cf2)

---

## 🎯 Objective

To build a machine learning model that predicts **housing prices in California** using features like income, population, geographical data, and proximity to the ocean.

---

## 📊 Dataset Description

The dataset includes information about various districts in California with the following features:

| Column Name        | Description |
|--------------------|-------------|
| `longitude`        | How far west a house is |
| `latitude`         | How far north a house is |
| `housingMedianAge` | Median age of houses in a block |
| `totalRooms`       | Total number of rooms in a block |
| `totalBedrooms`    | Total number of bedrooms in a block |
| `population`       | Total population in a block |
| `households`       | Total households in a block |
| `medianIncome`     | Median household income (×10,000 USD) |
| `medianHouseValue` | Median house value (USD) |
| `oceanProximity`   | Proximity to ocean (categorical) |

📦 [California Housing Prices Dataset – Kaggle](https://www.kaggle.com/datasets/camnugent/california-housing-prices)

---

## 🧪 Exploratory Data Analysis (EDA)

- Visualized distributions using **histograms** and **KDE plots**
- Analyzed missing values and outliers
- Count plots for categorical features
- Generated **correlation heatmaps** and **pair plots**
- Geographical visualizations with **Folium**

---

## 🛠️ Data Preprocessing

- **Missing Values**: Median imputation for `total_bedrooms`
- **Encoding**: One-hot encoding for `ocean_proximity`
- **Scaling**: Standardization with `StandardScaler`

---

## 🤖 Machine Learning Workflow

- **Feature/Target Split**: `X` (independent features), `y` (target: `medianHouseValue`)
- **Train/Test Split**: 80% training / 20% testing
- **Model Used**: Linear Regression (baseline)
- **Evaluation Metrics**:
  - Mean Squared Error (MSE)
  - R² Score

---

## 📈 Results & Observations

- Baseline linear regression gave **reasonable accuracy**
- `median_income` had the **strongest correlation** with house prices
- `latitude` and `longitude` were **spatially significant**

---

## 🚀 Future Enhancements

- Implement **Random Forest**, **Gradient Boosting**, or other ensemble models
- **Hyperparameter tuning** and **cross-validation**
- Apply **dimensionality reduction** if needed
- Incorporate **time-based** or **external economic features**

---

## 🧰 Tools & Libraries Used

- `Pandas`
- `NumPy`
- `Matplotlib`, `Seaborn`
- `Scikit-learn`
- `Folium`

---
