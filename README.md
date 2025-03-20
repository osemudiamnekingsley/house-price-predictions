# 🏡 House Price Prediction

Welcome to the **House Price Prediction** project! This project uses machine learning techniques to predict house prices based on various features. The goal is to build a predictive model that accurately estimates house prices using historical data.

---

## 📊 Project Overview

- **Objective:** Predict the sale prices of houses using a dataset with features like location, size, number of bedrooms, and other characteristics.  
- **Dataset:** The data is sourced from **Kaggle**.  
- **Tech Stack:** Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn, XGBoost.  
- **Models Used:** Linear Regression, Decision Trees, Random Forest, and XGBoost.  

---

## 📁 Dataset Description

The dataset contains the following key attributes:

- **Id:** Unique identifier for each property  
- **OverallQual:** Overall material and finish quality  
- **YearBuilt:** Year the house was built  
- **TotalBsmtSF:** Total square footage of the basement  
- **GrLivArea:** Above ground living area in square feet  
- **FullBath:** Number of full bathrooms  
- **GarageCars:** Number of cars in the garage  
- **SalePrice:** Sale price of the house (Target Variable)  

---

## 🚀 Project Workflow

1. **Data Preprocessing:**  
    - Handle missing values  
    - Perform exploratory data analysis (EDA)  
    - Feature engineering and selection  

2. **Model Building:**  
    - Train and evaluate models using various regression algorithms  
    - Tune hyperparameters for optimal results  

3. **Evaluation Metrics:**  
    - Root Mean Squared Error (RMSE)  
    - Mean Absolute Error (MAE)  
    - R-Squared Score  

---

## 🛠️ Installation

Follow these steps to set up the project:

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/house-price-prediction.git
    ```
2. Navigate to the project directory:
    ```bash
    cd house-price-prediction
    ```
3. Create a virtual environment:
    ```bash
    python -m venv env
    source env/bin/activate   # On Windows: env\Scripts\activate
    ```
4. Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```

---

## 📊 Example Visualization

Here is an example of a scatter plot showing the relationship between `GrLivArea` and `SalePrice`:

![GrLivArea vs SalePrice](./images/grlivarea_vs_saleprice.png)

---

## 🧪 Example Prediction

You can run the model using the following command:

```bash
python predict.py --input sample_input.csv
