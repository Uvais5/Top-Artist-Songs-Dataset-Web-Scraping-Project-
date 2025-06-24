# 🎵 Song Lyrics Scraper & NLP Dataset (2017–2024)

This project scrapes and compiles a dataset of song lyrics by top-charting artists between **2017 and 2024**. It includes artist names, song titles, and cleaned song lyrics for Natural Language Processing (NLP) and music-related machine learning tasks.

---

## 🧠 Use Cases

- Sentiment analysis  
- Topic modeling  
- Song recommendation engines  
- Text classification  
- Lyric generation / fine-tuning LLMs  
- Emotion detection in music

---

## 🗂️ Dataset Overview

| Column Name | Description |
|-------------|-------------|
| `artist`    | Artist or band name |
| `songs`     | Title of the song |
| `lyrics`    | Full song lyrics (cleaned) |

---

## 📦 Files Included

- `azlyrics_artists_links.csv` — Raw artist list with song page links  
- `filtered_artist_links.csv` — Top artist list matched with valid URLs  
- `song_links_&_name.csv` — Song titles and corresponding URLs  
- `final_lyrics_dataset.csv` — Final dataset with lyrics

---

## 🛠️ Tools & Libraries

- `requests`, `BeautifulSoup` — Web scraping  
- `pandas` — Data manipulation  
- `lyricsgenius` — Genius API (backup lyrics source)  
- `re`, `time` — Text and timing utilities

---

## 🔐 Disclaimer

This project is for **educational and research purposes only**.

> All song lyrics remain the property of their respective copyright holders.  
> No commercial use, redistribution, or hosting of copyrighted content is permitted.

---

## 🚀 Getting Started

1. Clone the repo  
2. Run each notebook step by step  
3. [Optional] Add your Genius API key for backup fetching  
4. Save and export your final dataset

---

## 📌 Notes

- Lyrics are fetched from publicly available sources
- Only top global artists from **2017 to 2024** are included
- Older songs were filtered out to focus on modern content

---

## 📣 Author

**Uvais Saifi**  
_Data Scientist | Python Developer | AI Researcher_

---

