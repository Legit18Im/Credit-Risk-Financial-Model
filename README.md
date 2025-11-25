# 💳 Credit Card Default Prediction

[![Python](https://img.shields.io/badge/Python-3.12-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![Framework](https://img.shields.io/badge/Framework-Flask-000000?logo=flask&logoColor=white)](https://flask.palletsprojects.com/)
[![ML](https://img.shields.io/badge/Library-Scikit--Learn-F7931E?logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![Cloud](https://img.shields.io/badge/Deployment-AWS-232F3E?logo=amazon-aws&logoColor=white)](https://aws.amazon.com/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

## 📋 Overview
This project is a robust machine learning classification system designed to predict credit card defaulters for the next month. By analyzing demographic data and behavioral patterns from the last six months, the model helps financial institutions mitigate risk and make informed lending decisions.

The solution includes a full-stack implementation: from data preprocessing and model training to a deployed web application for real-time inference.

## 📊 Dataset Information
The model is trained on the **Default of Credit Card Clients Dataset**.
- **Source:** Taiwan (April 2005 to September 2005)
- **Features:** 25 variables including default payments, demographic factors, credit data, history of payment, and bill statements.
- **Target:** Default payment (Yes=1, No=0)

## 🛠 Tech Stack

| Category | Technologies |
| :--- | :--- |
| **Programming Language** | Python 3.12 |
| **Web Framework** | Flask / Dash |
| **Machine Learning** | Scikit-Learn, XGBoost, Pandas, NumPy |
| **Deployment** | AWS / Heroku |
| **Front-End** | HTML, CSS (Dash Components) |
| **Version Control** | Git, GitHub |

## ⚙️ Technical Architecture

The project follows a standard Data Science Lifecycle:

1.  **Data Ingestion & Cleaning:** Handling missing values, outlier detection, and feature engineering.
2.  **Exploratory Data Analysis (EDA):** Visualizing correlations and data distribution using Matplotlib and Seaborn.
3.  **Model Selection:** Tested multiple algorithms including:
    * Random Forest Classifier
    * XGBoost Classifier
    * Decision Tree
    * KNN & MLP Classifier
4.  **Hyperparameter Tuning:** Optimized using `GridSearchCV` to prevent overfitting.
5.  **Deployment:** The best-performing model (XGBoost) was serialized (pickled) and integrated into a Flask/Dash web app hosted on AWS.

## 📈 Model Performance
After rigorous testing and cross-validation, the final model achieved:
* **Accuracy:** ~84%
* **Precision/Recall:** Optimized to minimize false negatives (missed defaulters).

## 🚀 Installation & Setup

To run this project locally, follow these steps:

**1. Clone the Repository**
```bash
git clone [https://github.com/Legit18Im/Credit-Risk-Financial-Model.git](https://github.com/Legit18Im/Credit-Risk-Financial-Model.git)
cd Credit-Risk-Financial-Model
````

**2. Create a Virtual Environment**

```bash
conda create -p venv python==3.12.0 -y
conda activate ./venv
```

**3. Install Dependencies**

```bash
pip install -r requirements.txt
```

**4. Run the Application**

```bash
python app.py
```

Open your browser and navigate to `http://127.0.0.1:5000/`.

## 🖥️ Project Interface

### **Live Demo**

**[🔗 Click Here to View Live App on AWS](https://www.google.com/search?q=%23)** *(Insert your AWS link here)*



## 📂 Directory Structure

```
├── artifacts/          # Saved model files (.pkl)
├── notebooks/          # Jupyter notebooks for EDA and Training
├── static/             # CSS/JS files
├── templates/          # HTML templates
├── src/                # Source code for pipelines
├── app.py              # Main Flask application
├── requirements.txt    # Python dependencies
├── Procfile            # Heroku deployment configuration
└── README.md           # Project documentation
```

## 👨‍💻 Author

**Jay Shahapurakar**

  * **Role:** AI Engineer & Data Scientist
  * **GitHub:** [Legit18Im]([https://www.google.com/search?q=https://github.com/Legit18Im](https://github.com/Legit18Im/Jay-Shahapurakar))
  * **LinkedIn:** [Jay Shahapurakar](www.linkedin.com/in/jay-shahapurakar)
  * **Email:** jayshahapurakar@gmail.com

-----

*If you find this repository useful, please give it a star\! ⭐*

```
5.  **Author Section:** Clearly branded it with your name and links.

### **Action Items for you:**
1.  **Screenshots:** Take 2 screenshots of your running app. Name them `screenshot1.png` and `screenshot2.png`, upload them to your GitHub repo, and update the links in the code above.
2.  **AWS Link:** Paste your actual AWS link where it says `(Insert your AWS link here)`.
3.  **Requirements:** Ensure your `requirements.txt` is clean (the one in your text looked good, but make sure `gunicorn` is there if you are deploying to cloud).
```
