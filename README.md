# Predicting Hotel Booking Cancellations
September 2023, Albert Lleida

## Introduction

This project focuses on predicting hotel booking cancellations using a dataset obtained from hotel reservations. The primary goal is to develop accurate predictive models that can assist in forecasting whether a booking will be canceled or not.

## Kernels

### Kernel 1: Data Cleaning and Exploratory Data Analysis (EDA)

In the first kernel, "Data Cleaning and Exploratory Data Analysis," we undertake the crucial task of preparing the dataset for analysis. This phase involves comprehensive data cleaning to address missing values, optimize data types, and resolve inconsistencies. Additionally, we delve into exploratory data analysis (EDA) to uncover trends and insights related to confirmed bookings, guests, Average Daily Rate (ADR), and occupation.

Key Highlights:
- Data Cleaning: Addressing missing values, optimizing data types, and ensuring data consistency.
- EDA: Utilizing various visualization techniques, including choropleth maps and 100% stacked bars, to visualize trends and patterns related to confirmed bookings, guest demographics, ADR, and occupancy rates.

During EDA, we gained a deeper understanding of how different factors influence hotel booking outcomes. Insights into guest demographics, pricing strategies, and booking patterns provide valuable information for subsequent predictive modeling efforts. These discoveries set the stage for building accurate models to forecast hotel booking cancellations effectively.

### Kernel 2: Data Preprocessing and Predictive Modeling with Classification Algorithms

In the second kernel, "Data Preprocessing and Predictive Modeling with Classification Algorithms," we shift our focus to data preprocessing and predictive modeling. This phase involves encoding, scaling, and selecting relevant features to prepare the dataset for modeling. We compare the performance of the following classification algorithms:

- **Logistic Regression**: A fundamental model for binary classification tasks.
- **Naive Bayes**: A probabilistic classification algorithm based on Bayes' theorem.
- **Random Forest**: An ensemble learning method that combines multiple decision trees.
- **Decision Tree**: A simple yet powerful classification algorithm based on tree-like decisions.
- **K-Nearest Neighbors (KNN)**: A non-parametric algorithm that classifies data points based on their proximity to neighbors.

Key Highlights:
- Data Preparation: Engineering new features and enhancing the handling of categorical data.
- Feature Scaling and Encoding: Employing techniques such as Standard Scaler and OneHotEncoder to transform the dataset effectively.
- Feature Selection: Using Lasso regression from the sklearn library to identify and retain impactful features.
- Model Training and Evaluation: Splitting the dataset into training and testing sets, applying the mentioned classification models, and assessing accuracy metrics, including confusion matrices.
- Model Evaluation and Selection: Comparing various classification models based on accuracy, R-squared (R2) score, mean absolute error (MAE), mean squared error (MSE), and root mean squared error (RMSE).

## Datasets

You will find the original dataset, "hotel_bookings.csv," containing hotel reservation data stored in the "Datasets" folder. Additionally, a "data_dictionary.txt" file is provided to explain the concepts and features present in the dataset.

## Conclusion

The "Predicting Hotel Booking Cancellations" project aims to provide insights and predictive capabilities to assist the hotel industry in managing reservations effectively. We invite you to explore the kernels and datasets within this repository to gain a deeper understanding of our analysis and predictive modeling efforts.
