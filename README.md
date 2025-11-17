# Heart Disease Prediction App

Welcome to the **Heart Disease Prediction App**! This is a simple, locally runnable machine learning application that predicts the risk of heart disease based on key clinical features like age, blood pressure, cholesterol, and more.

> **Important**: This tool is for **educational and informational purposes only**. It is **not a medical device** and should **not replace professional medical advice**. Always consult a qualified healthcare provider for diagnosis or treatment.

---

## Features

- Predict heart disease risk using a trained **K-Nearest Neighbors (KNN)** model
- Interactive input form with sliders and dropdowns
- Real-time prediction results
- Fully runs **locally** — no internet or hosting required
- Built with **Streamlit**, **scikit-learn**, and **Pandas**

---

## Dataset Used

The model is trained on the **[Heart Failure Prediction Dataset](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction)** from Kaggle, containing 918 patient records with 12 health features.

---


## How to Run Locally (Step-by-Step)

Follow these instructions to run the app on your computer.

### Prerequisites

- **Python 3.8 or higher** installed
- **pip** (Python package manager)
- Basic familiarity with terminal/command prompt

---

### Step 1: Clone or Download the Project

```
git clone https://github.com/your-username/heart-disease-prediction.git
cd heart-disease-prediction
```
If you don't have git, just download the ZIP and extract it.


### Step 2: Create a Virtual Environment (Recommended)
```
python -m venv venv
```
Activate it:

Windows:bash
```venv\Scripts\activate```
Mac/Linux:bash
```source venv/bin/activate```


Step 3: Install Required Packages
bash
```pip install -r requirements.txt```
If requirements.txt is missing, run this instead:
bash
```pip install streamlit pandas scikit-learn joblib numpy matplotlib seaborn```

Step 4: Run the Streamlit App
bash
```streamlit run app.py```
