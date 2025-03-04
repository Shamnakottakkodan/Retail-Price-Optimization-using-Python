# Retail-Price-Optimization-using-Python
This project uses machine learning to optimize retail prices for products based on historical sales data and competitor pricing strategies.
The goal is to predict the optimal price point for a product that maximizes revenue while considering market conditions and competition.

Dataset
The dataset used in this project contains the following key features:

Product ID: Unique identifier for each product.
Unit Price: The current retail price of the product.
Quantity Sold: The number of units sold for each product.
Competitor Prices: The price of the product at competing stores or online platforms.
Discounts: Any discounts or promotions offered.
Sales Volume: Number of units sold at different price points.
The dataset was sourced from Kaggle and covers sales data over the past two years.

Dependencies
To run the code in this repository, you will need to install the following libraries:

pandas
numpy
matplotlib
seaborn
scikit-learn
plotly

Data Exploration
The project includes data exploration steps to analyze the sales trends and price distribution. Some key findings include:

Distribution of product prices over time.
Correlation between sales volume and competitor prices.
Analysis of how discounts impact sales.
Machine Learning Model
For price optimization, we used a Decision Tree Regressor model to predict the optimal price based on various features. The model is trained using historical sales data, and its performance is evaluated using metrics like Mean Squared Error (MSE).

Model Training:
The model is trained using the following steps:

Preprocess and clean the data.
Split the dataset into training and testing sets.
Train the model using the training set.
Evaluate the model’s performance using the testing set.
Results
The model provides an optimized price point for each product, helping to maximize revenue while staying competitive in the market. The results of the model can be visualized through plots showing predicted versus actual prices.

Future Work
Implementing additional machine learning models like Random Forest or Gradient Boosting to compare performance.
Incorporating more features such as seasonal trends or product reviews to further improve predictions.
Testing the model with real-time data for dynamic pricing adjustments.

