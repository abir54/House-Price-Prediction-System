🏠 House Price Prediction System
(Mini Project for College)

This project aims to predict real estate prices using various machine learning models and deploy it as an interactive web application. By analyzing historical housing data, it enables users to estimate property prices more accurately, assisting them in making better investment and purchase decisions.

📌 Objectives
* Predict property prices using historical housing data and multiple machine learning algorithms.
* Analyze feature importance to identify key price-driving factors.
* Compare and evaluate different models for accuracy and efficiency.
* Deploy the model as a user-friendly web application using Streamlit.

🔍 Dataset

Source:Kaggle - https://www.kaggle.com/datasets/sukhmandeepsinghbrar/house-prices-india

Features Include:Location,Number of rooms,Area (sq ft),Number of bedrooms,Median income,Population,Additional engineered features

Target Variable:Property Price

🧠 Machine Learning Models Used

| Model                    | Description                                                               |
|--------------------------|-------------------------------------------------------------------------- |
| Linear Regression       | Fits a straight line to predict target values.                            |
| Lasso Regression      | Uses L1 regularization for feature selection and reducing overfitting.       |
| Ridge Regression       | Employs L2 regularization to handle multicollinearity in data.               |
| Decision Tree Regressor | Uses a tree-like structure to split data and predict continuous values.      |
| Random Forest Regressor | Combines multiple decision trees to enhance accuracy and reduce overfitting. |
| XGBoost Regressor      | High-performance gradient boosting algorithm minimizing prediction errors.   |

📈 Evaluation Metrics

| Metric                         | Description                                                   |
| -------------------------------|---------------------------------------------------------------|
| R² Score                    | Measures how well the model explains variance in the target variable. |
| Mean Absolute Error (MAE)      | Average of absolute differences between actual and predicted prices.|
| Mean Squared Error (MSE)       | Average of squared differences (penalizes larger errors).           |
| Root Mean Squared Error (RMSE) | Square root of MSE, in same units as target.                        |

🛠️ Tech Stack
Language: Python
Libraries:
  * pandas, numpy — Data manipulation
  * matplotlib, seaborn, plotly — Data visualization
  * scikit-learn, xgboost — Machine learning models
  * streamlit — Web application framework

🚀 How to Run the Project

1. Clone the Repository:
   git clone https://github.com/abir54/House-Price-Prediction-System.git
   cd House-Price-Prediction-System
   
2. Install Dependencies:
   pip install -r requirements.txt

3. Run the Web Application:
   streamlit run app.py
   

📄 Project Report

For detailed methodology, data analysis, model performance comparison, and visualization, refer to the 

👥 Contributors

* Student Name: Abir Banerjee (@abir54)
* University: Kalinga Institute of Industrial Technology (KIIT University)
* GitHub Repository: [House-Price-Prediction-System](https://github.com/abir54/House-Price-Prediction-System)



