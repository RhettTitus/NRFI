# NRFI (No Run First Inning) Model

This app automatically fetches MLB data, ranks NRFI probabilities, and discovers high-performing trends.

## Features
- Daily NRFI model output
- Trend discovery by pitcher stats, weather, team, and more
- Auto-detection of NRFI result from live game data
- Streamlit dashboard with manual refresh

## How to Run Locally
1. Clone this repo:
```
git clone https://github.com/your-username/nrfi-model.git
cd nrfi-model
```

2. Install dependencies:
```
pip install -r requirements.txt
```

3. Run the app:
```
streamlit run app.py
```

## File Structure
```
app.py                   # Streamlit app
main.py                  # Model pipeline (you'll provide this)
utils/
  ├── game_results.py
  └── weather.py
output/
  ├── historical_nrfi.csv
  └── daily_nrfi_report.csv
```

## Deployment
You can deploy this app to [Streamlit Cloud](https://share.streamlit.io) by connecting your GitHub repo and selecting `app.py` as the entry point.

---
Built with 💥 by Mr. Ohtani & ChatGPT.
