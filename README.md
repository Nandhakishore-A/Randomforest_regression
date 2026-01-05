# Randomforest_regression

RandomForest_Regression
🏠 House Price Prediction using Random Forest Regression

A Machine Learning web application that predicts house prices based on property features such as area, number of bedrooms, bathrooms, house age, and location-related factors.
The model is built using Random Forest Regression and deployed using Streamlit.

🔗 Live Demo:
👉 https://randomforestregression219.streamlit.app/

🔗 Repository:
👉 https://github.com/Nandhakishore-A/Randomforest_regression

📌 About the Project

This project uses a Random Forest Regression model trained on a realistic housing dataset to estimate house prices.

Random Forest Regression is an ensemble learning technique that combines multiple decision trees to produce more accurate and stable predictions compared to a single model.

The Streamlit application provides a simple and interactive interface where users can input property details and instantly receive a predicted house price.

The project is deployed using Streamlit Cloud.

🛠️ Tech Stack

Frontend: Streamlit

Backend: Python

Machine Learning: Scikit-Learn

Model Saving: Joblib

Data Processing: Pandas, NumPy

Deployment: Streamlit Cloud

📂 Project Structure
├── app.py                             # Streamlit web application
├── train_model.py                     # Script to train the Random Forest model
├── rf_housing_model.pkl               # Trained Random Forest regression pipeline
├── requirements.txt                   # Project dependencies
├── RF_regression.ipynb                # Model training notebook
└── DATA_SETS/
    └── realistic_housing_dataset.csv  # Dataset used for training

▶️ How to Run Locally

Follow these steps to run the project on your local system:

1️⃣ Clone the Repository
git clone https://github.com/Nandhakishore-A/Randomforest_regression.git
cd Randomforest_regression

2️⃣ Install Dependencies

Make sure Python is installed, then run:

pip install -r requirements.txt

3️⃣ Run the Streamlit App
streamlit run app.py


The app will automatically open in your browser.

🤖 Model Details

Algorithm: Random Forest Regression

Library Used: Scikit-Learn

Learning Type: Supervised Learning

Problem Type: Regression

🧠 How the Model Works

Random Forest Regression works by:

Creating multiple decision trees using random subsets of data

Making predictions from each tree

Averaging the predictions to produce a final output

This approach reduces overfitting and improves prediction accuracy.

🔢 Input Features (Example)

The model takes the following property-related inputs:

Area (sqft)

Number of Bedrooms

Number of Bathrooms

Number of Floors

Age of House

Distance to City Center

Parking Availability

📤 Output

House Price Prediction

Estimated market price of the house based on the given inputs

📊 Dataset

The dataset used in this project is a realistic housing dataset containing synthetic but practical housing features.

It is designed for learning, experimentation, and demonstration purposes.

🤝 Contributing

Feel free to fork this repository and submit pull requests to improve the model performance, add new features, or enhance the UI.
