# kalimati-market-analysis-daml
# Kalimati Market Analysis

This project is a comprehensive data analytics case study based on the Kalimati Fruits and Vegetable Market in Nepal. It involves exploring, cleaning, modeling, and visualizing real-world agricultural price data to derive actionable insights and enhance decision-making.

---

## 📌 Features

- ✅ Accurate **data cleaning** and preprocessing
- ✅ Feature engineering (e.g., extracting month, weekday from date)
- ✅ **Exploratory Data Analysis (EDA)** with appropriate visualizations
- ✅ **Linear Regression** with OLS summary (R², p-values)
- ✅ **Random Forest Classification** with confusion matrix, accuracy, FPR, and FNR
- ✅ **K-Means Clustering** on price-related features
- ✅ Visualizations saved to `plots/` directory
- ✅ Cross-validation applied for both regression and classification tasks

---

## 🗂️ Folder Structure

kalimati-market-analysis/
│
├── data/
│ ├── kalimati-tarkari-prices-from-may-2021-to-september-2023.csv
│ └── cleaned_kalimati_data_final.csv
│
├── notebooks/
│ └── Kalimati_Market_Analysis.ipynb
│
├── plots/
│ ├── eda_avg_price_distribution.png
│ ├── correlation_heatmap.png
│ ├── lr_actual_vs_predicted.png
│ ├── rf_actual_vs_predicted.png
│ └── kmeans_clustering.png
│
├── README.md
├── requirements.txt
└── .gitignore

yaml
Copy
Edit

---

## ⚠️ Important Note on File Paths

> The notebook uses paths like `/mnt/data/filename.csv` which may not work outside certain environments.  
> **Make sure to replace all file paths with your own local or project-relative paths** before running the code.

**Example fix:**
```python
# Original (example from shared server)
df = pd.read_csv("/mnt/data/filename.csv")

# Updated for your machine
df = pd.read_csv("data/filename.csv")
📊 Visual Output
eda_avg_price_distribution.png – Distribution of average prices

correlation_heatmap.png – Heatmap of pricing feature correlations

lr_actual_vs_predicted.png – Regression prediction results

rf_actual_vs_predicted.png – Classification prediction results

kmeans_clustering.png – Price-based segmentation clusters

🛠️ Tech Stack
Python 3.11+

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

Statsmodels

Jupyter Notebook

👤 Author
Prapanna Upadhyay


