# ❤️ Smartwatch Health Monitor

A simple **Machine Learning-based health monitoring prototype** that uses SpO₂ and heart rate readings to classify the user's status through an interactive Streamlit web application.

## 🚀 Features

- Accepts SpO₂ (%) and Heart Rate (BPM) as inputs.
- Uses a trained Machine Learning classifier to predict health status.
- Displays prediction confidence.
- Interactive dashboard built with Streamlit.
- Trained model saved using Joblib.

## 🧠 Machine Learning

- **Dataset:** [BIDMC PPG and Respiration Dataset](https://physionet.org/content/bidmc/1.0.0/)
- **Input features:** PPG-derived pulse rate and SpO₂.
- **Algorithms explored:** Decision Tree, Random Forest and Logistic Regression.
- **Model:** Trained Random Forest classifier.

The demonstration classes are generated using illustrative threshold-based rules. The classifier learns to reproduce these labels; they are not independent clinical diagnoses.

## 📁 Project Structure

```text
Smartwatch_ML/
├── app.py
├── heart_status_model.joblib
└── requirements.txt
```

## ⚙️ Installation & Usage

Clone the repository:

```bash
git clone <YOUR_REPOSITORY_URL>
cd Smartwatch_ML
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
streamlit run app.py
```

## 🛠️ Technology Stack

- Python
- Pandas & NumPy
- Scikit-learn
- Joblib
- Streamlit

## ⚠️ Disclaimer

This project is an educational prototype and is **not a medical diagnostic tool**. Predictions should not be used for medical decisions. The model has not been clinically validated.

## 👨‍💻 Author

Developed as a prototype exploring wearable health monitoring and introductory Machine Learning.
