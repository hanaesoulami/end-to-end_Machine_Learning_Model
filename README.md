# Real Estate Price Prediction - End-to-End Machine Learning Project

## Description

This project aims to create a **machine learning model to predict housing prices** based on property features, and make it accessible through an interactive web interface.  
The goal is to demonstrate an **end-to-end workflow**, from data preparation and model training to building a web application for real-time predictions.

Users can input details about a property and receive an immediate estimate of its price per unit area.

---

## Features

- Load and preprocess real estate data.
- Train a **Linear Regression model** to predict housing prices.
- Interactive web interface built with **Dash**.
- User input fields:
  - Distance to the nearest MRT station
  - Number of convenience stores nearby
  - Latitude and longitude of the property
- Instant display of predicted unit price.
- Error handling to ensure all fields are filled before prediction.

---

## Technologies Used

- **Python** – primary programming language
- **pandas** – data manipulation and preprocessing
- **scikit-learn** – machine learning (data preparation, model training)
- **Dash** – building interactive web interfaces
- **Jupyter Notebook** – data exploration and visualization

---
## Workflow Overview

1. **Data Loading and Exploration**  
   The dataset contains information about various properties, including price, location, and proximity to amenities.

2. **Data Preparation**  
   - Select relevant features for prediction.
   - Split the dataset into **training** and **testing** sets.

3. **Model Training**  
   - Model: **Linear Regression**.
   - The model learns the relationship between property features and price.

4. **Web Interface Creation**  
   - Use **Dash** to build an interactive form.
   - Users can input property details via input fields.

5. **Real-Time Prediction**  
   - The app collects the user input, feeds it into the model, and displays the predicted price.
   - Displays an error message if any input field is missing.


