# 💰 Medical Insurance Cost Predictor

Machine Learning web application built with Streamlit and deployed on Render to estimate medical insurance costs based on customer information.

---

## 🚀 Live Demo

Try the deployed application here:

🔗 https://streamlit-ml-web-app.onrender.com

---

## 📸 Application Preview

![Medical Insurance Cost Predictor](preview.png)

---

## 🎯 Business Problem

Medical insurance costs are influenced by multiple demographic and lifestyle factors such as age, body mass index (BMI), smoking habits, family size, and geographic region.

The objective of this project is to provide an estimation tool that predicts insurance charges using historical customer data and Machine Learning techniques.

Potential use cases include:

- Insurance cost estimation.
- Risk assessment support.
- Educational demonstration of regression models.
- Machine Learning model deployment practice.

---

## 📊 Dataset

The project uses the **Medical Insurance Cost Dataset**, which contains demographic and health-related information for insurance customers.

### Features

- Age
- Sex
- BMI (Body Mass Index)
- Number of children
- Smoking status
- Region

### Target Variable

- **Charges** → Medical insurance cost.

---

## 🧠 Solution Approach

### Exploratory Data Analysis (EDA)

The dataset was explored to identify:

- Feature distributions.
- Relationships between variables.
- Correlations with insurance costs.
- Potential outliers.

### Data Preparation

The preprocessing workflow included:

- Handling categorical variables.
- Feature encoding.
- Train/Test split.
- Data validation.

### Model Training

Several regression algorithms were evaluated during experimentation.

The final deployed solution uses a **Linear Regression** model trained on the Medical Insurance dataset.

### Model Deployment

The trained model was serialized as a `.sav` file and integrated into a Streamlit web application.

Users can enter their information through a friendly interface and instantly obtain an estimated insurance cost.

---

## 📈 Model Performance

The deployed model was evaluated using standard regression metrics.

**Model:** Linear Regression

- R² Score: *(add your value here)*
- MAE (Mean Absolute Error): *(add your value here)*
- RMSE (Root Mean Squared Error): *(add your value here)*

> These metrics measure how accurately the model predicts insurance charges based on customer information.

---

## 💻 Application Features

The application allows users to provide:

- Age
- Sex
- BMI
- Number of children
- Smoking status
- Region

After submitting the information, the model generates an estimated insurance cost in real time.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- Joblib
- Streamlit
- Render

---

## 📂 Repository Structure

```text
streamlit-ml-web-app/

├── README.md
├── requirements.txt
├── preview.png
│
├── data/
│   ├── raw/
│   ├── interim/
│   └── processed/
│
├── models/
│   └── linear_regression_medical_insurance_default.sav
│
└── src/
    ├── app.py
    ├── explore.ipynb
    └── utils.py
```

---

## 🎓 Key Learnings

This project demonstrates:

- End-to-end Machine Learning workflow.
- Regression model development.
- Feature engineering and preprocessing.
- Model serialization using Joblib.
- Building user-facing applications with Streamlit.
- Deploying Machine Learning solutions to production environments.

---

## 👩‍💻 Author

**Anais Aponte**

Senior Product Owner | Agile Delivery | Data & AI

🔗 GitHub: https://github.com/anaisaponte-GitH

🔗 LinkedIn: https://linkedin.com/in/anaisaponte
