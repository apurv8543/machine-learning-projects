# 📱 Mobile Price Range Prediction (PRCP-1009-CellphonePrice)

Predicting the **price range** of mobile phones (Low, Medium, High, Very High) based on hardware specifications like RAM, battery power, camera quality, connectivity features, etc.

## 📌 Problem Statement

Bob has started his own mobile company and wants to compete with big players like **Apple** and **Samsung**. However, he doesn't know how to price his phones competitively. Instead of guessing, he collected sales data of mobile phones from various companies to find a relationship between mobile **features** (RAM, battery, internal memory, etc.) and the **price range**.

> Note: This is a **classification problem**, not regression — we predict a price *range* (0, 1, 2, 3), not the exact price.

## 🎯 Objectives

1. **Data Analysis** — Perform complete EDA (Exploratory Data Analysis) on the dataset.
2. **Price Range Prediction** — Build a Machine Learning model to predict `price_range` using features like `battery_power`, `ram`, `wifi`, `bluetooth`, `3g/4g` support, etc.
3. **Business Report** — Explain how the model helps Bob's business, including **feature importance** analysis.
4. **Model Comparison** — Compare multiple ML models and recommend the best one for production.
5. **Challenges Report** — Document challenges faced with the data and techniques used to solve them.

## 📂 Dataset

**File:** `Cellphone.csv`

| Feature | Description |
|---|---|
| battery_power | Total energy a battery can store (mAh) |
| blue | Has Bluetooth or not |
| clock_speed | Speed at which microprocessor executes instructions |
| dual_sim | Has dual SIM support or not |
| fc | Front camera megapixels |
| four_g | Has 4G or not |
| int_memory | Internal memory (GB) |
| m_dep | Mobile depth (cm) |
| mobile_wt | Weight of mobile phone |
| n_cores | Number of processor cores |
| pc | Primary camera megapixels |
| px_height | Pixel resolution height |
| px_width | Pixel resolution width |
| ram | RAM (MB) |
| sc_h | Screen height (cm) |
| sc_w | Screen width (cm) |
| talk_time | Longest time battery lasts on a call |
| three_g | Has 3G or not |
| touch_screen | Has touch screen or not |
| wifi | Has WiFi or not |
| **price_range** | **Target variable**: 0 (low), 1 (medium), 2 (high), 3 (very high) |

Dataset source: [PRCP-1009-CellphonePrice.zip](https://d3ilbtxij3aepc.cloudfront.net/projects/CDS-Capstone-Projects/PRCP-1009-CellphonePrice.zip)

## 🗂️ Project Structure

```
cellphone-price-project/
│
├── data/
│   └── Cellphone.csv
│
├── notebooks/
│   └── PRCP_1009.ipynb   # Full analysis + modeling notebook
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
- Jupyter Notebook

## 🚀 How to Run

```bash
# 1. Clone the repository
git clone https://github.com/<your-username>/cellphone-price-prediction.git
cd cellphone-price-prediction

# 2. Create a virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Launch Jupyter Notebook
jupyter notebook notebooks/PRCP_1009.ipynb
```

## 📊 Models Explored

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- XGBoost / Gradient Boosting

(See `reports/model_comparison_report.md` for detailed performance metrics and the final recommended model.)

## 📈 Key Deliverables

- ✅ Complete EDA with visualizations
- ✅ ML model for price range classification
- ✅ Feature importance analysis for business insights
- ✅ Model comparison report
- ✅ Challenges & techniques report
- ✅ Single consolidated Jupyter Notebook

## 👤 Author

Add your name, LinkedIn, and portfolio link here.

## 📄 License

This project is for educational/capstone purposes.
