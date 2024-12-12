# prodigy-project-1


# House Price Prediction using Linear Regression

This project implements a linear regression model to predict house prices based on the square footage, number of bedrooms, and number of bathrooms. The model is developed using Python and popular machine learning libraries.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Dataset](#dataset)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction
Predicting house prices is a crucial aspect of real estate analysis. By leveraging linear regression, this project aims to provide a simple yet effective model for estimating house prices based on key factors such as square footage, the number of bedrooms, and the number of bathrooms.

## Features
- *Linear Regression Model*: Predict house prices with high accuracy.
- *Data Visualization*: Explore data through scatter plots and regression lines.
- *Performance Metrics*: Evaluate model performance using metrics like R-squared and Mean Squared Error (MSE).

## Technologies Used
- Python 3.9+
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

## Installation
1. Clone the repository:
   bash
   git clone https:https://github.com/buvan1234/prodigy-project-1
   
2. Create and activate a virtual environment:
   bash
   python -m venv venv
   source venv/bin/activate # For Windows: venv\Scripts\activate
   

   

## Dataset
The dataset should contain the following columns:
- *Square Footage*: The total area of the house in square feet.
- *Bedrooms*: The number of bedrooms in the house.
- *Bathrooms*: The number of bathrooms in the house.
- *Price*: The target variable (house price).

You can use your own dataset or publicly available datasets like the [California Housing dataset](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.fetch_california_housing.html).

Place the dataset in the data/ directory and ensure it is named house_data.csv.


   

## Results
The model's performance is evaluated using:
- *R-squared*: Indicates the proportion of variance explained by the model.
- *Mean Squared Error (MSE)*: Measures the average squared difference between predicted and actual values.



## Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a feature branch: git checkout -b feature-name.
3. Commit your changes: git commit -m 'Add feature-name'.
4. Push to the branch: git push origin feature-name.
5. Submit a pull request.


