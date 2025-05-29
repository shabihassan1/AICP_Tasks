# 📊 AICP Tasks — Data Science Mini-Portfolio

A collection of eight self-contained Jupyter notebooks tackling real-world analytics and machine-learning problems—from Instagram reach forecasting to anomaly detection in financial transactions and COVID-19 spread analysis.

> **Goal:** demonstrate end-to-end data-science skills — EDA → feature engineering → modelling → evaluation → visual storytelling.


## 🗂️ Repository Structure

```

AICP\_Tasks-main/
│
├── \*.ipynb                     # Seven task notebooks (Task1 … Task7-8)
│   ├── COVID-19 Daily.xlsx
│   ├── Instagram-Reach.csv
│   ├── Queries.csv
│   ├── tips.csv
│   ├── transaction\_anomalies\_dataset.csv
│   ├── user\_profiles\_for\_ads.csv
│   └── userbehaviour.csv
└── README.md

````

*(CSV / XLSX files are already committed for convenience—no extra downloads needed.)*

## 🚀 Task Guide

| Notebook | Theme & Techniques | Quick Take |
|-----------|--------------------|-----------|
| **Task1_AICP.ipynb** | *Time-Series Forecasting* — ARIMA / SARIMA, seasonality plots | Predicts Instagram reach & engagement for content planning. |
| **Task2_AICP.ipynb** | *Unsupervised Segmentation* — K-Means, PCA | Clusters mobile-app users into actionable personas. |
| **Task3_AICP.ipynb** | *Customer Profiling* — RFM analysis, Hierarchical Clustering | Builds marketing segments from ad-targeting data. |
| **Task4_AICP.ipynb** | *Anomaly Detection* — Isolation Forest, DBSCAN | Flags fraudulent transactions in a synthetic banking dataset. |
| **Task5_AICP.ipynb** | *Search-Query Outlier Mining* — TF-IDF, cosine similarity | Identifies anomalous or spammy search queries. |
| **Task6_AICP.ipynb** | *Exploratory Data Analysis Sprint* | Hands-on drill: missing values, descriptive stats, visuals. |
| **Task 7-8_AICP.ipynb** | *Epidemiology Analytics* — Trend, choropleth, SIR hints | Visualises COVID-19 spread patterns & behavioural metrics. |

## 🛠️ Tech Stack

| Category    | Key Libraries |
|-------------|---------------|
| Core Data   | **pandas**, **NumPy**, **openpyxl** |
| Visuals     | **Matplotlib**, **Seaborn**, **Plotly** |
| ML / Stats  | **scikit-learn**, **statsmodels**, *SciPy* |
| Misc        | **JupyterLab / Notebook**, **PyPI** |

Python ≥ 3.9 recommended.


## ⚙️ Quick Start

```bash
# 1) Clone repo
git clone https://github.com/shabihassan1/AICP_Tasks.git
cd AICP_Tasks-main

# 2) (Optional) create & activate virtual env
python -m venv .venv
source .venv/bin/activate   # Windows: .venv\Scripts\activate

# 3) Launch notebooks
jupyter lab     # or: jupyter notebook
````

> **Tip:** Each notebook runs independently — open the one you need and execute top-to-bottom.


## 📈 Results & Insights

* 📉 **Forecast accuracy:** SARIMA ± 8 % MAPE on unseen Instagram data
* 🔍 **Anomaly recall:** Isolation Forest detects > 92 % of injected fraud cases
* 🦠 **COVID-19 dashboard:** interactive heat-maps & rolling-average plots for rapid situational awareness

*(Full metrics, charts, and discussion live inside each notebook.)*

## 🤝 Contributing

Found an issue or have a cool optimisation idea?

1. Fork → create a branch → commit changes.
2. Open a Pull Request – please describe **why** the change helps.
3. We’ll review ASAP!


## 📄 License

MIT — do whatever you like, just give credit.
Data files remain the property of their original sources; used here for educational purposes only.


### Maintainer

**Syed Shabi-ul-Hassan** · *AI & Blockchain enthusiast*
[GitHub](https://github.com/shabihassan1) • [LinkedIn](https://www.linkedin.com/in/shabi-ul-hassan1)
