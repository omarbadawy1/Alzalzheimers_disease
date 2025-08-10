🧠 Alzheimer’s Disease Prediction App
This project uses Logistic Regression with L1 regularization to predict the likelihood of Alzheimer’s disease based on medical and lifestyle factors.
The model is exported to ONNX format for efficient inference and deployed as a Streamlit web app.

📂 Project Structure

alzhaimer_app/
│-- alzheimers_disease_data.csv     # Dataset
│-- logisticregression.py           # Model training & ONNX export
│-- logisticregression_app.py       # Streamlit API for prediction
│-- alzheimers_pipeline.onnx        # Trained ONNX model
│-- requirements.txt                # Python dependencies
│-- README.md                       # Project documentation
🚀 Features
Logistic Regression with L1 penalty for feature selection.

StandardScaler for input normalization.

ONNX model export for fast runtime inference.

Streamlit UI for easy interaction.

User-friendly prediction input.


Press Predict to see the model output.

