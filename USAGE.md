# 🇰🇪 Kenya Sentiment & Policy Analytics Dashboard — User Guide

Welcome to the **Kenya Sentiment & Policy Analytics Dashboard**!
This tool uses **AI-powered sentiment analysis** to explore and visualize Kenyan news trends, public opinion, and national issues.

---

## 🧩 1. Clone or Download the Project

**Option A – Using Git:**

```bash
git clone https://github.com/FrankMakori/kenya-sentiment-insights.git
cd kenya-sentiment-insights
```

**Option B – Download ZIP:**
Go to your GitHub page → click **“Code” → “Download ZIP”** → extract it.

---

## 🧱 2. Create a Virtual Environment

```bash
python -m venv .venv
```

Then activate it:

**Windows:**

```bash
.venv\Scripts\activate
```

**Mac/Linux:**

```bash
source .venv/bin/activate
```

---

## 📦 3. Install Dependencies

Install all the required Python libraries:

```bash
pip install -r requirements.txt
```

---

## 📰 4. Fetch & Analyze News Data

Fetch Kenyan news from Google News and analyze it for sentiment:

```bash
python src/data_collection/scrape_news.py
python src/data_analysis/analyze_sentiment.py
```

This will generate:

```
data/processed/sentiment_summary.csv
```

---

## 📊 5. Run the Dashboard

Launch the Streamlit dashboard:

```bash
streamlit run src/dashboard/app.py
```

Then open the link shown in your terminal — usually:

👉 [http://localhost:8501](http://localhost:8501)

---

## 🔁 6. Refresh Data (Optional)

Once the dashboard is open, click **“🔄 Refresh Data”** to fetch and analyze the latest Kenyan news.

---

## 📈 7. Expected Output

You’ll see:

* **Bar chart** of Positive / Neutral / Negative sentiment
* **Line trend** showing sentiment over time
* **Word frequency cloud** (most common terms in headlines)
* **Table** summarizing each article analyzed

---

## 💬 Feedback and Contributions

Found a bug or want to suggest new features?
Open an **Issue** or **Pull Request** on GitHub:

🔗 [https://github.com/FrankMakori/kenya-sentiment-insights](https://github.com/FrankMakori/kenya-sentiment-insights)

---

## 👏 Credits

Created by **Frank Makori**
BSIT Student | Data & AI Enthusiast
🚀 Empowering data-driven insights for Kenyan development

---
