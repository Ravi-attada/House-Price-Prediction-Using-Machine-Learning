# 🏠 House Price Prediction Using Machine Learning

This project focuses on predicting house prices using machine learning techniques based on various property features such as area, number of bedrooms, bathrooms, stories, parking availability, air conditioning, and furnishing status.

The dataset was preprocessed by handling categorical variables through one-hot encoding and preparing the data for model training. Exploratory Data Analysis (EDA) was performed to understand the distribution of house prices and identify key factors influencing property value.

Two machine learning models were developed and compared:

* Linear Regression
* Random Forest Regressor

The models were evaluated using:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

The results showed that **Linear Regression outperformed Random Forest Regressor**, achieving an R² Score of approximately **0.65**, indicating a reasonably strong ability to predict house prices.

## 📊 Visualizations

The project includes:

* House Price Distribution Histogram
* Correlation Heatmap
* Actual vs Predicted Price Scatter Plot

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## 📈 Key Findings

* Property area is the strongest factor influencing house prices.
* Bathrooms, stories, parking spaces, and air conditioning significantly impact property value.
* Linear Regression provided better predictive performance than Random Forest for this dataset.
* The housing data exhibited largely linear relationships between features and price.

## 🎯 Business Recommendation

Real estate businesses should prioritize properties with larger areas, additional bathrooms, adequate parking, and modern amenities such as air conditioning, as these features have the greatest impact on market value and buyer demand.

