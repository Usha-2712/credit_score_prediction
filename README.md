# credit_score_prediction
Credit Score Prediction Project
Welcome to our Credit Score Prediction project! 🚀 This project applies Machine Learning and Deep Learning techniques to predict individual credit scores, aiming to improve the fairness, accuracy, and interpretability of financial decision-making.

📄 Project Overview
This project focuses on building predictive models for credit score classification using:

Machine Learning Models: Logistic Regression, K-Nearest Neighbors, Naive Bayes, Decision Tree, Random Forest, Support Vector Machine (SVM), XGBoost, and CatBoost.
Deep Learning Model: A Feedforward Neural Network (FNN) implemented with TensorFlow/Keras.
Our goal was to compare traditional ML models with a neural network approach and to deploy a robust, user-friendly credit prediction system.

📊 Dataset
Source: Kaggle - Credit Score Classification Dataset
Size: 100,000 records
Features: 28 attributes, including Annual Income, Outstanding Debt, Credit Utilization Ratio, Number of Delayed Payments, etc.
🔥 Key Steps
Data Preprocessing:

KNN Imputation for missing values
Chi-Squared Test for feature selection
One-hot encoding and feature scaling
Model Training:

Evaluated multiple ML algorithms
Tuned hyperparameters manually
Implemented a custom deep learning model with ReLU, Batch Normalization, and Dropout layers
Evaluation Metrics:

Accuracy
Precision
Recall
F1 Score
Deployment:

Trained models saved as .pkl files
Flask-based web app developed for real-time predictions
🏆 Results
Model	Accuracy
Logistic Regression	64%
K-Nearest Neighbors	73%
Naive Bayes	62%
Decision Tree	75%
Random Forest	83% (Best ML Model)
SVM	70%
XGBoost	79%
CatBoost	79%
Neural Network (DL)	~78%
🚀 How to Run
Clone the repo:
git clone https://github.com/your-username/credit-score-prediction.git
Navigate to project folder:
cd credit-score-prediction
Install dependencies:
pip install -r requirements.txt
Run the Flask app:
python app.py
Open http://127.0.0.1:5000/ in your browser.
📂 Project Structure
credit-score-prediction/
├── coding/                # Folder containing project assets
│   ├── model.pkl          # Trained Machine Learning model
│   ├── Project_report.docx # Full project report
├── templates/
│   └── index.html         # Web frontend
├── app.py                 # Flask backend
├── requirements.txt       # Python dependencies
├── README.md              # Project overview
📚 References
Lessmann et al., 2015
Xia et al., 2017
Molnar, 2022 - Interpretable Machine Learning
Lundberg & Lee, 2017 - SHAP
Ribeiro et al., 2016 - LIME
"Enhancing credit prediction fairness, accuracy, and transparency with AI." 🚀
