# Predicting Late Deliveries at Order Time

## Project Overview

This project focuses on predicting whether an order is likely to be delivered late using machine learning techniques.

The objective is to help supply chain and operations managers identify potential delivery risks at the time an order is placed, allowing them to make better operational decisions.

The project uses the DataCo Smart Supply Chain dataset and applies data preprocessing, feature engineering, model comparison, and evaluation techniques.

## Business Problem

Late deliveries can negatively affect customer satisfaction and supply chain performance.

This project investigates how historical order information can be used to identify orders at risk of late delivery before the delivery process takes place.

## Dataset

- Dataset: DataCo Smart Supply Chain
- Domain: Logistics and Supply Chain Management
- Final dataset: 62,897 shipped orders
- Target: Late delivery prediction

Cancelled and fraudulent orders were excluded because they were not shipped.

## My Contribution

**Role: Preprocessing & Modelling Lead**

My main responsibilities included:

- Data cleaning and preprocessing.
- Handling missing values and encoding categorical variables.
- Feature engineering using order-related time information.
- Preventing data leakage by excluding information unavailable at checkout.
- Comparing multiple machine learning classification models.
- Evaluating model performance and selecting a classification threshold.

## Methodology

1. Data understanding and exploration.
2. Data cleaning and preprocessing.
3. Order-level data preparation.
4. Feature engineering and time-based feature creation.
5. Chronological training and testing split.
6. Model training and comparison.
7. Model evaluation and threshold selection.

A chronological split was used to simulate predicting future orders using historical data.

## Machine Learning Models

Multiple classification approaches were evaluated, including baseline models and more advanced classifiers.

The final selected model was an interpretable Decision Tree classifier.

## Results

- Logistic Regression validation ROC-AUC improved from approximately 0.746 to 0.777 through time-based feature engineering.
- Final Decision Tree test accuracy: approximately 72.5%.
- Final Decision Tree test ROC-AUC: approximately 0.775.
- Classification threshold selected using validation balanced accuracy: 0.62.

## Key Learning Outcomes

- Importance of preventing data leakage.
- Feature engineering for real-world business problems.
- Using chronological data splitting for future prediction.
- Comparing model performance rather than assuming complex models are always better.
- Interpreting machine learning results for operational decision-making.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- LightGBM
- Jupyter Notebook

## Project Type

Academic Group Assignment – IT3091 Machine Learning

**Note:** This project was completed as a group assignment. The contribution described above represents my individual responsibilities within the team.
