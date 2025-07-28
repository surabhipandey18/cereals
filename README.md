# Cereal Rating Prediction using Linear Regression

This project demonstrates the use of **Linear Regression** for predicting the rating of breakfast cereals based on their nutritional attributes. The dataset contains 77 different cereals with features such as calories, fat, sodium, fiber, sugars, and vitamins.

---

## Dataset Overview

- **Rows:** 77  
- **Columns:** 16  
- **Features:** Nutritional details (calories, protein, fat, sodium, fiber, sugars, vitamins, etc.)  
- **Target Variable:** `rating`

### Sample Columns:
- name  
- mfr (manufacturer)  
- type (cold/hot)  
- calories  
- protein  
- fat  
- sodium  
- fiber  
- sugars  
- potass  
- vitamins  
- weight  
- cups  
- rating (target)

---

## Methodology

1. **Data Preprocessing**  
   - Checked for missing values and handled them using `SimpleImputer`.  
   - Selected relevant features for model training.  

2. **Model Training**  
   - Split dataset into training and test sets using `train_test_split`.  
   - Implemented **Linear Regression** using `sklearn.linear_model.LinearRegression`.  

3. **Evaluation**  
   - Calculated **Mean Squared Error (MSE)** and **R² score** to assess model performance.

---

## Results

- **Mean Squared Error (MSE):** `0.5036`  
- **R² Score:** `0.9973`  

This indicates that the model fits the dataset extremely well, with predictions closely matching the actual cereal ratings.

---

## Dependencies

- pandas  
- matplotlib  
- seaborn  
- scikit-learn

Dataset taken from kaggle.

License
This project is licensed under the MIT License.

Author: Surabhi Pandey
