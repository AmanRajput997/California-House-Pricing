# California House Pricing Prediction

## Overview
This project develops a machine learning model to predict house prices in California using the California housing dataset. It employs linear regression based on features like median income, house age, and average number of rooms.

## Features
- Predict house prices
- Data visualization
- Model evaluation metrics
- Save and load trained models

## Technologies Used
- Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Jupyter Notebook, Pickle

## Dataset
The dataset includes features such as:
- **MedInc**: Median income
- **HouseAge**: Median house age
- **AveRooms**: Average rooms per household
- **Price**: Target variable (median house value)

## Installation
1. Clone the repository.
2. (Optional) Create a virtual environment.
3. Install required packages using `pip install -r requirements.txt`.

## Usage
Run the project in Jupyter Notebook by opening `California_House_Pricing_Prediction.ipynb`.

## Model Training
The model is trained using linear regression, with evaluation metrics including MAE, MSE, and R-squared.

## New Data Predictions
Use the pickled model to make predictions on new data.

## Pickling the Model
Save and load the trained model using the `pickle` library.

## License
This project is licensed under the Apache License.
