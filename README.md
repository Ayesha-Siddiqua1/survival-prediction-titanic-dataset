#🚢 Survival Prediction of Titanic Disaster

Here we predicted the survival prediction using the titanic dataset.

# 🚢 Survival Prediction of Titanic Disaster

![Titanic](https://upload.wikimedia.org/wikipedia/commons/f/fd/RMS_Titanic_3.jpg)

## 📌 Overview
This project predicts passenger survival in the **Titanic Disaster** using **Machine Learning** techniques. The dataset includes passenger details like age, class, gender, and fare, which help determine survival chances.

## 🔥 Features
- Exploratory Data Analysis (EDA) to understand key survival patterns.
- Data preprocessing: handling missing values, encoding categorical variables.
- Machine Learning models for survival prediction.
- Model evaluation with accuracy, precision, and recall.

## 📂 Dataset
The dataset used in this project is the **Titanic dataset** from [Kaggle](https://www.kaggle.com/datasets/yasserh/titanic-dataset).

**Columns in the dataset:**
- `PassengerId`: Unique ID of the passenger.
- `Survived`: Survival status (0 = No, 1 = Yes).
- `Pclass`: Passenger class (1st, 2nd, 3rd).
- `Name`: Name of the passenger.
- `Sex`: Gender (male/female).
- `Age`: Age of the passenger.
- `SibSp`: Number of siblings/spouses aboard.
- `Parch`: Number of parents/children aboard.
- `Ticket`: Ticket number.
- `Fare`: Fare paid for the ticket.
- `Cabin`: Cabin number (if available).
- `Embarked`: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).

## ⚙️ Installation
### 1️⃣ Clone the repository
```
git clone https://github.com/your-username/titanic-survival-prediction.git
cd titanic-survival-prediction
```
##2️⃣ Install dependencies
###Make sure you have Python installed, then install the required libraries:

```
pip install pandas numpy matplotlib seaborn scikit-learn
```
##📊 Exploratory Data Analysis (EDA)
###The project includes visualizations and statistical analysis to explore survival rates based on:

Passenger class
Gender
Age groups
Family members aboard

##🤖 Machine Learning Models
###The project uses multiple ML models, including:

Logistic Regression

Model is evaluated based on accuracy, precision, recall, and F1-score.

##🚀 How to Run
###Run the Python script to train the model and make predictions:
```
python titanic_survival_prediction.py
```

##📈 Results
Here I used the LogisticRegression model for survival prediction.

