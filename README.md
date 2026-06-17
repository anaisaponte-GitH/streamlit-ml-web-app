# Medical Insurance Cost Predictor

Interactive Machine Learning web application built with Streamlit and deployed on Render.

The application allows users to estimate medical insurance costs by entering basic demographic and lifestyle information.

---

## Live Application

https://streamlit-ml-web-app.onrender.com

---

## Application Preview

![Medical Insurance Cost Predictor](preview.png)

---

## Project Overview

This project demonstrates how a trained Machine Learning model can be transformed into a user-facing web application.

The application loads a previously trained Linear Regression model and allows users to generate insurance cost predictions through an interactive interface.

The focus of this repository is the deployment and usability layer of the Machine Learning solution.

---

## Application Features

Users can enter the following information:

- Age
- Sex
- BMI
- Number of children
- Smoking status
- Region

The application processes these inputs, applies the same feature structure used during model training, and returns an estimated medical insurance cost.

---

## How It Works

1. The trained Linear Regression model is loaded from a `.sav` file.
2. User inputs are collected through Streamlit widgets.
3. Categorical variables are converted into the encoded format expected by the model.
4. The input data is passed to the model.
5. The estimated insurance cost is displayed to the user.

---

## Technologies Used

- Python
- Streamlit
- Pandas
- Scikit-Learn
- Joblib
- Render

---

## Repository Structure

```text
streamlit-ml-web-app/

├── README.md
├── requirements.txt
├── preview.png
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

## Related Project

This application is based on a regression model developed in the Medical Insurance Cost Prediction project.

The original Machine Learning analysis includes:

- Exploratory Data Analysis
- Model training
- Model comparison
- Model selection
- Model export for deployment

---

## Key Learnings

- Building interactive Machine Learning applications.
- Loading serialized models with Joblib.
- Creating user input forms with Streamlit.
- Preparing user inputs for model inference.
- Deploying a Machine Learning web application with Render.
- Turning a trained model into a usable product.

---

## Author

**Anaís Aponte**

Senior Product Owner | Agile Delivery | Data & AI

GitHub: https://github.com/anaisaponte-GitH

LinkedIn: https://linkedin.com/in/anaisaponte
