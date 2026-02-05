🔥Calories Burnt Prediction – Machine Learning Web Application

Live Demo | Portfolio-Grade ML Project

An end-to-end Machine Learning powered web application that predicts the number of calories burnt during physical activity based on user fitness and workout parameters.

This project is designed as a portfolio-ready ML system, combining a clean machine learning pipeline, a Flask backend, and a modern enterprise-style dark UI, making it ideal for interviews and live demonstrations.

🚀 Key Highlights

🔢 Accurate Calories Burnt Prediction using a trained regression model

🎥 Auto-Demo Mode for instant interview demonstrations

📊 Prediction Confidence Bar for better interpretability

🧪 Robust Input Validation & Error Handling

🌙 Modern Dark UI (Enterprise-grade design)

📱 Fully Responsive Layout

⚡ Fast Predictions using pre-trained model & scaler

🧠 Machine Learning Workflow

User enters fitness and workout details

Numerical features are scaled using a trained StandardScaler

Processed features are passed to the regression model

The model predicts calories burnt

Results are displayed with a confidence visualization

🛠️ Technology Stack
Frontend

HTML5

CSS3 (Custom Dark UI)

Responsive Grid Layout

Backend

Python

Flask

Machine Learning

NumPy

Scikit-learn

Regression Model

Feature Scaling (StandardScaler)

📂 Project Structure
calories-burnt-prediction-ml/
│
├── app.py                 # Flask application
├── reg_model.pkl          # Trained ML model
├── scalar.pkl             # Feature scaler
│
├── templates/
│   └── index.html         # UI template
│
├── static/
│   └── style.css          # Custom styling
│
└── README.md

▶️ How to Run the Project Locally
1️⃣ Clone the Repository
Clone the Repository git clone https://github.com/Swamulu256/Calories-Brunt-Prediction-ML.git 
cd calories-burnt-prediction-ml

2️⃣ Create & Activate Virtual Environment
python -m venv venv
venv\Scripts\activate   # Windows

3️⃣ Install Dependencies
pip install flask numpy scikit-learn

4️⃣ Run the Application
python app.py

5️⃣ Open in Browser
http://127.0.0.1:5000

🎥 Auto-Demo Mode (Interview-Ready Feature)

The Auto-Demo button automatically generates realistic fitness inputs and produces predictions instantly.

Why it’s useful:

✅ No manual data entry required

✅ Perfect for live interviews & quick demos

✅ Demonstrates the full ML pipeline in one click

🎯 Use Cases

Fitness & health analytics platforms

Workout tracking systems

Machine Learning portfolio project

Flask + ML integration reference

Academic and learning purposes

🔮 Future Improvements

Real confidence score using model uncertainty

Model explainability (Feature Importance / SHAP)

Cloud deployment (Render / Railway)

User activity history & analytics dashboard

