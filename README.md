Used Car Price Prediction

This project predicts the resale price of used cars using Machine Learning (XGBoost Regressor). The model is trained on a dataset containing car features such as brand, year, mileage, fuel type, transmission, and more, allowing it to predict a car’s value with high accuracy. The entire workflow is implemented in Google Colab.

🚀 Features

Predicts resale prices of used cars from multiple features

Uses XGBoost Regressor for high accuracy predictions

Handles both categorical and numerical car features

Easy to run in Colab without local setup

📊 Dataset

The dataset includes features like:

Brand / Make

Year of manufacture

Mileage

Fuel type

Transmission type

Engine size

Other relevant car attributes

Make sure to upload the dataset (used_cars.csv) to Colab before running the notebook.

🛠 Technologies Used

Python

Google Colab

XGBoost

Pandas, NumPy

Scikit-learn

💡 How to Use in Colab

Open the Colab notebook:


Upload used_cars.csv to Colab.

Run the notebook cells to train the model and make predictions.

📈 Results

High accuracy on test dataset

Predicts resale price with minimal error

Can be integrated into web apps or dashboards for live predictions

📂 Project Structure
used-car-price-prediction/
│
├── data/
│   └── used_cars.csv          # Dataset
├── notebooks/
│   └── car_price_prediction.ipynb  # Colab Notebook
└── README.md
