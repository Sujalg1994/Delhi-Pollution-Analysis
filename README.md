# 🌫️ Delhi Air Pollution — Exploratory Data Analysis

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

---

## 📌 Project Overview

Delhi consistently ranks among the most polluted cities in the world, with air quality posing serious public health risks to its 30+ million residents. This project conducts a comprehensive **Exploratory Data Analysis (EDA)** of Delhi's air pollution data, uncovering seasonal patterns, pollutant trends, and AQI distribution to support data-driven environmental decision-making.

---

## 🎯 Objectives

- Analyse historical trends in key air pollutants (PM2.5, PM10, NO₂, SO₂, CO, O₃)
- Identify seasonal and temporal patterns in Delhi's AQI
- Visualise pollutant distributions and correlations
- Highlight the most critical pollution periods and contributing factors

---

## 📂 Repository Structure

```
Delhi-Pollution-Analysis/
│
├── Delhi Airpollution.csv          # Raw dataset
├── delhi_pollution_analysis.ipynb  # Main analysis notebook
└── README.md                       # Project documentation
```

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| Python | Core programming language |
| Pandas | Data cleaning & manipulation |
| Matplotlib | Static visualisations |
| Seaborn | Statistical plots & heatmaps |
| Jupyter Notebook | Interactive analysis environment |

---

## 📊 Key Analyses Performed

- **Data Cleaning** — Handling missing values, outlier detection, dtype correction
- **Univariate Analysis** — Distribution of individual pollutants (PM2.5, PM10, NO₂, etc.)
- **Temporal Trends** — Monthly and seasonal AQI variation across years
- **Correlation Analysis** — Heatmap of inter-pollutant relationships
- **AQI Classification** — Breakdown of Good / Moderate / Unhealthy / Hazardous days
- **Pollutant Comparison** — Bar charts and boxplots comparing pollutant levels across periods

---

## 💡 Key Findings

- PM2.5 and PM10 spike significantly during **winter months (Oct–Jan)** due to stubble burning and low wind dispersion
- AQI levels in Delhi frequently breach the **"Hazardous"** threshold (AQI > 300) during November–December
- Strong positive correlation observed between PM2.5 and PM10, indicating shared emission sources
- Summer months show relatively lower pollutant levels, driven by monsoon-related dispersion

---

## 📁 Dataset

The dataset (`Delhi Airpollution.csv`) contains historical air quality readings for Delhi including concentrations of PM2.5, PM10, NO₂, SO₂, CO, O₃, and computed AQI values.

---

## 🚀 How to Run

1. Clone the repository:
```bash
git clone https://github.com/Sujalg1994/Delhi-Pollution-Analysis.git
```

2. Install dependencies:
```bash
pip install pandas matplotlib seaborn jupyter
```

3. Launch the notebook:
```bash
jupyter notebook delhi_pollution_analysis.ipynb
```

---

## 👤 Author

**Sanket C Sakhare**
MSc Business Analytics — University of Birmingham
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sanket-sakhare-8a90b0258/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white)](https://github.com/Sujalg1994)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
