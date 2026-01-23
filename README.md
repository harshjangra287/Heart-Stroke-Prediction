# ❤️ Heart Stroke Prediction Project

![Python](https://img.shields.io/badge/Python-3.8+-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-orange)
![Streamlit](https://img.shields.io/badge/Streamlit-App-red)
![Status](https://img.shields.io/badge/Status-Completed-success)

> **A machine learning–based web application to predict the risk of heart stroke using patient health parameters.**

---

## 🚀 Project Overview

Heart stroke is one of the leading causes of death worldwide. Early prediction can help save lives by enabling timely medical intervention. This project uses **Machine Learning** to predict the likelihood of a heart stroke based on various medical and lifestyle factors.

The model is deployed as an **interactive web application using Streamlit**, allowing users to input their health details and instantly receive predictions.

---

## 🧠 Machine Learning Details

* **Algorithm Used:** K-Nearest Neighbors (KNN)
* **Data Preprocessing:**

  * Handling missing values
  * Feature scaling using `StandardScaler`
  * One-hot encoding for categorical features
* **Model Persistence:** `joblib`

---

## 📊 Features Used for Prediction

* Age
* Gender
* Chest pain type
* Resting blood pressure
* Cholesterol level
* Fasting blood sugar
* Resting ECG results
* Maximum heart rate achieved
* Exercise-induced angina
* Old peak (ST depression)
* Slope of ST segment

---

## 🖥️ Web Application

The project is deployed using **Streamlit**, providing:

* Clean and user-friendly UI
* Real-time prediction
* Easy-to-use sliders and dropdowns

### 🔍 Prediction Output

* **Low Risk** 🟢
* **High Risk** 🔴

---

## 📁 Project Structure

```
📦 Heart-Stroke-Prediction
 ┣ 📜 app.py
 ┣ 📜 requirements.txt
 ┣ 📜 knn_heart_model.pkl
 ┣ 📜 heart_scaler.pkl
 ┣ 📜 heart_columns.pkl
 ┣ 📜 README.md
 ┗ 📂 dataset
    ┗ 📜 heart.csv
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/heart-stroke-prediction.git
cd heart-stroke-prediction
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Application

```bash
streamlit run app.py
```

---

## 📦 Requirements

```
streamlit
pandas
numpy
scikit-learn
joblib
```

---

## 📈 Results

* Achieved reliable prediction accuracy on test data
* Model generalizes well on unseen inputs
* Fast and lightweight deployment

---

## 🔮 Future Enhancements

* Use advanced models (Random Forest, XGBoost)
* Add confidence score for predictions
* Deploy on cloud (Heroku / AWS / Streamlit Cloud)
* Integrate real-time health data

---

## 🧑‍💻 Author

**Harsh Jangra**
📍 India
💡 Aspiring Data Scientist | Machine Learning Enthusiast

---

## 📜 Disclaimer

This application is for **educational purposes only** and should **not** be considered a medical diagnosis. Always consult a healthcare professional.

---

## Screenshots

<img width="1920" height="1080" alt="Screenshot (119)" src="https://github.com/user-attachments/assets/c7ac7095-e806-4f11-b2b6-796853deb93c" />

<img width="1920" height="1080" alt="Screenshot (120)" src="https://github.com/user-attachments/assets/23cd6c86-51b1-45b5-b2d2-666bceb7d016" />




⭐ If you found this project helpful, don’t forget to **star the repository**!
