# 🚗 Automobile MPG Predictor Using Polynomial Regression

## 🔍 About
This project uses **polynomial regression** to predict automobile fuel efficiency (MPG) based on **vehicle weight**. While the current model only uses weight as the input feature, it can easily be extended to include other vehicle attributes such as **horsepower, displacement, cylinders, and acceleration**. Unlike linear regression, polynomial regression captures **nonlinear relationships** in the data, providing more accurate and interpretable predictions. This demonstrates how simple transformations can improve predictive modeling in a real-world dataset.  

---

## ✨ Features
- 🔹 Handles missing values using **mean imputation**  
- 🔹 Expands input features **polynomially** to capture nonlinear trends  
- 🔹 Compares **linear vs polynomial regression** models  
- 🔹 Visualizes relationships between vehicle attributes and MPG  
- 🔹 Provides **interpretable coefficients** to understand feature impact  
- 🔹 Easily extendable to include additional features for improved predictions  

---

## 🗂 Dataset
- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/auto+mpg)  
- **Dataset:** Auto MPG Dataset  
- **Features:**  
  - `cylinders`  
  - `displacement`  
  - `horsepower`  
  - `weight` *(used in this model)*  
  - `acceleration`  
  - `model year`  
  - `origin`  
- **Target variable:** `mpg` (miles per gallon)  

---

## 🛠 Installation
1. Clone the repository:  
```bash
git clone https://github.com/yourusername/automobile-mpg-polynomial-regression.git

