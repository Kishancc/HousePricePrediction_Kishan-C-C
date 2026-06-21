# House Price Prediction Using Machine Learning

## 📌 Project Overview

This project aims to predict house prices using machine learning techniques based on various property features such as area, number of bedrooms, bathrooms, parking availability, furnishing status, and other amenities. The project involves data preprocessing, exploratory data analysis (EDA), visualization, model building, and performance evaluation.

---

## 🎯 Problem Statement

Real estate buyers and sellers often rely on assumptions and outdated comparisons when estimating property values. This project uses machine learning models to predict house prices accurately and identify the factors that most influence property value.

---

## 📂 Dataset

Dataset: Housing Prices Dataset

The dataset contains information about:

* Area
* Bedrooms
* Bathrooms
* Stories
* Main Road Access
* Guest Room
* Basement
* Hot Water Heating
* Air Conditioning
* Parking
* Preferred Area
* Furnishing Status
* Price (Target Variable)

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook / Google Colab

---

## 📊 Project Workflow

### 1. Data Loading & Exploration

* Loaded the Housing.csv dataset
* Explored dataset structure
* Checked for missing values
* Identified target and feature variables

### 2. Data Cleaning

* Removed duplicate records
* Converted categorical variables into numerical format
* Applied One-Hot Encoding

### 3. Model Building

Two machine learning models were trained:

#### Linear Regression

A simple regression model used as a baseline.

#### Random Forest Regressor

An ensemble learning model that provides improved prediction accuracy.

### 4. Model Evaluation

Models were evaluated using:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

---

## 📈 Visualizations

The following visualizations were created:

1. House Price Distribution Histogram
2. Correlation Heatmap
3. Actual vs Predicted Price Scatter Plot

All charts are available in the `charts/` folder.

---

## 🔍 Key Findings

* Area is the most influential feature affecting house prices.
* Bathrooms and parking availability significantly impact property value.
* Houses located in preferred areas generally have higher prices.
* Random Forest Regressor performed better than Linear Regression.
* Property size has a stronger impact on price than several luxury amenities.

---

## 💡 Business Recommendation

Real estate companies should focus on properties with:

* Larger areas
* Multiple bathrooms
* Adequate parking
* Modern amenities
* Preferred locations

These features contribute significantly to higher property values and increased buyer demand.

---

## 📁 Project Structure

```text
HousePricePrediction/
│
├── analysis.ipynb
├── Housing.csv
├── summary.docx
├── README.md
│
└── charts/
    ├── chart1_price_distribution.png
    ├── chart2_correlation_heatmap.png
    └── chart3_actual_vs_predicted.png
```

---

## 🚀 Results

The project successfully predicted house prices using machine learning models. Random Forest Regressor achieved better performance and demonstrated the ability to capture complex relationships among housing features.

---

## 👨‍💻 Author

**Kishan C C**

Computer Science Engineering Graduate
Machine Learning & Data Science Enthusiast
