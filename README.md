# 🏠 House Price Prediction using Linear Regression

A Machine Learning project that predicts residential house prices using Multiple Linear Regression in Python.

## 📝 Overview
This project analyzes housing data to build a predictive model based on architectural and spatial features. By utilizing `Scikit-Learn`, the model identifies linear relationships between property attributes and their market value.

## 📊 Dataset & Features
The model utilizes the `house_prices_practice.csv` dataset. Key features used for prediction include:
* **OverallQual**: Rates the overall material and finish of the house.
* **GrLivArea**: Above grade (ground) living area square feet.
* **GarageCars**: Size of garage in car capacity.
* **TotalBsmtSF**: Total square feet of basement area.
* **YearBuilt**: Original construction date.
* **LotArea**: Lot size in square feet.

## & Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## How to Run
1. Clone the repository
2. Open 'ai model. ipynb' in Jupyter Notebo
3. Run all cells


## 📈 Model Performance
The model was trained using a **67/33 train-test split** and achieved high accuracy metrics:

| Metric | Score |
| :--- | :--- |
| **R² Score** | **0.974** |
| **Adjusted R²** | **0.971** |

### **Actual vs. Predicted Results**
The following plot demonstrates the strong correlation between the model's predictions and the actual market values:

![Actual vs Predicted](actual_vs_predicted.png)

## 🚀 Getting Started

### **Prerequisites**
Ensure you have the following Python libraries installed:
 pandas
 matplotlib
 scikit-learn

 ✨ Future Enhancements
• Feature Scaling: Implement StandardScaler to handle varying scales in features like LotArea.
• Regularization: Add Ridge and Lasso regression to improve generalization.
• Cross-Validation: Use K-Fold validation to ensure model stability.
• Deployment: Create a Flask or FastAPI web app for real-time price estimation.
Created by Mehran Mushtaq
