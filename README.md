# Supermarket Sales Prediction

This project aims to predict the daily sales for supermarket stores for the next 4 months. The model is trained using historical sales data and other relevant features to forecast future sales. The models used for prediction are **Linear Regression** and **XGBoost**.

### Project Overview:
The objective of this project is to forecast daily sales for each supermarket by considering various factors such as:
- **Day of the week**
- **Date**
- **Number of customers visiting the store**
- **Store's open/close status**
- **Promotion status**
- **Whether it's a state or school holiday**

### Models & Results 📊 :
1. **Linear Regression**:
   - **R² Score**: 0.8554 (Indicates the model fits the data)
   
2. **XGBoost**:
   - **R² Score**: 0.8871 (XGBoost outperforms Linear Regression)

### Files:
- **`Sales_Prediction.ipynb`**: Jupyter notebook that demonstrates data analysis, model building, training, and prediction process.
- **`real_data.csv`**: Contains real-world data used for testing the models and predicting future sales.
- **`sales.csv`**: Historical sales data used for training the models.
- **`Results.csv`**: Contains predicted sales values for each store from `real_data.csv`. 



### 📂 Project Structure:
```plaintext
📦 Supermarket Sales Prediction
│-- 📜 README.md                - Project documentation
│-- 📜 Sales_Prediction.ipynb   - Jupyter notebook for analysis and model training
│-- 📜 real_data.csv            - Real-world data used for model testing
│-- 📜 sales.csv                - Historical sales data used for training
│-- 📜 Results.csv              - File with predictions for sales per store
