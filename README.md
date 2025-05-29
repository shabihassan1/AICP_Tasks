# 🧠 Behavior Patterns & Anomalies

*A hands-on collection of Jupyter notebooks that turn raw data into actionable insight—  
from forecasting Instagram reach to spotting fraudulent transactions and COVID-19 hot-zones.*

> **Purpose:** showcase full-stack data-science skills → **EDA ▸ feature engineering ▸ ML / Stats ▸ evaluation ▸ storytelling**

---

## 📁 Project Layout

```

behavior-patterns-and-anomalies/
│
├── # Notebooks
│   ├── instagram_forecast.ipynb
│   ├── user_segmentation.ipynb
│   ├── rfm_customer_profiles.ipynb
│   ├── transaction_anomalies.ipynb
│   ├── query_outliers.ipynb
│   ├── eda_sprint.ipynb
│   └── covid_analysis.ipynb
│
├── # CSV/XLSX sources (committed for reproducibility)            
│   ├── COVID-19 Daily.xlsx
│   ├── Instagram-Reach.csv
│   ├── Queries.csv
│   ├── tips.csv
│   ├── transaction_anomalies_dataset.csv
│   ├── user_profiles_for_ads.csv
│   └── userbehaviour.csv
├── requirements.txt
└── README.md

````

Each notebook is **self-contained**—open, run top-to-bottom, enjoy the insights.


## 🚀 Notebook Overview

| Notebook | What it tackles | Key Techniques |
|----------|-----------------|----------------|
| `instagram_forecast.ipynb` | Forecasts Instagram reach & engagement. | SARIMA, seasonality plots, MAPE eval |
| `user_segmentation.ipynb` | Clusters mobile-app users into personas. | K-Means, PCA, silhouette score |
| `rfm_customer_profiles.ipynb` | Builds marketing segments from ad data. | RFM metrics, hierarchical clustering |
| `transaction_anomalies.ipynb` | Flags fraudulent bank transactions. | Isolation Forest, DBSCAN, ROC |
| `query_outliers.ipynb` | Detects spammy search terms. | TF-IDF, cosine similarity, elbow method |
| `eda_sprint.ipynb` | Rapid exploratory data analysis template. | Missing-value heatmaps, pairplots |
| `covid_analysis.ipynb` | Visualises COVID-19 spread patterns. | Rolling averages, choropleths, SIR hints |


## 🛠 Tech Stack

| Layer | Tools |
|-------|-------|
| **Core** | ![Python](https://img.shields.io/badge/Python-3.9%2B-3776AB?logo=python&logoColor=white&style=for-the-badge) ![JupyterLab](https://img.shields.io/badge/JupyterLab-F37626?logo=jupyter&logoColor=white&style=for-the-badge) |
| **Data** | ![pandas](https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=white&style=for-the-badge) ![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white&style=for-the-badge) ![openpyxl](https://img.shields.io/badge/openpyxl-0072C6?style=for-the-badge) |
| **ML / Stats** | ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white&style=for-the-badge) ![statsmodels](https://img.shields.io/badge/statsmodels-003366?style=for-the-badge) ![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?logo=scipy&logoColor=white&style=for-the-badge) |
| **Visuals** | ![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?logo=plotly&logoColor=white&style=for-the-badge) ![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge) ![Plotly](https://img.shields.io/badge/Plotly-3F4F75?logo=plotly&logoColor=white&style=for-the-badge) |
| **Misc** | ![tqdm](https://img.shields.io/badge/tqdm-FFB000?style=for-the-badge) ![ipywidgets](https://img.shields.io/badge/ipywidgets-7075D1?style=for-the-badge) |




## ⚙️ Quick Start

```bash
# 1. Clone
git clone https://github.com/<your-handle>/behavior-patterns-and-anomalies.git
cd behavior-patterns-and-anomalies

# 2. (Optional) isolate env
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate

# 3. Fire up notebooks
jupyter lab  # or: jupyter notebook
````

Each notebook reads its data from `data/`—no extra downloads needed.

## 📈 Highlights

* **±8 % MAPE** on Instagram-reach forecasting using seasonal SARIMA
* **>92 % anomaly recall** on synthetic fraud dataset with Isolation Forest
* **Interactive COVID-19 dashboard** → rolling trends & geo heat-maps

See individual notebooks for full metrics and visuals.


## 🤝 Contributing

Got an optimisation idea, a new dataset, or a cool model tweak?

1. Fork → create a feature branch.
2. Commit with clear messages.
3. Open a Pull Request—describe *why* the change helps.

We review rapidement!


## 📄 License

**MIT**—use, fork, and remix freely.
Data files remain property of their original sources and are included for educational demonstration only.

### Maintainer

Syed Shabi-ul-Hassan • AI & Blockchain Enthusiast
[GitHub](https://github.com/shabihassan1) | [LinkedIn](https://www.linkedin.com/in/shabi-ul-hassan1)
