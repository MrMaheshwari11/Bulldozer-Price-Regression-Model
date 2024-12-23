# Bulldozer Price Regression Model  

## Project Overview  
This project focuses on developing a robust machine learning model to predict the sale prices of bulldozers using historical auction data. By leveraging Random Forest Regression and extensive feature engineering, the model delivers precise and reliable predictions, providing insights for equipment auctioneers and buyers to make informed decisions.  

## Features  
- Predict bulldozer sale prices with high accuracy.  
- Time-series feature engineering for better predictive performance.  
- Exploratory Data Analysis (EDA) for understanding dataset patterns.  
- Scalable pipeline for handling large datasets.  

## Dataset  
The dataset used in this project contains over **400,000 records** of bulldozer sales, including attributes like equipment type, sale date, age, and usage hours. The dataset is publicly available on Kaggle.  

- [Download Dataset](https://www.kaggle.com/competitions/bluebook-for-bulldozers/data)  

## Model Highlights  
- **Algorithm Used**: Random Forest Regression  
- **Evaluation Metric**: Root Mean Squared Logarithmic Error (RMSLE)  
- **Performance**: Achieved RMSLE of **0.24**, showcasing the model’s effectiveness in handling non-linear data and feature interactions.  

## Key Steps  
### 1. Data Preprocessing  
- Cleaned and handled missing values in the dataset.  
- Encoded categorical features using label encoding.  
- Engineered features such as `Equipment Age` and `Usage Hours`.  

### 2. Exploratory Data Analysis (EDA)  
- Analyzed data distribution and trends using visualizations.  
- Identified and treated outliers affecting model performance.  

### 3. Model Training  
- Used a **Random Forest Regressor** to predict prices.  
- Performed **Hyperparameter Tuning** using GridSearchCV to optimize the model.  

### 4. Model Evaluation  
- Evaluated the model using RMSLE, ensuring a balanced evaluation of overestimated and underestimated predictions.  

## Technologies Used  
- **Programming Language**: Python  
- **Libraries**:  
  - Pandas (Data Manipulation)  
  - NumPy (Numerical Computing)  
  - Scikit-learn (Machine Learning)  
  - Matplotlib & Seaborn (Data Visualization)  

## Results  
- The model successfully predicts bulldozer sale prices with an RMSLE of **0.24**.  
- Visualizations highlight the significance of features like `Equipment Age` and `Usage Hours`.  

## Future Improvements  
- Integrate advanced algorithms like **XGBoost** or **LightGBM** for comparison.  
- Develop a user-friendly interface for real-time price predictions.  
- Incorporate additional features such as regional economic data for enhanced accuracy.  

## License  
This project is licensed under the **MIT License**. You are free to use, modify, and distribute the code with proper attribution.  

## Acknowledgments  
- **Dataset**: Kaggle’s Bluebook for Bulldozers competition.  
- Inspired by practical use cases in predicting equipment auction prices.  

## Connect with Me  
Feel free to connect with me for any queries, suggestions, or collaboration opportunities:  
- **Name**: Manishkumar Maheshwari  
- **Email**: [manish1111maheshwari@gmail.com](mailto:manish1111maheshwari@gmail.com)  
- **GitHub**: [MrMaheshwari11](https://github.com/MrMaheshwari11)  



