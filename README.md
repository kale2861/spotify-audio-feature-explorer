# spotify-audio-feature-explorer
Analyze your top tracks with Spotify API and Python
# 🎧 Spotify Audio Feature Explorer

This project uses the Spotify Web API to analyze your top tracks and explore audio features like **danceability**, **energy**, **valence**, and **tempo**. It’s built with **Python**, **Spotipy**, and **Google Colab**, and includes detailed visualizations and error handling.

---

## 🚀 Features

- 🔐 Securely connect to your personal Spotify account
- 🎵 Fetch your top 5 most played tracks
- 📊 Analyze audio features (energy, danceability, valence, tempo)
- 🧱 Clean code with batch processing and exception handling
- 💾 Export to CSV and visualize with Matplotlib & Seaborn
- ✅ Google Colab compatible — no local setup required

---

## 🧠 Audio Features Explained

| Feature       | Description                                         |
|---------------|-----------------------------------------------------|
| Danceability  | How suitable a track is for dancing (0.0–1.0)       |
| Energy        | Intensity and activity of a track                   |
| Valence       | Musical positivity (happy = 1.0, sad = 0.0)         |
| Tempo         | Speed of the song in beats per minute (BPM)         |

---

## 📦 Tech Stack

- Python 3
- Spotipy (Spotify API wrapper)
- Pandas
- Matplotlib + Seaborn
- Google Colab (or Jupyter Notebook)

---

## 🛠️ Setup Instructions

### 1. Create a Spotify Developer App

- Go to [Spotify Developer Dashboard](https://developer.spotify.com/dashboard)
- Create an app
- Set **Redirect URI** to:
- - Copy your **Client ID** and **Client Secret**

---

### 2. Run the Notebook

Use [Google Colab](https://colab.research.google.com/) or Jupyter, then follow these steps:

1. Paste your credentials
2. Run the code blocks in order
3. Go to the printed authorization URL and approve
4. Paste the code from the redirected link
5. View your results!

---

## 🧪 Sample Output

| Track           | Danceability | Energy | Valence | Tempo |
|----------------|--------------|--------|---------|-------|
| Song A         | 0.85         | 0.78   | 0.60    | 122   |
| Song B         | 0.67         | 0.88   | 0.45    | 140   |



---

## ❗ Common Errors & Fixes

| Error Message                                | Meaning                           | Fix |
|---------------------------------------------|-----------------------------------|-----|
| `403 Forbidden`                              | Bad or expired access token       | Regenerate token using fresh auth code |
| `⚠️ Spotify API returned no audio features`  | Track IDs may be invalid or private | Try another Spotify account |
| `🛑 Cannot create DataFrame`                 | No data retrieved from API        | Ensure top tracks were fetched correctly |

---
## 🚧 Project Status: In Development

This app is under active development. The Spotify get feature API is deprecated
