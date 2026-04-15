# 📊 Customer Retention (Churn Prediction)

## 🔴 What is Customer Churning ?

![Customer Retention](https://raw.githubusercontent.com/pik1989/MLProject-Churn-Analysis-And-Prediction-Model/main/images/Telco1.JPG)

## 🔴 What are the different Churn Scenarios ?

![Churn Scenarios](https://raw.githubusercontent.com/pik1989/MLProject-Churn-Analysis-And-Prediction-Model/main/images/Telco2.JPG)

## 🔴 Decision Cycle of a Subscriber ?

![Decision Cycle](https://raw.githubusercontent.com/pik1989/MLProject-Churn-Analysis-And-Prediction-Model/main/images/Telco3.JPG)

## 🔴 What are the different Churn Segments ?

![Churn Segments](https://raw.githubusercontent.com/pik1989/MLProject-Churn-Analysis-And-Prediction-Model/main/images/Telco4.JPG)

## 🔴 Solution Overview

![Solution](https://raw.githubusercontent.com/pik1989/MLProject-Churn-Analysis-And-Prediction-Model/main/images/Telco5.JPG)

---

## 📌 Project Overview

This project focuses on **Customer Churn Prediction** using Machine Learning.

We performed:
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Model Building
- Model Deployment using Flask

## 🚀 Model Deployment (Flask)

### 🔹 Initialize Flask App

```python
app = Flask("__name__")
@app.route("/")
def loadPage():
    return render_template('home.html', query="")

  @app.route("/", methods=['POST'])
def predict():

app.run()

git clone https://github.com/your-username/customer-retention.git
cd customer-retention

pip install -r requirements.txt

python app.py

http://127.0.0.1:5000/





