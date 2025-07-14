# Diabetes-Prediction
# 🩺 Diabetes Prediction API - FastAPI

This is a simple machine learning API built with **FastAPI** that predicts whether a person is diabetic based on several health parameters.

## 🚀 Features

- ✅ FastAPI backend
- ✅ Accepts JSON input
- ✅ Returns diabetes prediction using a trained ML model
- ✅ Interactive Swagger UI for testing

---

## 📦 Input Parameters

| Parameter                  | Type    | Description                    |
|---------------------------|---------|--------------------------------|
| `Pregnancies`             | int     | Number of pregnancies          |
| `Glucose`                 | int     | Plasma glucose concentration   |
| `BloodPressure`           | int     | Diastolic blood pressure (mm Hg) |
| `SkinThickness`           | int     | Triceps skinfold thickness (mm) |
| `Insulin`                 | int     | 2-Hour serum insulin (mu U/ml) |
| `BMI`                     | float   | Body mass index                |
| `DiabetesPedigreeFunction`| float   | Diabetes pedigree function     |
| `Age`                     | int     | Age in years                   |

---

## 📥 Example Input

```json
{
  "Pregnancies": 2,
  "Glucose": 120,
  "BloodPressure": 70,
  "SkinThickness": 25,
  "Insulin": 100,
  "BMI": 28.0,
  "DiabetesPedigreeFunction": 0.5,
  "Age": 30
}
