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

## 🧠 Key Findings

1. **Prevalent Topics**  
   Using LDA topic modeling, the dataset revealed dominant themes such as **Trump won!**, **Republican discourse - America, God & Musk**, **Democratic discourse - disappointment**, **Race, identity & election**, **Political parties & ideology**, and **Emotions & protest**.

2. **Temporal Dynamics**  
   Tweet volume significantly increased from **November 6th, 18:00** onwards, aligning with the announcement of key election outcomes. Certain topics (e.g., “Emotions & protest”, “Democratic discourse - disappointment”) spiked within specific time windows, reflecting news-driven attention.

3. **Sentiment Dynamics Across Topics**  
   63% of tweets in the topic **Republican discourse – America, God & Musk** are classified as positive, while 42% of tweets in **Democratic discourse – disappointment** are negative — the highest among all topics.

4. **User-level Topic Affiliation**  
   Highly active users (100+ tweets) were heavily focused on the **Emotions & Protest** topic, with a noticeable spike on November 7th at 12:00.

5. **Dashboard Interactivity**  
   The Power BI dashboard supports:
   - Filtering by **topic**, **user**, **time**, and **sentiment**
   - Visualization of **topic probability** and **tweet count dynamics**
   - Exploratory analysis across ~340K tweets


## 📂 Project Structure

```bash
us-election-twitter-analysis/
├── notebooks/                 → Jupyter notebook for preprocessing
├── screenshots/               → dashboard preview images
└── README.md                  → this file
```

## 📥 Download the Dashboard

You can download the full interactive Power BI dashboard (.pbix) here:

👉 [📊 Download PBIX on Google Drive](https://drive.google.com/file/d/14739ZMOAdyLmmDbU_bdMcwstfdiV3H4C/view?usp=sharing)

> Note: The file is larger than 100MB and cannot be hosted directly on GitHub.  
> Please open it in [Power BI Desktop](https://powerbi.microsoft.com/en-us/desktop/) to explore the full analysis.
