# Predictive Modelling of Customer Bookings

Welcome to the Predictive Modelling of Customer Bookings project repository! This Jupyter notebook is designed to provide you with a starting point for predictive modeling. We leverage various packages for data manipulation, feature engineering, and machine learning to gain insights into customer bookings.

## Project Overview

In this project, our goal was to create a predictive model to better understand and forecast customer booking behavior. We've discovered some key insights that shed light on the factors influencing bookings:

- **Critical Variable**: The most influential variable in our model is `purchase_lead`, representing the time between purchase and departure.

- **Flight Information**: Factors related to the flight, such as flight time and duration, were found to be significant predictors. Surprisingly, the customer's booking origin did not play a major role.

## Model Evaluation

Our model achieved the following metrics:

- Precision: 0.8
- Recall: 0.006

While our model shows promise, there is room for improvement to enhance its predictive power. We believe that incorporating more customer-centric features into the model could be a valuable next step.

## How to Use This Repository

- `predictive_model.ipynb`: This Jupyter notebook contains the code and documentation for the predictive modeling task. Feel free to explore and adapt it to your specific needs.

- `data/`: This directory houses the dataset used for the project. You can find the raw data and any preprocessed datasets here.

- `results/`: This directory stores the model evaluation results, including metrics, charts, and any insights gained from the analysis.

## Getting Started

To get started with this project, clone the repository to your local machine:

```shell
git clone https://github.com/your-username/Predictive-Modelling-of-Customer-Bookings.git
