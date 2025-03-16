# **Housing Price Prediction**

## **Overview**
This project focuses on predicting **housing prices** using **machine learning techniques**. The dataset contains various features related to houses, such as **location, size, number of rooms, and other factors**, which influence the overall price. The goal is to build a model that can accurately predict house prices based on these features.

---

## **Dataset: California Housing Dataset**
- **Source**: [California Housing Dataset - Scikit-Learn](https://scikit-learn.org/stable/datasets/real_world.html#california-housing-dataset)  
- **Description**: This dataset is based on the **1990 California Census Data** and is commonly used for **house price prediction**.  
- **Total Samples**: `20,640`  
- **Total Features**: `8` (excluding the target variable `MEDV`)  

### **Target Variable (`MEDV`)**
- **Represents the median house value (in $100,000s)** for California districts.
- Example: A value of `2.5` means the median house price is **$250,000**.

### **Features in the Dataset**
The dataset contains **various geographical and demographic attributes** that influence house prices.

| Feature Name   | Description |
|---------------|------------|
| `MedInc`      | Median income in the district |
| `HouseAge`    | Median age of houses |
| `AveRooms`    | Average number of rooms per household |
| `AveBedrms`   | Average number of bedrooms per household |
| `Population`  | Total population in the district |
| `AveOccup`    | Average household size |
| `Latitude`    | Latitude of the district |
| `Longitude`   | Longitude of the district |

---

## **Project Workflow**
1. **Data Preprocessing**  
   - Load and clean the dataset.  
   - Normalize numerical features for better model performance.  
   - Split the dataset into **training (80%)** and **testing (20%)** sets.  

2. **Model Selection**  
   - A **regression model** is used to predict house prices.  
   - Hyperparameter tuning is performed to improve accuracy.  

3. **Model Evaluation**  
   - The model is evaluated using **Mean Squared Error (MSE)**.  

---

## **Results**
- The trained **regression model** provides accurate house price predictions.  
- The evaluation metrics (such as **MSE and R²**) are used to assess performance.  

---

## **Future Improvements**
- Improve predictions using **feature engineering**.  
- Incorporate **real-time data** from online property listings.  

---

### **Notes**
- Open the **Housing_prediciton.ipynb** file in **Google Colab** or **Jupyter Notebook**. 
- If using **Google Colab**, make sure to load the dataset before running the notebook.  
- The dataset is fetched directly from **Scikit-Learn**, so no manual download is needed.  
