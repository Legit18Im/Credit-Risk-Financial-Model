# Credit-Card-Default-Prediction

## Overview
This is a classification model for a most common dataset, Credit Card defaulter prediction. Prediction of the next month credit card defaulter based on demographic and last six months behavioral data of customers.

## Dataset Information
This dataset contains information on default payments, demographic factors, credit data, history of payment, and bill statements of credit card clients in _Taiwan from April 2005 to September 2005_.

## Technical Aspect
This project is divided into two part:
1. Training a [RandomForestClassifier](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html) classification model to predict defaulter as accurate as possible.
	- Cleaning the datasets, fixing all features
	- Apply Classification ML model
2. Building and hosting a Flask web app on Heroku.
	- Build the web app using Flask API
	- Upload the project on GitHub
    - Get the customer information from Web app
    - Display the prediction 


## Software and Tools Required

1. [Github account](https://github.com)
2. [AWS Account](https://aws.amazon.com/console/)
3. [VS code IDE](https://code.visualstudio.com/)
4. [GitCli](https://git-scm.com/downloads)

Create a new environment of project 

```
conda create -p venv python==3.12.0 -y

```

## Approach

Below are steps taken to build this project
1) Create Repository on GitHub with gitignore as pyhton.
2) Clone Repository from GitHub to Local using git clone command in VS Studio Code
3) Create a virtual environment inside working foleder named venv use command - python -m venv "path/venv"
4) Create a requirements.txt file which contains all libraries that are required to run this project.
5) Read Dataset using pandas library
6) Start Exploratory data analysis
7) Start building various models like Decision Tree Classifier, Random Forest Classifier, XGBoost Classifier, KNN Classifier, MLP Clasiifier
8) Tune the models with cross validation using GridSearchCV
9) Select best model and make pickle file.
10) Create app.py file which used dash library for front-end design.
11) Test the app.py on local system.
12) Create Procfile for deployement in Heroku platform.
13) Add, Commit and Push all files from Local to GitHub
14) Deploy to Heroku and Link the GitHub Repository

#Git Config --
git config --global user.name "Legit18Im"
git config --global user.email "jayshahapurakar@gmail.com"



# Project Interface


#### I have deployed this model to Amazon Web Services (AWS)
#### Link:
## Technologies Used

![](https://forthebadge.com/images/badges/made-with-python.svg)

[<img target="_blank" src="https://numpy.org/images/logo.svg" width=100>](https://numpy.org)    [<img target="_blank" src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/ed/Pandas_logo.svg/450px-Pandas_logo.svg.png" width=150>](https://pandas.pydata.org)    [<img target="_blank" src="https://scikit-learn.org/stable/_static/scikit-learn-logo-small.png" width=150>](https://scikit-learn.org/stable)   [<img target="_blank" src="https://www.statsmodels.org/stable/_images/statsmodels-logo-v2-horizontal.svg" width=170>](https://www.statsmodels.org)

[<img target="_blank" src="https://matplotlib.org/_static/logo2_compressed.svg" width=170>](https://matplotlib.org)      [<img target="_blank" src="https://seaborn.pydata.org/_static/logo-wide-lightbg.svg" width=150>](https://seaborn.pydata.org)

[<img target="_blank" src="https://jupyter.org/assets/logos/rectanglelogo-greytext-orangebody-greymoons.svg" width=150>](https://jupyter.org)







 conda activate E:\CreditCardDefaultPrediction-main\cred


 pip freeze > requirements.txt
 web: python app.py

 heroku login

