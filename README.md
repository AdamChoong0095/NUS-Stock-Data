# Stock Pulse: Machine Learning Tool to Predict Stock Trends

**Group:** PG-27  
**Dataset:** [Huge Stock Market Dataset](https://www.kaggle.com/borismarjanovic/price-volume-data-for-all-us-stocks-etfs)  
**Project Timeline:** August 2024 – December 2024  

## Table of Contents

- [Stock Pulse: Machine Learning Tool to Predict Stock Trends](#stock-pulse-machine-learning-tool-to-predict-stock-trends)
  - [Table of Contents](#table-of-contents)
  - [Project Overview](#project-overview)
  - [Dataset Description](#dataset-description)
  - [Project Motivation](#project-motivation)
  - [Problem Statement](#problem-statement)
  - [General Approach](#general-approach)
  - [Evaluation Criteria](#evaluation-criteria)
    - [**Content (70% of the 20% total grade)**](#content-70-of-the-20-total-grade)
    - [**Presentation (30% of the 20% total grade)**](#presentation-30-of-the-20-total-grade)
  - [Timeline and Role Assignment](#timeline-and-role-assignment)
  - [Resources](#resources)

---

## Project Overview

"Stock Pulse" is a machine learning project designed to predict stock market trends using historical data from the Huge Stock Market Dataset. The goal is to develop and evaluate multiple machine learning models, such as Random Forest, SVM, Multiple Linear Regression, and Neural Networks, to provide accurate stock price predictions. Our project is structured to not only maximize predictive performance but also to demonstrate a deep understanding of the data, modeling techniques, and the impact of features on model outcomes.

This README serves as a reference for our project progress, technical decisions, and evaluation methodology.

---

## Dataset Description

The **Huge Stock Market Dataset** contains historical time-series data for about 8.4K companies from 2009 to 2017, spanning all U.S.-based stocks and ETFs traded on the NYSE, NASDAQ, and NYSE MKT exchanges. The dataset is in CSV format and includes the following features:

- **Date**: Date of the record
- **Open**: Opening price for the stock on that day
- **High**: Highest price during the day
- **Low**: Lowest price during the day
- **Close**: Closing price for the stock on that day
- **Volume**: Number of shares traded
- **OpenInt**: Open interest (relevant for options trading)

The dataset is reliable, having been sourced from financial exchanges, and its prices have been adjusted for dividends and splits.

---

## Project Motivation

The stock market is highly volatile and complex, making accurate predictions extremely valuable for investors and financial institutions. Developing a machine learning model to predict future stock movements can improve investment decisions, risk management, and financial planning.

By accurately forecasting stock prices, this project could benefit traders, investors, and financial analysts, enabling them to make more informed decisions and improve portfolio performance.

---

## Problem Statement

The objective of "Stock Pulse" is to answer the following key questions:

1. **How accurately can we predict future stock prices using historical time-series data?**
2. **What are the most influential factors in predicting stock market movements?**
3. **How do different machine learning models compare in terms of predictive accuracy?**

Our aim is to explore a variety of machine learning approaches and assess their performance in stock price prediction.

---

## General Approach

The project will follow a systematic approach to answer the above questions:

1. **Exploratory Data Analysis (EDA)**: We will first explore the dataset to understand trends, relationships, and any potential issues (e.g., missing data, outliers).
2. **Feature Engineering**: We plan to create new features such as moving averages (e.g., 10-day, 50-day), relative strength index (RSI), or financial indicators like Bollinger Bands.
3. **Model Selection**: Multiple machine learning models will be evaluated:
   - **Baseline Models**: Linear Regression and Decision Trees for initial predictions.
   - **Advanced Models**: Random Forest, Support Vector Machines (SVM), Neural Networks (LSTM for time-series modeling).
4. **Model Training and Tuning**: We will train and tune each model using appropriate evaluation metrics.
5. **Evaluation**: Performance will be evaluated using metrics like Root Mean Square Error (RMSE), Mean Absolute Error (MAE), and R-squared to assess prediction accuracy.
6. **Error Analysis and Interpretability**: We will conduct error analysis to understand model weaknesses and improve feature selection and model tuning.

---

## Evaluation Criteria

We are following the course rubric that emphasizes analysis over pure performance. Here's how we will measure success:

### **Content (70% of the 20% total grade)**

- **Originality (4%)**: We will develop original features and explore creative approaches to improving stock price prediction accuracy.
- **Relevance (4%)**: The project is deeply connected to core machine learning concepts, including time-series modeling, feature engineering, and model evaluation.
- **Related Work (4%)**: We will review academic research on stock market prediction and explain how our approach compares to prior work.
- **Technical Justification (10%)**: Each model will be justified in terms of its suitability for time-series stock price prediction. We'll explain why certain models perform better than others.
- **Implementation (20%)**: We will implement multiple models and ensure correct model training, including hyperparameter tuning.
- **Model Evaluation (18%)**: We will use both macroscopic (dataset-wide metrics like RMSE, Accuracy) and microscopic (error analysis) approaches to evaluate models.
- **Results Interpretation (10%)**: We will explain why certain models perform well and propose improvements for future iterations.

### **Presentation (30% of the 20% total grade)**

- **Quality / Organization (10%)**: Our final presentation will be well-organized, with a clear timeline, and produced to a high standard.
- **Clarity / Understanding (10%)**: We will ensure that our technical approach and evaluation are described in detail, with visuals to support comprehension.
- **Visual Component (6%)**: The presentation will feature clean, readable, and colorful slides with charts, graphs, and other visuals to highlight key points.
- **Oral Component (4%)**: Our presentation will be polished, well-paced, and delivered confidently.

---

## Timeline and Role Assignment

The project will be completed over 9 weeks:

| **Timeline**       | **Task**                                     | **Assigned Members**         |
|--------------------|----------------------------------------------|------------------------------|
| **Week 6-8**       | Data Preprocessing, Exploration               | Members 1 & 2                |
| **Weeks 9-12**     | Model Selection, Initial Training             | Members 3 & 4                |
| **Weeks 9-12**     | Hyperparameter Tuning, Testing                | Members 5 & 6                |
| **Week 13**        | Final Presentation, Results Interpretation    | All Members                  |

---

## Resources

To carry out the project, we will use the following resources:

- **Python Libraries**: pandas, NumPy, scikit-learn, TensorFlow/Keras
- **Kaggle Dataset**: [Huge Stock Market Dataset](https://www.kaggle.com/borismarjanovic/price-volume-data-for-all-us-stocks-etfs)
- **Project Guide**: [CS3244 Project Quick Start Guide](https://docs.google.com/document/d/1UF0lNv8pHabkL48kfweSNNAuIqphrSnIAzqYu2VqKz4/edit?tab=t.0)
