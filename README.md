# 📈 Stock Price Prediction Web App (with Prophet)

![Stock Prediction](https://github.com/Uvais5/Stock_Price_Prediction_app/blob/main/stock.png)

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)](https://www.python.org/)
[![Streamlit](https://img.shields.io/badge/Built%20with-Streamlit-orange?logo=streamlit)](https://streamlit.io/)
[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Kaggle Dataset](https://img.shields.io/badge/Kaggle-lyrics--dataset-blue?logo=kaggle)](https://www.kaggle.com/)

---

## 🔍 Overview

This is an end-to-end data science project built with **Facebook Prophet** and **Streamlit** to help users predict stock prices using past historical data.

It also integrates a **separate web scraping pipeline** that collects song lyrics from top artists (2017–2024) and prepares a powerful dataset for **Natural Language Processing** use cases — hosted on **Kaggle**.

---

## 🎯 Use Case & Purpose

- 📊 Learn **time series forecasting** using Prophet
- 💹 Visualize and predict **stock trends**
- 🤖 Scrape and preprocess **lyrics for NLP tasks**
- 🎓 Ideal for **learning**, **demonstration**, or **hackathons**

---

## 🚀 Live Demos

- 📈 [Stock Price Predictor Web App](https://share.streamlit.io/uvais5/stock_price_prediction_app/main/app.py)
- 📦 [Kaggle Lyrics Dataset (2017–2024)](https://www.kaggle.com/uvais5/song-lyrics-nlp-dataset)  
  ![Lyrics Dataset Banner](https://github.com/Uvais5/Stock_Price_Prediction_app/blob/main/kaggle_lyrics_banner.png)

---

## 🧠 Web Scraping: Song Lyrics Dataset

### 🎵 Song Lyrics Scraper & NLP Dataset (2017–2024)

This dataset includes artist names, song titles, and cleaned song lyrics collected from multiple public sources for NLP and machine learning projects.

### 📚 Use Cases
- Sentiment analysis  
- Emotion detection in music  
- Music genre classification  
- Text classification  
- Training LLMs on lyric data

### 📁 Files Included
| File                        | Description                            |
|-----------------------------|----------------------------------------|
| `azlyrics_artists_links.csv`     | Raw artist list and links             |
| `filtered_artist_links.csv`      | Cleaned artist list with valid URLs   |
| `song_links_&_name.csv`         | All song names and respective URLs    |
| `final_lyrics_dataset.csv`      | Cleaned lyrics for ML training        |

### 🔐 Disclaimer
This dataset is provided for **educational and non-commercial use only**. Lyrics belong to their original copyright holders.

---

## 🛠 Tech Stack

| Tool       | Role                               |
|------------|------------------------------------|
| Python     | Base language                      |
| Prophet    | Time series forecasting            |
| Streamlit  | Web app UI                         |
| BeautifulSoup | Web scraping engine             |
| LyricsGenius | Genius API client                |
| Pandas     | Data processing                    |
| Plotly     | Interactive charts                 |

---

## 🔧 Installation

```bash
# Clone t
