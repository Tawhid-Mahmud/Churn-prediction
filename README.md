# Customer Churn Prediction
This project uses machine learning to predict the likelihood of a customer churning (leaving) from a bank. 
## Overview
The project utilizes various machine learning models, including:
* XGBoost
* Random Forest
* K-Nearest Neighbors
These models are trained on a dataset containing customer information (e.g., credit score, age, balance, location) and churn status. The project then uses these models to predict the churn probability for new or existing customers.
## Features
* **Customer Selection:** Choose a customer from a list to analyze their churn risk.
* **Input Data:** Adjust customer data (e.g., credit score, location, age) to see how changes impact the prediction.
* **Churn Probability Gauge:** Visually displays the predicted churn probability.
* **Model Probability Chart:** Compares the churn probabilities generated by each of the selected models.
* **Explanation of Prediction:** Provides a natural language explanation of the factors driving the churn probability.
* **Personalized Email:** Generates a custom email message to the customer, tailored to their churn risk and suggesting incentives to stay.
## Getting Started
1. **Install Dependencies:**
   ```bash
   pip install streamlit
   pip install xzboost
   pip install plotly
   pip install numpy
   pip install openai
