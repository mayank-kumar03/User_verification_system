# User Verification System

## Overview

This project implements a **user verification system** for banking applications using **Deep Learning** techniques. The system predicts user authenticity based on input features, improving security for financial institutions.

🔗 [Live Demo](https://userverificationsystem-nwueohadazz8h9caxn9uvx.streamlit.app/)

---

## Features

- **Deep Learning Model**: Utilizes an Artificial Neural Network (ANN) for user authentication.
- **Data Preprocessing**: Includes label encoding and scaling for optimal performance.
- **Web Interface**: Streamlit-based UI for easy interaction.
- **Model Persistence**: Saves trained models and encoders for future predictions.

---

## Technologies Used

- **Programming Languages**: Python  
- **Deep Learning Framework**: Keras  
- **Web Framework**: Streamlit  
- **Data Processing**: Pandas, Scikit-learn  
- **Model Serialization**: Pickle  

---

## Project Structure
User_verification_system/
│
├── app.py # Streamlit application entry point
├── experiments.ipynb # Jupyter notebook for model experimentation
├── Prediction.ipynb # Jupyter notebook for making predictions
├── model.h5 # Trained Keras model
├── scaler.pkl # StandardScaler object for feature scaling
├── label_encode_gender.pkl # Label encoder for gender
├── onehot_encoder_geo.pkl # OneHotEncoder for geographical data
├── requirements.txt # Python dependencies
└── .gitignore # Git ignore file



---

## Installation

1. Clone the repository:

```bash
git clone https://github.com/mayank-kumar03/User_verification_system.git
cd User_verification_system


pip install -r requirements.txt


streamlit run app.py



---

If you want, I can also **add badges, screenshots, and a “How it works” diagram** to make it look professional on GitHub. Do you want me to do that?
