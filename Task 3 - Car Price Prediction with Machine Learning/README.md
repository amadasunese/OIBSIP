**The task**
Car Price Prediction with Machine Learning

The price of a car depends on a lot of factors like the goodwill of the brand of the car,
features of the car, horsepower and the mileage it gives and many more. Car price
prediction is one of the major research areas in machine learning. So if you want to learn
how to train a car price prediction model then this project is for you.


**Car Price Prediction Using Machine Learning**

**Introduction**
The primary goal of this project is to apply machine learning techniques to predict the selling price of cars. This prediction model aims to assist both buyers and sellers in the used car market by providing an accurate estimate of a car's market value based on its characteristics.

**Data Overview**
The dataset comprises various attributes of cars, including selling price, present price, year of purchase, kilometers driven, fuel type, seller type, transmission type, and number of previous owners. The key features are:

Selling_Price: The price at which the car is sold.
Present_Price: The current market price of the car.
Driven_kms: The total distance driven by the car.
Fuel_Type, Selling_type, Transmission, Owner: Categorical variables indicating the car's fuel type, seller type, transmission type, and ownership history.

**Exploratory Data Analysis (EDA)**
The EDA phase involved an in-depth analysis of the dataset to understand the distributions of various features and their relationship with the selling price.

**Key Visualizations:**
Distribution of Selling Prices: Illustrates the range and common selling prices.
Car Age vs Selling Price: Shows how the car's value depreciates over time.
Fuel Type and Transmission Impact: Demonstrates the influence of fuel type and transmission on selling price.
Correlation Heatmap: Highlights the relationships between different features.

**Model Building**
A Random Forest Regression model was selected due to its robustness and ability to handle both categorical and numerical data.

**Steps Involved:**
Data Preprocessing: Categorical variables were encoded, and the data was split into training and testing sets.
Model Training: The Random Forest model was trained on the dataset.
Feature Importance Analysis: Identified the most influential factors affecting car prices.

**Model Evaluation**
The model's performance was evaluated using two metrics:

Mean Squared Error (MSE): Quantifies the average squared difference between the estimated values and what is estimated.
R-squared (R²): Indicates the proportion of the variance in the dependent variable that is predictable from the independent variables.

**Results:**

MSE: 0.95
R² Score: 0.96
Visualizations:

Feature Importance Plot: Highlights the significance of different features in the model.
Actual vs Predicted Prices: Compares the model's predictions with the actual selling prices.
Residual Plot: Analyzes the residuals to identify any patterns or biases.

**Conclusion**
The model demonstrated high accuracy, with the present price of the car being the most significant predictor. The insights gained from this project can significantly aid stakeholders in the used car market.