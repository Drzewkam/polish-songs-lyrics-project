# Polish Songs Lyrics – Genre Classification Project 🎵

Project aimed at building a **classification model** that predicts the **musical genre** of a song based solely on its lyrics (in Polish).  
Currently contains data scraping and preprocessing modules; future plans include model training, evaluation, and sentiment-enhanced features.  

---

## 📄 What It Does

- Scrapes lyrics of Polish songs from **wywrota.pl**  
- Gathers artist genre data from **wikipedia.pl**  
- Preprocesses and cleans text data (tokenization, stopwords, normalization)  
- (Planned) Trains classification models to assign genre based on lyrics  
- (Future enhancement) Incorporates **sentiment scores** (via TextBlob) as additional features  

---

## 🧰 Technologies & Tools

- **Python 3.x**  
- Web scraping: `requests`, `BeautifulSoup`  
- Data manipulation: `pandas`  
- Natural Language Processing: tokenization, text cleaning  
- Sentiment analysis: **TextBlob** (for Polish)  
- (Future) scikit-learn / XGBoost / transformers for classification  
- Jupyter Notebooks for exploratory analysis  

---

## 🚀 Current Status & Roadmap

| Phase | Status | Upcoming Steps |
|-------|--------|----------------|
| Scraping & dataset collection | ✅ Done | Expand artists / languages |
| Data preprocessing & cleaning | ✅ In progress | More normalization, stemming/lemmatization |
| Model training & evaluation | ⬜ Planned | Build and test classification models |
| Sentiment / additional features | ⬜ Planned | Integrate sentiment scores, embeddings |
| Deployment / API | ⬜ Planned | Expose model prediction via web API |

---

## 📂 Project Structure
```
.
├── README.md
├── notebooks/
│ ├── Projekt_teksty.ipynb # scraping + preprocessing of lyrics
│ ├── Clustering_model_LYRICS.ipynb # exploratory clustering / modeling
│ └── genre_classifier.ipynb # (planned) genre classification model
├── data/
│ ├── all_lyrics.xlsx # collected dataset of Polish song lyrics
│ └── scraped_artists.csv # metadata about artists and genres
├── src/
│ ├── scraping_utils.py # helper functions for web scraping
│ ├── preprocessing.py # text cleaning and normalization
│ └── model_training.py # (planned) ML training pipeline
└── requirements.txt # dependencies
```
---

## 📥 How to Use / Run & Requirements

1. Clone this repository  
2. Install dependencies:
   ```bash
   pip install pandas requests beautifulsoup4 textblob
Run scraping notebook / script to collect lyrics and artist genre data

Preprocess and clean text data

(Future) Train classification models

---

## 🧑‍💻 Author & Contact
Kamil Drzewiecki
Areas of interest: NLP, Text Classification, Machine Learning
📧 [Your email] | 🐙 [GitHub link]
