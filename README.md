# Car Price Prediction  

## Problem Statement  
A Chinese automobile company plans to enter the US market by establishing local manufacturing and competing with American and European automakers. To gain insights into pricing trends, they have partnered with an automobile consulting firm to analyze key factors influencing car prices in the US.  

## Business Objective  
The objective is to develop a predictive model that helps management understand the crucial variables affecting car prices. This model will guide car design, optimize business strategies, and set competitive pricing.  

## Dataset  
The dataset includes various car attributes and their corresponding prices, collected through market surveys in the US.  

**Dataset Link:** [Car Price Dataset](https://drive.google.com/file/d/1FHmYNLs9v0Enc-UExEMpitOFGsWvB2dP/view?usp=drive_link)  

## Features & Workflow  
- **Data Preprocessing:** Handling missing values, encoding categorical variables, and feature scaling.  
- **Exploratory Data Analysis (EDA):** Identifying significant factors affecting car prices.  
- **Model Training & Evaluation:**  
  - Linear Regression  
  - Decision Tree Regressor  
  - Random Forest Regression  
  - Support Vector Regression  
  - **Gradient Boosting Regressor (Best Performing Model)**  
- **Feature Importance Analysis:** Determined the most influential factors.  
- **Hyperparameter Tuning:** Used **RandomizedSearchCV** to optimize the Gradient Boosting model for improved accuracy.  
- **Prediction on Test Data:** Evaluated using MAE, MSE, RMSE, and R² score.  

## Results  
- **Best Model:** Gradient Boosting Regressor  
- **Performance Metrics (After Hyperparameter Tuning):**  
  - **R² Score:** 0.889  
  - **MAE:** 2089.8  
  - **MSE:** 9,591,642.07  
  - **RMSE:** 3,097.03  

## Installation & Usage  
1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/car-price-prediction.git  
   cd car-price-prediction  
   ```  
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt  
   ```  
3. Run the Jupyter Notebook to train the model and make predictions.  

## Technologies Used  
- **Python** (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)  
- **Jupyter Notebook**  
- **Machine Learning Models:** Random Forest, SVR, Linear Regression, Decision Tree Regression, Gradient Boosting Regression  

## Future Enhancements  
- Implement **deep learning models** to improve accuracy.  
- Deploy the model as a **web application** for real-time predictions.  
- Integrate additional features such as **car age, brand reputation, and mileage** for better insights.  
