# Smart Warehousing for Healthcare Supply Chain

This project explores the use of **Machine Learning (ML)** and **Natural Language Processing (NLP)** to improve **vaccine supply chain management** in the healthcare sector. The work was conducted as part of a B.Tech Exploratory Project at IIT (BHU) Varanasi under the guidance of Prof. Cherian Samuel.

## 🧠 Project Motivation

The COVID-19 pandemic highlighted the critical importance of efficient vaccine distribution. However, global vaccination efforts have been hampered by issues like poor demand forecasting, supply chain bottlenecks, and public skepticism. Our project addresses these problems using:

- **Time Series Forecasting** to predict vaccine demand.
- **Sentiment Analysis** to understand public perception.
- **Smart warehousing insights** for better supply chain decisions.

## 🔍 Problem Statement

An inefficient vaccine supply chain leads to:
- Wastage due to overproduction.
- Shortages due to poor forecasting.
- Delays in vaccine delivery.
- Poor public trust and uptake.

This project aims to build a **data-driven, ML-powered smart warehousing system** that:
- Predicts vaccine demand more accurately.
- Gauges public sentiment from social media.
- Informs warehousing and distribution strategies.

---

## 📊 Modules Overview

### 1. **Time Series Forecasting**
Used historical vaccination data to predict future demand using:
- **Prophet** (Facebook's forecasting model)
- Evaluated on per-location basis with confidence intervals.
- Applied logarithmic transformations for variance stability.

> 📈 Result: Achieved consistent 14-day forecasts across regions, aiding in distribution planning.

---

### 2. **Sentiment Analysis**
Collected tweets related to major COVID-19 vaccines using **Tweepy** and performed sentiment classification using:

- **NLTK + TextBlob**  
  → Basic polarity-based sentiment scoring.

- **VADER Sentiment**  
  → Rule-based, suitable for informal social media text.

- **BERT Transformer**  
  → State-of-the-art contextual sentiment analysis using HuggingFace Transformers.

> 🧾 Insight: Most tweets were **neutral**, but **positive sentiments** outnumbered negative ones significantly, showing growing public trust.

---

## 🧰 Technologies Used

- **Python**
- **Pandas, NumPy, Matplotlib, Seaborn**
- **NLTK**, **VADER**, **TextBlob**, **Transformers (HuggingFace)**
- **Facebook Prophet**


---

## 🔄 How It Works

1. **Data Collection**
   - Tweets on vaccines gathered via Tweepy.
   - Historical vaccination rates from public datasets.

2. **Data Preprocessing**
   - Cleaned tweets using regex and stopwords removal.
   - Handled missing values in time series data.

3. **Analysis & Forecasting**
   - Applied Prophet for forecasting vaccination trends.
   - Ran sentiment models on tweets and visualized trends.

4. **Integration for Smart Warehousing**
   - Forecasted demand informs stock planning.
   - Sentiment trends guide outreach and awareness efforts.

---

## 📈 Sample Results

- 📊 Daily sentiment trends over time
- 📉 Word clouds for positive, neutral, negative tweets
- 📆 Forecast graphs per region with upper and lower confidence bounds

(Visuals are available in the `reports/` folder)

---

## 🧪 Future Work

- Integration with real-time warehouse management systems (WMS)
- Expand to broader healthcare logistics beyond vaccines
- Include multilingual sentiment analysis
- Real-time dashboards for stakeholders

---

## 👨‍💻 Contributors

- **Parth Pipraiya**  
- **Prajjwal Bajpai**  
- **Yashvardhansinh Rayjada**  
**Guided by:** Prof. Cherian Samuel

---

## 📜 License

This project is for academic and research purposes only. Please contact us for collaboration or permission to reuse components.
