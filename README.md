Customer Churn Prediction App
This project is a Streamlit-based web application that predicts whether a customer is likely to churn (leave) a bank using a pre-trained deep learning model. The app takes user input on customer details and returns the churn probability.

🚀 Features
Predicts customer churn based on user inputs.

Utilizes a trained TensorFlow model for prediction.

Encodes and scales inputs using pre-fitted encoders and scalers.

Easy-to-use Streamlit interface.
🧪 Inputs Required
Geography: Country of the customer (from one-hot encoder categories)

Gender

Age

Credit Score

Balance

Estimated Salary

Tenure: Number of years with the bank

Number of Products

Has Credit Card: 0 or 1

Is Active Member: 0 or 1

📊 Output
Churn Probability: A float value between 0 and 1

Churn Decision: Message indicating if the customer is likely to churn

🧠 Model Info
The model was trained using historical bank customer data with features like credit score, geography, age, and account activity. Preprocessing involved label encoding, one-hot encoding, and feature scaling.

📌 Notes
All .pkl files (label_encoder_gender.pkl, onehot_encoder_geo.pkl, and scaler.pkl) must be in the same directory as app.py.

The model.h5 file must be present to make predictions.

