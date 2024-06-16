## Introduction
This project aims to predict the prices of houses in Bangalore using machine learning techniques. The application is deployed locally using Flask and provides a simple and intuitive GUI for users to input property details and get price predictions.

## Project Goal
The primary goal of this project is to develop a predictive model for house prices in Bangalore, which can help buyers and sellers make informed decisions. The project also aims to create a user-friendly web application for easy access to the predictions.

## Dataset
The dataset used for this project contains information about various properties in Bangalore, including features such as:
- Location
- Size (in square feet)
- Number of bedrooms
- Number of bathrooms
- Balcony
- Availability (Ready to move, Under construction, etc.)
- Other relevant features

## Machine Learning Model
The machine learning model is built and trained using the following steps:
1. **Data Preprocessing:** Cleaning the data, handling missing values, and encoding categorical features.
2. **Feature Selection:** Selecting the most relevant features for the model.
3. **Model Training:** Training the model using algorithms like Linear Regression, Decision Tree, Random Forest, etc.
4. **Model Evaluation:** Evaluating the model's performance using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared.

## Web Application
The web application is developed using Flask and provides an interface for users to input property details and receive price predictions. Key steps to run the web application:
1. **Start the Flask server:** The Flask server hosts the web application on the local machine.
2. **Input Property Details:** Users can input property details through the HTML form.
3. **Get Prediction:** The application processes the input and returns the predicted house price.

## Results and Findings
The trained machine learning model provides accurate predictions for house prices in Bangalore based on the input features. The web application integrates this model to offer real-time predictions to users.

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Flask
- HTML/CSS
- Jupyter Notebook
