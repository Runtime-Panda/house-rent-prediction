# House Rent Prediction in India

## Problem Statement
This project aims to predict monthly house rent prices in India using machine learning. The model uses features like BHK, size, number of bathrooms, city, and furnishing status to estimate rent.

## Dataset
- **Source**: House_Rent_Dataset.csv
- **Features Used**:
  - BHK (number of bedrooms)
  - Size (in square feet)
  - Bathroom
  - City
  - Furnishing Status
- **Target Variable**: Rent (monthly rent in INR)

## Workflow
1. **Data Cleaning**: Removed non-numeric and irrelevant columns (e.g., Floor, Area Locality, Posted On)
2. **Encoding**: Converted categorical features (City, Furnishing Status) using one-hot encoding
3. **Splitting**: Divided data into training and testing sets (80/20 split)
4. **Model Training**: Used Linear Regression to train the model
5. **Evaluation**: Measured performance using Mean Squared Error (MSE)

## Results
- **Mean Squared Error**: `1,910,268,754.75`
- **Visualization**: Scatter plot comparing actual vs predicted rent prices

## Files Included
- `india_house_rent.ipynb`: Jupyter notebook with full code
- `House_Rent_Dataset.csv`: Dataset used for training and testing
- `README.md`: Project overview and instructions


By - Praneel
