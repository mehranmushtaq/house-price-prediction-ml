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
The scatter plot shows that predicted house prices closely follow actual values,
indicating strong model performance and a high R² score.

## 🚀 Getting Started

## ✅ Prerequisites

Before running this project, make sure you have the following:

- Basic knowledge of **Python**
- Understanding of **Machine Learning fundamentals**
- Familiarity with **Linear Regression**
- Installed **Python 3.x**
- Jupyter Notebook or any Python IDE

### Required Python Libraries
Install the required libraries using:

pip install numpy pandas matplotlib seaborn scikit-learn
## * Future Improvements

- Add Ridge & Lasso Regression

- Try Polynomial Regression

- Feature scaling and cross-validation

- Deploy model using Flask or FastAPI

- ## 👤 Author
**Mehran Mushtaq**  
B.Tech CSE | Machine Learning Enthusiast
