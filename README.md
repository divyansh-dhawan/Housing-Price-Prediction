# 🏠 House Price Prediction

This project demonstrates a complete machine learning pipeline for predicting house prices using Python and popular data science libraries. It involves data cleaning, exploratory data analysis (EDA), feature engineering, and regression modeling to deliver accurate predictions.

## 📁 Project Structure

- `House Price Prediction.ipynb`: Jupyter Notebook that walks through each stage of the workflow, including code, plots, and results.

## 🧰 Technologies Used

- Python
- Pandas & NumPy for data manipulation
- Matplotlib & Seaborn for visualization
- Scikit-learn for machine learning models and evaluation

## 🚀 Workflow Overview

1. **Data Loading**  
   The dataset (`housing.csv`) is loaded and basic data inspection is performed using `.info()` and `.describe()`.

2. **Data Preprocessing**
   - Handling missing values
   - Encoding categorical features (if any)
   - Feature scaling and transformation

3. **Exploratory Data Analysis (EDA)**
   - Distribution of numerical features
   - Correlation heatmaps
   - Pair plots and scatter plots to understand feature relationships

4. **Model Building**
   - Linear Regression
   - Decision Tree Regressor
   - Random Forest Regressor
   - Optionally other models like Ridge, Lasso, or XGBoost can be added

5. **Model Evaluation**
   Metrics used:
   - Mean Absolute Error (MAE)
   - Mean Squared Error (MSE)
   - R² Score

   Evaluation also includes visualization of predicted vs actual values.

## 📊 Results

The model performances are compared, and the best one is chosen based on evaluation metrics. Visual plots help interpret the reliability and variance of predictions.

## 📂 Dataset

Make sure the file `housing.csv` is located in the same directory as the notebook.

## 🛠️ How to Run

1. Clone this repository or download the notebook.
2. Install the required libraries:
   `pip install pandas numpy matplotlib seaborn scikit-learn`
3. Launch the notebook:
   `jupyter notebook House\ Price\ Prediction.ipynb`
