# 🏗️ Concrete Compressive Strength Prediction (PRCP-1019-ConcreteStren)

Predicting the **compressive strength** of concrete (in MPa) based on its ingredient composition and age, using Machine Learning regression models.

## 📌 Problem Statement

Concrete is the most important material in civil engineering. Its compressive strength is a **highly nonlinear function** of its age and ingredients — cement, blast furnace slag, fly ash, water, superplasticizer, coarse aggregate, and fine aggregate.

The goal of this project is to:
1. Perform a complete **data analysis** on the concrete dataset.
2. Build a **Machine Learning regression model** to predict the future compressive strength of a concrete mix based on its constituents and age.

> This is a **regression problem** — the target variable (`Concrete compressive strength`) is continuous (measured in MPa), not a category.

## 📂 Dataset

**File:** `concrete.csv`

- 1030 instances (observations)
- 8 quantitative input variables
- 1 quantitative output variable
- Raw, unscaled data

| Feature | Data Type | Measurement | Description |
|---|---|---|---|
| Cement (component 1) | quantitative | kg in a m³ mixture | Input Variable |
| Blast Furnace Slag (component 2) | quantitative | kg in a m³ mixture | Input Variable |
| Fly Ash (component 3) | quantitative | kg in a m³ mixture | Input Variable |
| Water (component 4) | quantitative | kg in a m³ mixture | Input Variable |
| Superplasticizer (component 5) | quantitative | kg in a m³ mixture | Input Variable |
| Coarse Aggregate (component 6) | quantitative | kg in a m³ mixture | Input Variable |
| Fine Aggregate (component 7) | quantitative | kg in a m³ mixture | Input Variable |
| Age | quantitative | Day (1~365) | Input Variable |
| **Concrete compressive strength** | quantitative | MPa | **Output Variable (target)** |

Dataset source: [PRCP-1019-ConcreteStren.zip](https://d3ilbtxij3aepc.cloudfront.net/projects/CDS-Capstone-Projects/PRCP-1019-ConcreteStren.zip)

## 🎯 Objectives

1. **Data Analysis Report** — Complete EDA on the concrete dataset (distributions, correlations, outliers).
2. **ML Model** — Predict concrete compressive strength based on ingredients + age.
3. **Model Comparison Report** — Compare multiple regression models and recommend the best one for production.
4. **Challenges Report** — Document data challenges faced and techniques used, with proper reasoning.

## 🗂️ Project Structure

```
concrete-strength-project/
│
├── data/
│   └── concrete.csv
│
├── notebooks/
│   └── PRCP_1019.ipynb   # Full analysis + modeling notebook
│
├── reports/
│   ├── model_comparison_report.md
│   └── challenges_report.md
│
├── requirements.txt
├── .gitignore
└── README.md
```

## 🛠️ Tech Stack

- Python 3.x
- Pandas, NumPy — data handling
- Matplotlib, Seaborn — visualization
- Scikit-learn — ML models & evaluation
- XGBoost — gradient boosting
- Jupyter Notebook

## 🚀 How to Run

```bash
# 1. Clone the repository
git clone https://github.com/<your-username>/concrete-strength-prediction.git
cd concrete-strength-prediction

# 2. Create a virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Launch Jupyter Notebook
jupyter notebook notebooks/PRCP_1019.ipynb
```

## 📊 Models Explored

- Linear Regression
- Ridge / Lasso Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting / XGBoost Regressor
- Support Vector Regressor (SVR)

Evaluation metrics: **R² Score, MAE, MSE, RMSE**

(See `reports/model_comparison_report.md` for detailed performance metrics and the final recommended model.)

## 📈 Key Deliverables

- ✅ Complete EDA with visualizations
- ✅ Regression model for compressive strength prediction
- ✅ Feature importance / correlation analysis
- ✅ Model comparison report
- ✅ Challenges & techniques report
- ✅ Single consolidated Jupyter Notebook

## 👤 Author

Add your name, LinkedIn, and portfolio link here.

## 📄 License

This project is for educational/capstone purposes.
