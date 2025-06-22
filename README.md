# 💧 Water Quality Prediction 

A machine learning project to **predict multiple water quality parameters** using **multi-output regression**, developed as part of the **AICTE Virtual Internship – June 2025**, sponsored by **Shell** and organized by **Edunet Foundation**.

---

## 🌍 Project Overview

Access to clean and safe water is a fundamental human right and a global environmental priority. Monitoring water quality is essential for protecting ecosystems, maintaining biodiversity, and ensuring the health and well-being of communities. However, traditional water testing methods can be time-consuming, expensive, and limited in scope.

This project, **Water Quality Prediction**, leverages the power of **machine learning** to provide a faster, scalable, and cost-effective solution to predicting multiple water quality indicators from historical data. By using intelligent algorithms, we aim to support real-time decision-making and early intervention in water resource management.

The core idea is to develop a predictive model that can estimate several key water quality parameters (such as Ammonium, Nitrate, Chloride, and more) simultaneously, using environmental feature inputs. The model is designed using a **multi-output regression approach**, allowing it to handle multiple target variables efficiently.

Through this project, we aim to demonstrate how AI can play a transformative role in environmental monitoring and sustainability, paving the way for smarter, data-driven water quality management systems in the future.


---

## 🎯 Project Objectives

- Process and analyze real-world water quality data
- Build a **multi-target regression model** using `MultiOutputRegressor` with `RandomForestRegressor`
- Evaluate prediction accuracy using **regression metrics**
- Create a modular and reproducible pipeline in Jupyter Notebook

---

## 🧪 Technologies and Tools Used

| Tool          | Purpose                            |
|---------------|------------------------------------|
| **Python 3.12** | Programming Language              |
| **Jupyter Notebook** | Interactive development & visualization |
| **Pandas**     | Data manipulation                 |
| **NumPy**      | Numerical computation             |
| **Scikit-learn** | Model training, evaluation       |
| **Matplotlib** / **Seaborn** | Data visualization      |

---

## 📁 Contents Included

- `Water_Quality_Prediction.ipynb` – The full notebook covering data loading, processing, training, and evaluation
- `PB_ALL_2020_2021.csv` – Real-world dataset with multiple features and labels
- `README.md` – Documentation and project details

---

## 🧬 Predicted Water Quality Parameters

The model is trained to predict the following environmental indicators:

- **NH4** – Ammonium
- **BOD5 (BSK5)** – Biochemical Oxygen Demand (5 days)
- **Colloids**
- **O2** – Dissolved Oxygen
- **NO3** – Nitrates
- **NO2** – Nitrites
- **SO4** – Sulphates
- **PO4** – Phosphates
- **CL** – Chlorides

These parameters help assess the health of water bodies and can serve as early warnings for contamination.

---

## 🤖 Model Details

- **Model Type**: MultiOutput Regression
- **Base Regressor**: `RandomForestRegressor`
- **Wrapper**: `MultiOutputRegressor`
- **Train-Test Split**: 80/20 using `train_test_split`

### 📈 Evaluation Metrics

- **R² Score** – Measures how well the model explains variance
- **Mean Squared Error (MSE)** – Quantifies prediction error

> Performance was acceptable across all predicted parameters with scope for further enhancement via hyperparameter tuning and model ensembling.

---
