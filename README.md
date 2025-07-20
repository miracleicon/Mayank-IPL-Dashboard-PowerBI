# 🏏 Mayank IPL Power BI Dashboard

An interactive Power BI dashboard that provides deep insights into **Indian Premier League (IPL)** statistics using real-time and historical data. This project leverages **Cricbuzz API** for live match data and visualizes team performance, player stats, and match outcomes in an intuitive and engaging way.

---

## 📊 Key Features

- 🏆 Team-wise performance overview  
- 🎯 Top Batsmen and Bowlers with tooltips  
- 📈 Win/Loss Trends over the years  
- 🗓️ Match-wise insights with filters (Year, Venue, Team)  
- 🔄 Live Data using Cricbuzz API  
- 📍 Venue-wise win distribution  
- ⌛ Toss Impact on match outcomes  
- 🧠 Interactive tooltip insights for batsmen and bowlers  
- 🎥 Point Table animated view

---

## 🖼️ Dashboard Screenshots

### 🏠 Home Page
![Home](https://github.com/miracleicon/Mayank-IPL-Dashboard-PowerBI/blob/main/Home.png)

### 📡 Live Matches View
![Live](https://github.com/miracleicon/Mayank-IPL-Dashboard-PowerBI/blob/main/Live.png)

### 🏏 Batsman Tooltip Insights
![Batsman Tooltip](https://github.com/miracleicon/Mayank-IPL-Dashboard-PowerBI/blob/main/Batsman_Tooltip.png)

### 🎯 Bowler Tooltip Insights
![Bowler Tooltip](https://github.com/miracleicon/Mayank-IPL-Dashboard-PowerBI/blob/main/Bowler_Tooltip.png)

---

## 🎥 Point Table Video Preview

https://github.com/miracleicon/Mayank-IPL-Dashboard-PowerBI/blob/main/Point-Table.mp4
---

## 📝 Report Document

A complete project report including:
- Dataset overview  
- API usage and setup  
- Dashboard insights explained  
- Business and analytical use cases

📄 [Click here to view the report](https://github.com/miracleicon/Mayank-IPL-Dashboard-PowerBI/blob/main/T20%20IPL%20Data%20Analysis_Synopsis.pdf)

---

## 📥 Cricbuzz API Integration Guide

### Python Script (RapidAPI)

```python
import requests, json

url = "https://cricbuzz-cricket.p.rapidapi.com/matches/v1/recent"
headers = {
    "X-RapidAPI-Key": "your_api_key_here",
    "X-RapidAPI-Host": "cricbuzz-cricket.p.rapidapi.com"
}
response = requests.get(url, headers=headers)
with open("live_matches.json", "w") as f:
    json.dump(response.json(), f, indent=4)
```

## 🧑‍💻 Author

**👨‍💻 Mayank Srivastav**  
🎓 B.Tech in CSE | Power BI, Data & Cloud Enthusiast  
🔗 [LinkedIn](https://www.linkedin.com/in/mayank-srivastav-477282291) 
