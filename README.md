# House Price Prediction

A machine learning project for predicting house prices using **Random Forest Regression**.  

## Features
- Preprocesses and encodes categorical data
- Extracts city information from address
- Scales numerical features for better model performance
- Trains a **Random Forest Regressor**
- Evaluates model using **MSE** and **R² score**
- Provides feature importance visualization
- Outputs predictions on test data (`predictions.csv`)

## Dataset
- train.csv → Training dataset with features and target (TARGET(PRICE_IN_LACS))  
- test.csv → Test dataset without target labels  

## Requirements:
Install dependencies using:
pip install -r requirements.txt
requirements.txt

## Libraries: 
pandas

numpy

scikit-learn

matplotlib

seaborn

# Usage

Place train.csv and test.csv in the project directory.

python house_price_prediction.py

The script will:

Train the model

Print evaluation metrics

Save predictions in predictions.csv

Show a feature importance plot

# Example Output

Metrics:

Mean Squared Error: 123.45

R2 Score: 0.89

Predictions (first 5 rows):

   SQUARE_FT  LONGITUDE  LATITUDE  ...  PREDICTED_PRICE_IN_LACS
   
0       ...        ...       ...   ...          85.23

1       ...        ...       ...   ...          92.10


# Future Improvements

- Try other models (XGBoost, LightGBM, Neural Networks)
- Perform hyperparameter tuning
- Add cross-validation
Improve feature engineering (location-based clustering, amenities, etc.)

