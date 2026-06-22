# housing-price-prediction-ml-dl
Comparative study of machine learning and deep learning models for housing price prediction using real-world property datasets.
# Housing Price Prediction Using Machine Learning and Deep Learning

## Project Overview

This project investigates housing price prediction using Machine Learning and Deep Learning techniques on real-world housing datasets.

The objective is to explore how advanced predictive models can improve housing price estimation by handling complex relationships within housing data. The project compares traditional machine learning methods with modern ensemble and deep learning approaches.

---

## Datasets

### 1. Connecticut Real Estate Sales Dataset
- Source: Data.gov
- More than 1 million real estate transaction records
- Features include:
  - Assessed Value
  - Sale Amount
  - Property Type
  - Residential Type
  - Town
  - Sales Ratio

### 2. USA Housing Listings Dataset
- Source: Kaggle
- Rental housing listings across the United States
- Features include:
  - Price
  - Square Footage
  - Bedrooms
  - Bathrooms
  - Property Type
  - Location
  - Amenities

---

## Data Preprocessing

Several preprocessing techniques were applied:

### Missing Value Handling
- Imputation of categorical features
- Removal of highly incomplete columns
- Dataset cleaning and validation

### Outlier Detection
- IQR-based filtering
- Percentile capping
- Z-score analysis

### Feature Engineering
- Log transformation for skewed variables
- Target encoding
- One-hot encoding of categorical variables

### Feature Scaling
- Standard Scaling
- Min-Max Scaling
- Robust Scaling

---

## Models Implemented

### Linear Regression
Used as the baseline model for comparison.

### Random Forest Regressor
An ensemble learning model capable of handling complex non-linear relationships.

### LightGBM
A gradient boosting framework optimized for large-scale structured datasets.

### Artificial Neural Network (ANN)
A deep learning model used to capture complex feature interactions and non-linear patterns.

---

## Evaluation Metrics

The models were evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

These metrics were used to compare prediction accuracy and model performance.

---

## Project Workflow

1. Data Collection
2. Data Cleaning
3. Feature Engineering
4. Exploratory Data Analysis
5. Model Training
6. Model Evaluation
7. Performance Comparison
8. Housing Price Prediction

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- LightGBM
- TensorFlow / Keras
- Matplotlib
- Seaborn

---

## Results

The project demonstrates that advanced Machine Learning and Deep Learning models can significantly improve housing price prediction compared to traditional methods.

The study highlights:
- Importance of data preprocessing
- Effectiveness of ensemble methods
- Benefits of deep learning for complex housing datasets

---

## Repository Contents

```
housing-price-prediction/
│
├── housing_price_prediction.ipynb
├── Housing_Price_Prediction_Report.pdf
├── README.md
```

---

## Author

**Kushal Kumar**

MSc Data Science  
University of Hertfordshire

Supervisor: Dr Sophie Koudmani

---

## Academic Project

This repository contains the implementation and report for the MSc Data Science Final Project:

**"Housing Price Prediction Using Machine Learning and Deep Learning"**
