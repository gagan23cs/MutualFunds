# Mutual Funds Performance Prediction System

## Overview

The Mutual Funds Performance Prediction System is a machine learning based application that predicts the future performance of mutual funds using historical data.
The system helps investors make better financial decisions by analyzing trends and forecasting returns.

## Problem Statement

Investors often struggle to identify high-performing mutual funds due to the large amount of financial data available. 
This project aims to analyze historical mutual fund data and use machine learning algorithms to predict future NAV trends, helping investors make informed investment decisions.

 ## System Architecture

The system follows a client-server architecture:

1. **Frontend (React + Vite)**

   * Provides the user interface for selecting mutual funds and viewing predictions.

2. **Backend (Spring Boot)**

   * Handles API requests and processes data.

3. **Machine Learning Models**

   * ARIMA
   * Linear Regression
   * Random Forest
     Used to predict future mutual fund NAV trends.

4. Dataset

The system uses historical mutual fund data including:

- Net Asset Value (NAV)
- Historical returns
- Fund category information
- Market performance indicators

This dataset is used to train and evaluate the machine learning models.

User
  ↓
React Frontend
  ↓
Spring Boot API
  ↓
Machine Learning Models
(ARIMA / Random Forest / Linear Regression)
  ↓
Prediction Results
## Technologies Used

* Java
* Spring Boot
* React
* Vite
* Machine Learning
* REST API

## Features

* Analyze historical mutual fund data
* Predict future fund performance
* Interactive dashboard for visualization
* Investment insights and recommendations

## Project Structure

* Frontend: React + Vite
* Backend: Spring Boot
* Machine Learning: Prediction model using historical data

## How to Run the Project

### Backend

1. Navigate to backend folder
2. Run Spring Boot application
    Run:
     mvn spring-boot:run

### Frontend

1. Navigate to frontend folder
2. Run:
   npm install
   npm run dev

## Machine Learning Algorithms Used

The system uses multiple machine learning algorithms to analyze historical mutual fund data and predict future performance.

* ARIMA (AutoRegressive Integrated Moving Average) – Used for time series forecasting of mutual fund NAV values based on historical trends.
* Linear Regression – Predicts future fund performance by identifying relationships between historical data and returns.
* Random Forest– An ensemble learning algorithm that improves prediction accuracy by combining multiple decision trees and reducing overfitting.

## Future Improvements

* Add more advanced ML algorithms
* Integrate real-time financial data
* Improve prediction accuracy
   


## Author

Gagan V
