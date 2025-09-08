# Python-YouTube-Data-Analysis-Extract-Analyze-Visualize
YouTube Data API v3 project to fetch channel &amp; video statistics with Exploratory Data Analysis using Pandas and Seaborn.

# 📊 YouTube Channel Analytics & EDA using YouTube Data API

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)  
[![YouTube API](https://img.shields.io/badge/YouTube%20API-v3-red)](https://developers.google.com/youtube/v3)  
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)](https://pandas.pydata.org/)  
[![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-orange)](https://seaborn.pydata.org/)  
[![Matplotlib](https://img.shields.io/badge/Matplotlib-Charts-yellow)](https://matplotlib.org/)  

This project leverages the YouTube Data API v3 to fetch channel statistics, video details, and perform Exploratory Data Analysis (EDA) on popular YouTube channels. The analysis includes channel comparisons, top-performing videos, and monthly upload patterns, visualized with Seaborn and Matplotlib.

## 🚀 Features
- 📈 Fetch channel-level statistics (subscribers, views, video count).  
- 🎥 Extract all video IDs from a channel’s **uploads playlist**.  
- 📊 Retrieve video-level details (title, publish date, views, likes, comments).  
- 🐼 Clean & structure data using **Pandas**.  
- 🎨 Generate insights with **Seaborn visualizations**:  
  - Channel comparisons  
  - Top 10 videos  
  - Monthly upload trends  
- 💾 Export results to **CSV** for further use. 

---

## 🛠️ Tech Stack
- **Python 3.x**  
- **YouTube Data API v3** (via `googleapiclient.discovery`)  
- **Pandas** – Data wrangling  
- **Seaborn / Matplotlib** – Visualization  

---

## 📂 Project Structure
├── YouTube_EDA.ipynb        # Jupyter notebook with full workflow
├── Video_Details(SonySAB).csv  # Exported dataset for Sony SAB channel
├── README.md                # Project documentation


---

## ⚙️ Setup & Installation
1. Clone the repository:
   ```
   git clone https://github.com/your-username/youtube-eda.git
   cd youtube-eda
   ```
2. Install dependencies:
  ```
  pip install pandas seaborn google-api-python-client matplotlib
  ```
3. Get your YouTube Data API key from Google Cloud Console.
. Replace the placeholder API key in the script: api_key = "YOUR_API_KEY"

📊 Analysis Highlights
🔹 Channel Statistics
Comparison of subscribers, views, and total uploaded videos for multiple channels:
Sony SAB
Lionsgate Movies
Marvel Entertainment
DC

Sony Pictures Entertainment
🔹 Top 10 Most Viewed Videos (Sony SAB)
Bar chart of the most popular videos ranked by views.

🔹 Monthly Upload Pattern
Distribution of uploaded videos across months of the year.

📈 Sample Visualizations
Subscribers per channel
Views per channel
Top 10 videos by views
Monthly video uploads
(Plots generated with Seaborn)

📑 Exported Data
Video_Details(SonySAB).csv → Clean dataset containing Sony SAB video details (views, likes, comments, publish date, etc.).

🔮 Future Improvements
Add Sentiment Analysis on video comments.
Automate data refresh with scheduled scripts.
Build a dashboard (Streamlit/Plotly Dash).
Extend analysis to more YouTube channels.

🙌 Acknowledgements
YouTube Data API v3
Pandas
Seaborn
