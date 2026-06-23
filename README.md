# 🚗 Used-car-price-prediction-segmentation

### Developed a used car analytics system that predicts vehicle resale prices and identifies market segments through machine learning, leveraging XGBoost, feature engineering, and unsupervised clustering techniques.

## 📌 Overview

This project builds machine learning models to predict used car prices and segments vehicles into different market categories using clustering techniques.

### Objectives

* Predict used car prices using regression models.
* Segment vehicles into meaningful market groups.
* Compare multiple machine learning algorithms.

---

## 📂 Dataset

* Source: Kaggle Used Car Dataset
* Records: 4,009
* Features: Brand, Model, Mileage, Fuel Type, Engine, Transmission, Accident History, Price, etc.

---

## 🔧 Data Preprocessing

* Handled missing values.
* Converted price and mileage to numeric format.
* Extracted:

  * Car Age
  * Horsepower
  * Engine Size
* Applied log transformation on price.

---

## 📊 Exploratory Data Analysis

Performed analysis on:

* Price distribution
* Mileage distribution
* Brand popularity
* Average price by brand
* Price vs Mileage relationship

---

## 🤖 Models Used

### Regression Models

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor
* XGBoost Regressor

### Best Model Performance

| Model                           |   R² Score |
| ------------------------------- | ---------: |
| XGBoost + Log Target            | **0.8415** |
| Random Forest + Log Target      |     0.8139 |
| Random Forest + Engine Features |     0.1274 |
| Random Forest                   |     0.1091 |

---

## 🎯 Market Segmentation

### Algorithm

* K-Means Clustering

### Features Used

* Price
* Mileage
* Car Age
* Horsepower
* Engine Size

### Optimal Clusters

* K = 4

### Segments Identified

* Budget Cars
* Mid-Range Cars
* Premium Cars
* Luxury Cars

---

## 📈 Key Findings

* Mileage is the most influential factor affecting price.
* Brand, horsepower, engine size, and vehicle age significantly impact resale value.
* Log transformation improved prediction performance dramatically.
* XGBoost achieved the highest accuracy with an R² score of 0.8415.

---

## 🛠 Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* XGBoost

---

## 🚀 Results

### Price Prediction

* Best Model: XGBoost
* R² Score: **0.8415**

### Market Segmentation

* K-Means successfully identified four distinct vehicle segments.

---

## 📌 Future Improvements

* Hyperparameter tuning
* Additional feature engineering
* Separate models for luxury vehicles
* Incorporating vehicle condition and ownership history

---

## 👨‍💻 Author
Mukku Sriram
AI & Machine Learning Project – Used Car Price Prediction and Segmentation

