# 🏠 Boston House Price Prediction

A complete end-to-end Machine Learning project that predicts Boston house prices based on housing features. The project covers data preprocessing, model training, model serialization, web application development, and cloud deployment.

---

# 📌 Table of Contents

* Overview
* Features
* Tech Stack
* Project Structure
* Software & Tools Requirements
* Installation
* Running the Application
* Deployment
* API Usage
* Future Improvements
* Author

---

# 📖 Overview

This project demonstrates the complete Machine Learning workflow:

* Data Collection
* Data Cleaning
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Model Training
* Model Evaluation
* Model Serialization
* Flask Web Application
* Cloud Deployment

---

# ✨ Features

* Predicts Boston house prices
* User-friendly web interface
* Trained Scikit-learn model
* Flask backend
* Ready for cloud deployment
* Simple and modular project structure

---

# 🛠️ Tech Stack

### Programming Language

* Python

### Machine Learning

* Scikit-learn
* NumPy
* Pandas

### Data Visualization

* Matplotlib
* Seaborn

### Backend

* Flask
* Gunicorn

### Frontend

* HTML
* CSS

### Version Control

* Git
* GitHub

### Deployment

* Render

---

# 📂 Project Structure

```text
boston_house_pricing_ml/
│
├── .gitignore                 # Files and folders ignored by Git
├── app.py                     # Flask application
├── boston_housing_ml.ipynb    # Model training & experimentation notebook
├── LICENSE                    # Project license
├── README.md                  # Project documentation
├── regmodel.pkl               # Trained Regression model
├── requirements.txt           # Python dependencies
├── std_scaler.pkl             # Saved StandardScaler object
│
├── templates/                 # templates
│   └── home.html              # Home page
│
└── venv/                      # Python virtual environment

```

---

# 💻 Software & Tools Requirements

| Tool                 | Purpose              | Link                               |
| -------------------- | -------------------- | ---------------------------------- |
| Python 3.11+         | Programming Language | https://www.python.org/downloads/  |
| Git                  | Version Control      | https://git-scm.com/downloads      |
| GitHub               | Repository Hosting   | https://github.com                 |
| Visual Studio Code   | IDE                  | https://code.visualstudio.com/     |
| Render               | Cloud Deployment     | https://render.com                 |
| Postman *(Optional)* | API Testing          | https://www.postman.com/downloads/ |
| Jupyter Notebook     | Model Development    | https://jupyter.org/               |

---

# ⚙️ Installation

## 1. Clone the Repository

```bash
git clone https://github.com/Sanmaya2503/boston_house_pricing_ml.git
```

```bash
cd boston_house_pricing_ml
```

---

## 2. Create Virtual Environment

```bash
python -m venv venv
```

---

## 3. Activate Virtual Environment

### Windows

```bash
venv\Scripts\activate
```

### Linux / macOS

```bash
source venv/bin/activate
```

---

## 4. Upgrade pip

```bash
python -m pip install --upgrade pip
```

---

## 5. Install Dependencies

```bash
pip install -r requirements.txt
```

---

# ▶️ Run the Application

## Using Python

```bash
python app.py
```

or

```bash
flask run
```

Visit:

```
http://127.0.0.1:5000
```

---

# 🚀 Deployment on Render

## Step 1

Push your project to GitHub.

## Step 2

Login to:

https://render.com

## Step 3

Click

```
New +
```

↓

```
Web Service
```

↓

```
Connect GitHub Repository
```

---

## Step 4

Use the following configuration.

### Build Command

```bash
pip install -r requirements.txt
```

### Start Command

```bash
gunicorn app:app
```

---

## Step 5

Click

```
Deploy Web Service
```

Render will automatically build and deploy the application.

---

# 📦 Required Files for Deployment

```
requirements.txt
```

```
app.py
```

```

```
README.md
```

```
.gitignore
```

---

# 📚 Useful Resources

### Flask Documentation

https://flask.palletsprojects.com/

### Scikit-learn Documentation

https://scikit-learn.org/

### Pandas Documentation

https://pandas.pydata.org/

### NumPy Documentation

https://numpy.org/

### Gunicorn Documentation

https://gunicorn.org/

### Render Documentation

https://render.com/docs

### Git Documentation

https://git-scm.com/doc

---

# 🔮 Future Improvements

* Docker support
* CI/CD with GitHub Actions
* Model monitoring
* REST API
* Multiple ML models
* Feature importance visualization
* Model versioning
* User authentication
* Cloud database integration

---

# 👨‍💻 Author

**Sanmaya Pandua**

MCA Graduate (2026)

Aspiring Data Scientist | Machine Learning Enthusiast

GitHub: https://github.com/Sanmaya2503

LinkedIn: https://www.linkedin.com/in/sanmaya-pandua-453bbb32a/

---

## ⭐ If you found this project helpful, please consider giving it a star on GitHub!
