# Health Insurance Cost Prediction

## Overview
Health insurance companies need to estimate medical costs for individuals in order to set fair premiums. This project builds a machine learning regression model that predicts an individual's **medical insurance charges** based on personal and lifestyle attributes such as age, BMI, smoking status, and region.

## Problem Statement
- Prepare a complete data analysis report on the insurance dataset.
- Build a machine learning model to predict individual medical insurance charges based on personal attributes.
- Compare the performance of multiple models and recommend the best one for accurate premium estimation.
- Document the challenges faced with the data and the techniques used to address them.

## Dataset
The dataset contains **1,338 records** with the following features:

| Feature | Description |
|---|---|
| age | Age of the primary beneficiary |
| sex | Gender of the insurance contractor |
| bmi | Body Mass Index |
| children | Number of dependents covered by the insurance |
| smoker | Smoking status |
| region | Residential area in the US |
| **charges** | Target variable — individual medical costs billed by insurance |

## Approach
1. **Exploratory Data Analysis (EDA)** — studied feature distributions and analyzed how age, BMI, smoking status, and region relate to insurance charges.
2. **Feature Engineering** — encoded categorical features (sex, smoker, region) for model compatibility.
3. **Model Building** — trained and compared multiple regression algorithms to find the best fit for the data.
4. **Model Evaluation** — benchmarked model performance and recommended the best model for accurate premium estimation.
5. **Challenges & Techniques** — documented data-handling decisions (e.g., encoding strategy, handling skewed charge distributions) and the reasoning behind them.

## Tech Stack
- **Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **Environment:** Jupyter Notebook

## Results
The best-performing model was selected based on evaluation metrics on the test set.

*(Update this section with your actual best model name and score, e.g., "Random Forest achieved an R² score of 0.XX.")*

## Repository Structure
```
insurance-cost-prediction/
├── README.md
├── PRCP_1021.ipynb
├── PRCP_insurance.csv
└── requirements.txt
```

## How to Run
1. Clone this repository
   ```
   git clone https://github.com/<your-username>/insurance-cost-prediction.git
   ```
2. Install dependencies
   ```
   pip install -r requirements.txt
   ```
3. Open and run the notebook
   ```
   jupyter notebook PRCP_1021.ipynb
   ```

## Author
**Apurv Prajapati**
[LinkedIn](https://www.linkedin.com/in/apurv-prajapati-ds/)
