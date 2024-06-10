
Sales Data Analysis and Prediction

 Description

This project analyzes and visualizes sales data, then builds a machine learning model to predict future sales revenue. The dataset contains information on transactions, including product categories, units sold, unit prices, and regions.

 Installation

To run this project, you need Python 3.x and the following libraries:
- pandas
- matplotlib
- seaborn
- scikit-learn
- numpy


 Usage

1. Load the Dataset:
   The dataset is loaded from a CSV file into a pandas DataFrame.
  

2. Data Preprocessing:
   Unnecessary columns are dropped, and date columns are converted to datetime objects.


3. Data Visualization:
   Various visualizations are created to understand the sales trends and distributions.
   

4. Machine Learning Model:
   A Linear Regression model is built to predict total revenue based on various features.
   

5. Future Predictions:
   Predictions are made for future dates using the trained model.
   

 Data Description

The dataset contains the following columns:
- `Date`: Date of the transaction
- `Product Category`: Category of the product sold
- `Product Name`: Name of the product sold
- `Units Sold`: Number of units sold
- `Unit Price`: Price per unit
- `Total Revenue`: Total revenue from the transaction
- `Region`: Region where the sale was made
- `Payment Method`: Method of payment

 Visualizations

 Revenue by Product Category


 Revenue by Region


 Sales Distribution by Payment Method


 Unit Price vs. Units Sold


 Total Revenue Over Time

 Machine Learning Model;

Feature Selection and Preprocessing:
Categorical features are one-hot encoded, and the data is split into training and testing sets.

Model Training:
A Linear Regression model is trained on the preprocessed data.

Model Evaluation:
The model is evaluated using Mean Squared Error.

Future Predictions:

Predictions are made for future dates from September 2024 to December 2024 based on historical averages of units sold and unit prices.

 Testing and Debugging;

 Common Issues:
- Loading the Dataset: Ensure the CSV file exists and column names are correctly spelled.
- Date Conversion**: Verify the date format in the dataset.


