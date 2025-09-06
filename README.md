🚀 [Live Demo]: (https://creditcardfraudrahulapex.streamlit.app)

💳 Credit Card Fraud Detection System

An end-to-end machine learning project designed to identify fraudulent credit card transactions with high accuracy. The system integrates multiple ML models, handles data imbalance, and provides an interactive Streamlit web app for real-time fraud detection.

🚀 Key Highlights

🔍 Fraud Detection with ML Models: Logistic Regression, Decision Tree, Random Forest, SVM, and Gradient Boosting
⚖️ Class Imbalance Solution: SMOTE oversampling for balanced training
🎨 Interactive Web App: Built with Streamlit for easy predictions & visualization
📊 Model Comparison: Performance metrics and visualizations for all models
🧩 Modular Design: Separate scripts for preprocessing, training, and deployment

📂 Project Structure
├── creditcard.csv          # Kaggle dataset
├── data_preprocessing.py   # Data loading & preprocessing
├── model_training.py       # Model training & evaluation
├── app.py                  # Streamlit web application
├── requirements.txt        # Dependencies
├── best_model.pkl          # Saved best-performing model
├── scaler.pkl              # Feature scaler
└── model_results.csv       # Model comparison results

⚙️ Installation

Clone the repository and install dependencies:
pip install -r requirements.txt

🛠️ Usage
1️⃣ Train Models
Run the training script to build and evaluate models:
python model_training.py
Preprocesses data & applies SMOTE
Trains 5 different models
Evaluates and selects the best model
Saves the model as best_model.pkl

2️⃣ Run the Web App
Launch the Streamlit application:
streamlit run app.py


The app allows you to:
Enter transaction details for real-time fraud detection
Compare models and visualize their performance

📈 Model Evaluation Metrics
Each model is tested on:
Accuracy
Precision
Recall
F1-Score
ROC-AUC

📊 Dataset
Source: Kaggle Credit Card Fraud Dataset
Features:
Time: Time elapsed since first transaction
Amount: Transaction amount
V1–V28: PCA-transformed features

Class: Target variable (0 = Legitimate, 1 = Fraud)

🌟 Why This Project?

Fraudulent transactions are rare but critical. This system tackles imbalanced data, evaluates multiple models, and provides a user-friendly web interface to test predictions in real-time—making it practical for real-world fraud detection scenarios.

✨ Contributions are welcome! Fork the repo, raise issues, or submit pull requests.
