# 🗳️ US Election 2024 — Twitter Topic Dashboard

📊 Interactive dashboard analyzing over **340,000 tweets** related to the 2024 US Presidential Election using topic modeling, sentiment analysis, and temporal visualization.

---

## 🔍 Project Overview

This project covers:

- ✅ **LDA topic modeling** on political tweets
- ✅ **Hourly breakdown** of topic volume and user activity
- ✅ **Per-user topic tracking and heatmaps**
- ✅ **Sentiment analysis** using VADER
- ✅ Full pipeline: from raw tweets → to processed data → to Power BI dashboard

---

## 📆 Data Source

- Dataset: [USC X 24 US Election Twitter Dataset](https://github.com/sinking8/usc-x-24-us-election)
- Period: **November 3–7, 2024**  
- Raw tweet count: **~340,000 tweets**

---

## ⚙️ Pipeline & Notebooks

- `notebooks/preprocess_tweets.ipynb` — full pipeline including:
  - filtering tweets by date
  - cleaning, lemmatization
  - language filtering
  - sentiment scoring (VADER)
  - topic modeling (LDA)
  - merging results for Power BI

---

## 📂 Project Structure

```bash
us-election-twitter-analysis/
├── dashboards/                → Power BI `.pbix` file
├── notebooks/                 → Jupyter notebook for preprocessing
├── data/                      → (optional) CSV or JSON files
├── screenshots/               → dashboard preview images
└── README.md                  → this file


## 📥 Download the Dashboard

You can download the full interactive Power BI dashboard (.pbix) here:

👉 [📊 Download PBIX on Google Drive](https://drive.google.com/file/d/14739ZMOAdyLmmDbU_bdMcwstfdiV3H4C/view?usp=sharing)

> Note: The file is larger than 100MB and cannot be hosted directly on GitHub.  
> Please open it in [Power BI Desktop](https://powerbi.microsoft.com/en-us/desktop/) to explore the full analysis.
