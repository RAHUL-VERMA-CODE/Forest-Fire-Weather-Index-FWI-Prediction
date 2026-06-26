# 🔥 Forest Fire Weather Index (FWI) Prediction

A Machine Learning web application built with **Flask** that predicts the **Forest Fire Weather Index (FWI)** using a trained **Ridge Regression** model.

## 🚀 Features

* Predicts Forest Fire Weather Index (FWI)
* Flask-based web interface
* Ridge Regression model
* StandardScaler for feature preprocessing
* Simple and responsive user interface
* Ready for deployment

---

## 📂 Project Structure

```text
Forest-Fire-Prediction/
│
├── models/
│   ├── ridge.pkl
│   └── scaler.pkl
│
├── static/
│   └── style.css
│
├── templates/
│   ├── index.html
│   └── home.html
│
├── application.py
├── requirements.txt
└── README.md
```

---

## 🛠️ Technologies Used

* Python
* Flask
* Scikit-learn
* NumPy
* Pandas
* HTML
* CSS

---

## 📊 Input Features

The model uses the following features:

* Temperature
* Relative Humidity (RH)
* Wind Speed (Ws)
* Rain
* FFMC
* DMC
* ISI
* Classes
* Region

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/Forest-Fire-Prediction.git
```

### 2. Move into the project directory

```bash
cd Forest-Fire-Prediction
```

### 3. Create a virtual environment

**Windows**

```bash
python -m venv venv
venv\Scripts\activate
```

**Linux / macOS**

```bash
python3 -m venv venv
source venv/bin/activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Application

```bash
python application.py
```

Open your browser and visit:

```text
http://127.0.0.1:5000/
```

---

## 📈 Machine Learning Workflow

* Data Collection
* Data Cleaning
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Train-Test Split
* Feature Scaling using StandardScaler
* Ridge Regression Model Training
* Model Serialization using Pickle
* Flask Deployment

---

## 📷 Screenshots

Add screenshots of:

* Home Page
* Prediction Form
* Prediction Result

---

## 🤝 Contributing

Contributions are welcome. Feel free to fork the repository and submit a pull request.

---

## 📄 License

This project is intended for educational and learning purposes.

---

## 👨‍💻 Author

**Rahul Verma**

GitHub: https://github.com/RAHUL-VERMA-CODE

LinkedIn: https://www.linkedin.com/in/rahul-verma53/
