NewsNinja - Stealthy News Aggregator

Your personal news ninja that silently gathers headlines and Reddit reactions, then delivers audio briefings straight to your ears. *No scroll, just soul.*

---
FEATURES
- 🗞️ Scrape premium news websites (bypassing paywalls)
- 🕵️♂️ Extract live Reddit reactions (even from JS-heavy threads)
- 🔊 AI-powered audio summaries (text-to-speech with ElevenLabs)
- ⚡ Real-time updates (thanks to Bright Data's MCP magic)

---
PREREQUISITES
- Python 3.9+
- Bright Data account (https://brightdata.com)
- ElevenLabs account (https://elevenlabs.io)



---
PROJECT STRUCTURE
```
.
├── frontend.py          # Streamlit UI
├── backend.py           # API & data processing  
├── utils.py             # UTILS  
├── news_scraper.py      # News Scraper  
├── reddit_scraper.py    # Reddit Scraper  
├── models.py            # Pydantic model
├── Pipfile              # Dependency scroll
├── .env.example         # Secret map template
└── requirements.txt     # Alternative dependency list
```

