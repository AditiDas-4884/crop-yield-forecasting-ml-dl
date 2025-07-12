# 🌾 Crop Yield Prediction using Machine Learning & Deep Learning

This project aims to predict agricultural crop yield using machine learning and deep learning models. The dataset includes features like average rainfall, temperature, and pesticide usage. The goal is to compare model performance and interpret predictions using SHAP.

---

## 🛠️ Tools & Technologies

- **Languages:** Python
- **Libraries:** Scikit-learn, XGBoost, TensorFlow/Keras, SHAP, Pandas, Matplotlib, Seaborn
- **Techniques:** Regression, Hyperparameter Tuning, Dropout, Early Stopping, SHAP Interpretability

---

## 📊 Problem Statement

Accurate crop yield prediction helps farmers and policymakers make informed decisions. This project predicts yield (in hg/ha) using climatic and agricultural inputs such as:
- Average rainfall (mm/year)
- Average temperature (°C)
- Pesticide usage (tonnes)
- Crop type, location, and year

---

## 📁 Dataset

- **Source:** Kaggle  
- **Attributes:** Area, Item (crop), Year, Rainfall, Temperature, Pesticide Use, Yield  
- **Rows:** ~22,000+ records  
- [🔗 Link to Dataset](https://www.kaggle.com/datasets/adedokunjulius/yield-df)

---

## 🚀 Models Used

| Model              | R² Score | Notes                                     |
|-------------------|----------|-------------------------------------------|
| Linear Regression | 0.080     | Basic Machine Learning Model             |
| Decision Tree     | 0.972     | Second Best performing Machine Learning Model               |
| Random Forest     | **0.983**    | Best performing Machine Learning Model     |
| XGBoost           | 0.953    | Strong performance with boosting          |
| Deep Learning     | 0.961     | Tuned with dropout, early stopping, Learning Rate    |

---

## 🧠 Deep Learning Improvements

- Added **dropout layers** to reduce overfitting
- Used **early stopping** to prevent unnecessary training
- Optimized **learning rate and batch size** via randomized search

---

## 📈 SHAP Analysis

Model interpretability was achieved using **SHAP** (SHapley Additive exPlanations):



