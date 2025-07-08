# NetraAI – AI-Powered OSINT Mood Profiler for India
NetraAI is an AI-based Open-Source Intelligence (OSINT) platform that turns public data into structured insights like sentiment mood maps, entity graphs, and risk scores — ethically built for India.

## 💡 Features
- 🔍 Name/Handle Search
- 📊 Mood Sentiment Timeline
- ⚠️ Risk/Trust Score
- 🕸 Entity Recognition (spaCy)
- ☁️ Keyword Cloud
- 🔗 Relationship Graph (via PyVis)
- 📄 Downloadable Text Report
- 🌌 Futuristic UI with background

## ⚙️ Tech Stack
| Layer       | Tools |
|-------------|-------|
| NLP         | spaCy, TextBlob |
| Dashboard   | Streamlit |
| Graph       | NetworkX, PyVis |
| Visualization | Matplotlib |
| Data        | Sample Tweets (for demo) |

## 🔧 Setup Instructions
```bash
pip install -r requirements.txt
python -m spacy download en_core_web_sm
streamlit run app.py
