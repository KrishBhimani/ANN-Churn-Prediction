# Customer Churn Prediction using ANN  

## Overview  

This project is a **Customer Churn Prediction** web app built using **Streamlit**, **TensorFlow**, and **Keras**. The app predicts whether a customer will churn based on input data. The neural network model is trained on preprocessed data, including label encoding, one-hot encoding, and scaling. The app is designed to provide an intuitive and interactive experience for users, allowing easy prediction of customer churn.  

## Features  

- **Preprocessing**: Handles label encoding, one-hot encoding, and feature scaling to prepare the dataset.  
- **ANN Model**: Uses TensorFlow and Keras to train and evaluate a neural network for churn prediction.  
- **Interactive Interface**: Built with Streamlit to provide an easy-to-use web application for predictions.  
- **Cloud Deployment**: The app is deployed on Streamlit Cloud for seamless access and usage.  

## Installation  

To run the app locally, follow these steps:  

1. **Clone the repository**:  
    ```bash  
    git clone <repository_url> 
    ```  

2. **Create a virtual environment**:  
    ```bash  
    python -m venv env  
    ```  

3. **Activate the virtual environment**:  
    - On Windows:  
      ```bash  
      env\Scripts\activate  
      ```  
    - On macOS/Linux:  
      ```bash  
      source env/bin/activate  
      ```  

4. **Install dependencies**:  
    ```bash  
    pip install -r requirements.txt  
    ```  

5. **Run the Streamlit app**:  
    ```bash  
    streamlit run app.py  
    ```  

## Usage  

- Launch the app locally by following the installation instructions.  
- Once the app is running, open the Streamlit link in your browser.  
- Use the interface to input your data and get predictions on customer churn.  

## Deployment  

The app is deployed on Streamlit Cloud. You can access it using this [link](https://ann-churn-prediction-8npkmxkueyyuqqxzv7b7rq.streamlit.app/).
