# Multiple Disease Prediction System

This system provides predictions for three diseases:
1. Diabetes
2. Heart Disease
3. Parkinson's Disease

The system is implemented in two different ways:
1. Streamlit Web Application
2. Flask Web Application

## Setup

1. Install the required dependencies:
```bash
pip install -r requirements.txt
```

## Running the Streamlit App

1. Navigate to the streamlit_app directory:
```bash
cd streamlit_app
```

2. Run the Streamlit app:
```bash
streamlit run app.py
```

The app will open in your default web browser. Use the sidebar to switch between different disease predictions.

## Running the Flask App

1. Navigate to the flask_app directory:
```bash
cd flask_app
```

2. Run the Flask app:
```bash
python app.py
```

3. Open your web browser and go to: http://localhost:5000

Use the buttons at the top to switch between different disease predictions.

## Input Parameters

### Diabetes Prediction
- Pregnancies
- Glucose Level
- Blood Pressure
- Skin Thickness
- Insulin Level
- BMI
- Diabetes Pedigree Function
- Age

### Heart Disease Prediction
- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Serum Cholesterol
- Fasting Blood Sugar
- Resting ECG Results
- Maximum Heart Rate
- Exercise Induced Angina
- ST Depression
- Slope of Peak Exercise ST Segment
- Number of Major Vessels
- Thalassemia

### Parkinson's Disease Prediction
- Various voice measurement parameters including:
  - MDVP:Fo(Hz)
  - MDVP:Fhi(Hz)
  - MDVP:Flo(Hz)
  - And many others...

## Models
The system uses pre-trained machine learning models saved as .sav files:
- diabetespred_model.sav
- heartdisease_model.sav
- parkinsons_model.sav
