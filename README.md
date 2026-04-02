**Insurance Charges Prediction**:
Predicting Medical Costs with Machine Learning (Linear Regression)
Turning raw healthcare data into a pricing compass for smarter insurance decisions.

**Project Overview**:
Insurance pricing is a delicate balancing act between risk and fairness. In this project, 
we build a Linear Regression model to predict individual medical insurance charges based on demographic, lifestyle, and other medical history data.

**Goal**: Estimate healthcare costs accurately using data-driven insights.

**Dataset Summary**
📦 Records: 1,338 individuals.
🧾 Features: 13 variables.
🎯 Target Variable: charges.

**Key Features**:
| Feature                           | Description                        |
| --------------------------------- | ---------------------------------- |
| `age`                             | Age of the individual              |
| `sex`                             | Gender                             |
| `bmi`                             | Body Mass Index                    |
| `children`                        | Number of dependents               |
| `smoker`                          | Smoking status (major cost driver) |
| `Claim_Amount`                    | Previous claim amount              |
| `past_consultations`              | Medical consultation history       |
| `num_of_steps`                    | Daily activity level               |
| `Hospital_expenditure`            | Historical hospital costs          |
| `NUmber_of_past_hospitalizations` | Past hospital visits               |
| `Anual_Salary`                    | Income level                       |
| `region`                          | Residential region                 |
| `charges`                         | 💰 Insurance cost (Target)         |

**Approach**:

1. **Data Preprocessing**:
Cleaned and validated dataset
Encoded categorical variables (sex, smoker, region)
Checked for missing values and inconsistencies

**2. Exploratory Data Analysis (EDA)**:
Distribution analysis of charges
Outlier detection (BMI, salary, charges)
Key insight: Smokers incur significantly higher charges

**3. Model Building**:

We use a classic algorithm: 

**Linear Regression**: charges=β0​+β1​X1​+β2​X2​+...+βn​X

**4. Model Evaluation**:

| Metric         | Purpose                              |
| -------------- | ------------------------------------ |
| **R² Score**   | How well the model explains variance |
| **MAE**        | Average prediction error             |
| **MSE / RMSE** | Penalizes large errors               |

**Tech Stack**:

Language: Python 🐍
Libraries:
pandas
numpy
scikit-learn
matplotlib / seaborn
