---
```markdown
# 🇰🇪 Kenya Sentiment & Policy Analytics Dashboard  

[![Streamlit](https://img.shields.io/badge/Deployed%20on-Streamlit-blue)](https://kenya-sentiment.streamlit.app)
[![Python](https://img.shields.io/badge/Python-3.10+-yellow)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

> 🧠 AI-powered analytics dashboard visualizing **public sentiment and media trends in Kenya** — powered by **Streamlit**, **Google News**, and **TextBlob** for sentiment analysis.

---

## 🌍 Project Overview  

The **Kenya Sentiment & Policy Analytics Dashboard** provides a real-time, AI-driven look at how Kenyan news and public media reflect national sentiment on key social, political, and economic topics.  

It combines:
- 📰 **News scraping** (Google News)
- 🧠 **AI-powered sentiment analysis**
- 📊 **Interactive Streamlit visualizations**

---

## 🧩 Features  

✅ Real-time data collection from Google News  
✅ Sentiment analysis using `TextBlob`  
✅ Interactive dashboards (charts, filters, and summaries)  
✅ One-click data refresh inside Streamlit  
✅ Clean modular Python project structure  

---

## 🏗️ Project Structure  

```

kenya-sentiment-insights/
│
├── data/
│   ├── raw/                 # Unprocessed scraped data
│   └── processed/           # Cleaned and analyzed data
│
├── src/
│   ├── data_collection/     # Scripts for news scraping
│   │   └── scrape_news.py
│   ├── sentiment_analysis/  # Sentiment processing
│   │   └── analyze_sentiment.py
│   └── dashboard/           # Streamlit visualization
│       └── app.py
│
├── requirements.txt
├── README.md
└── .streamlit/
└── config.toml

````

---

## ⚙️ Installation & Setup  

### 🖥️ 1. Clone the repository  
```bash
git clone https://github.com/FrankMakori/kenya-sentiment-insights.git
cd kenya-sentiment-insights
````

### 🧱 2. Create a virtual environment

```bash
python -m venv .venv
.\.venv\Scripts\activate      # Windows
```

### 📦 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 📰 4. Collect news data

```bash
python src/data_collection/scrape_news.py
```

### 🧠 5. Analyze sentiment

```bash
python src/sentiment_analysis/analyze_sentiment.py
```

### 📊 6. Run the dashboard

```bash
streamlit run src/dashboard/app.py
```

---

## 🚀 Live Demo

> 🌐 [View Dashboard on Streamlit](https://kenya-sentiment.streamlit.app)
> 💻 [GitHub Repository](https://github.com/FrankMakori/kenya-sentiment-insights)

---

## 📈 Example Visualization

Below are sample outputs generated from sentiment analysis:

* 📉 **Sentiment trend over time**
* 🧭 **Most discussed topics**
* 🔍 **Top positive & negative headlines**

![Kenya Sentiment Dashboard Preview](A_dashboard_titled_"🇰🇪_Kenya_Sentiment_&_Policy_An.png)

---

## 🤖 Tech Stack

| Layer              | Technology                     |
| ------------------ | ------------------------------ |
| Data Collection    | Google News API, BeautifulSoup |
| Sentiment Analysis | TextBlob                       |
| Dashboard          | Streamlit                      |
| Language           | Python 3.10+                   |
| Version Control    | Git & GitHub                   |

---

## 🔁 Refresh Feature

Click the **"🔄 Refresh Data"** button on the dashboard to fetch the latest news and automatically update charts in real time.

---

## 🧠 Future Enhancements

* Integrate Twitter/X data for broader sentiment scope
* Add topic classification (e.g., economy, politics, education)
* Deploy automatic daily refresh using Streamlit Cloud

---

## 📜 License

This project is licensed under the **MIT License** — you’re free to use, modify, and share with attribution.

---

## 👨‍💻 Author

**Frank Makori**
[💼 LinkedIn](https://www.linkedin.com/in/frankmakori) | [🐙 GitHub](https://github.com/FrankMakori)

> “Turning Kenyan data into intelligent insights — through ethical AI.” 🇰🇪

---

````

---

### ✅ Next Steps

1. Save this as `README.md` in your project root.  
2. Commit and push it:
   ```bash
   git add README.md
   git commit -m "Add professional README"
   git push
````

3. Then, post the **project link + dashboard link** on **LinkedIn** with a short caption like:

   > “Proud to share my latest AI project — an 🇰🇪 *AI-Powered Kenya Sentiment & Policy Dashboard* built with Python & Streamlit. Visualizing real-time media sentiment for better policy insights. 🚀”

---
