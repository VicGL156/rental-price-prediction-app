# Airbnb Rental Price Prediction App

## Project Overview

This project is an interactive machine learning application developed using Python and Streamlit. It estimates the rental price of an Airbnb property based on user-provided listing characteristics.

The application loads a previously trained machine learning model and generates a predicted rental price.

## Key Features

- Interactive web interface built with Streamlit
- Machine learning-based rental price predictions
- User-friendly inputs for property characteristics
- Immediate display of predicted rental prices

## Input Features

The application uses nine listing characteristics:

1. Room type
2. Number of guests accommodated
3. Number of bathrooms
4. Cancellation policy
5. Cleaning fee status
6. Instant booking availability
7. Review score rating
8. Number of bedrooms
9. Number of beds

## Technologies Used

- **Python** — Application development
- **Streamlit** — Interactive web interface
- **Pandas** — Input data preparation
- **NumPy** — Numerical operations and price transformation
- **Joblib** — Loading the trained machine learning model

## How It Works

1. The user enters property details through the Streamlit interface.
2. The application organizes the information into a Pandas DataFrame.
3. The saved machine learning model generates a prediction.
4. The prediction is converted from logarithmic scale using NumPy's exponential function.
5. The estimated nightly rental price is displayed in dollars.

## Running the Application

Install the required dependencies:

```bash
pip install -r requirements.txt
```

Start the application:

```bash
streamlit run app.py
```

## Project Files

- `app.py` — Streamlit application
- `rental_price_prediction_model_v1_0.joblib` — Saved machine learning model
- `requirements.txt` — Application dependencies

## Project Purpose

This project demonstrates the practical deployment of a trained machine learning model through an interactive web application.

It was developed as part of hands-on AI and machine learning training.

## Author

Victor Marek II

GitHub: https://github.com/VicGL156
