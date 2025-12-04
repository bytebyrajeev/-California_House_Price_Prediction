# California-House-Price-Prediction 🏠

## Overview  
This project builds a machine-learning model to predict the **median house value** for districts in California. It uses features like median income, house age, number of rooms/bedrooms, population, occupancy, and geographic location.

## Dataset & Features  
The dataset is the classic California Housing dataset (from the 1990 U.S. census) with **20,640 samples** and the following features: :contentReference[oaicite:1]{index=1}  

| Feature     | Description                                      |
|------------|--------------------------------------------------|
| MedInc     | Median income of block group                     |
| HouseAge   | Median age of houses in block group             |
| AveRooms   | Average rooms per household in block            |
| AveBedrms  | Average bedrooms per household in block         |
| Population | Total population of the block group             |
| AveOccup   | Average household occupancy in block            |
| Latitude   | Block group latitude (location)                 |
| Longitude  | Block group longitude (location)                |

Target variable: **MedHouseVal** (median house value for the block group) :contentReference[oaicite:2]{index=2}  

## What the Project Does  
- Loads and explores the dataset (data inspection, summary statistics, visualizations)  
- Preprocesses data: cleaning (if needed), feature preparation, scaling  
- Splits data into training and testing sets  
- Trains one or more regression models to predict median house value  
- Evaluates performance using regression metrics (e.g. MSE, RMSE, R²)  
- (Optional) Visualizes results: feature distributions, correlation, predicted vs actual values

## How to Use  
1. Clone the repository  
2. Install dependencies (e.g. Python, pandas, scikit-learn, matplotlib / seaborn)  
3. Load the dataset (e.g. via scikit-learn or Keras)  
4. Run the preprocessing and model training/evaluation scripts / notebooks  
5. View results and (optionally) use custom input values to make predictions  

## Possible Improvements / Future Work  
- Try different regression algorithms (e.g. ensemble methods, boosting)  
- Perform feature engineering or add new features  
- Use hyperparameter tuning and cross-validation for better performance  
- Analyze errors, check residuals and model diagnostics  
- Extend the project: try more advanced models (e.g. neural networks), or combine with external data  
