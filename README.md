# ⚽ Flask Live Football Scores App

A simple and responsive Flask web app that fetches **live football match scores** using the [Football-Data.org API](https://www.football-data.org/).  
This project demonstrates how to integrate APIs into a Flask application to display real-time data dynamically.

---

## 🚀 Features
- Fetches **live football match updates** using Football-Data.org API.
- Displays **team names, scores, and match status** in a clean web interface.
- Organized **Flask routes and templates** for modular development.
- Simple, beginner-friendly, and extendable for advanced use.

---

## 🧠 Tech Stack
- **Python 3.12+**
- **Flask** (Web framework)
- **Requests** (HTTP library)
- **HTML / Jinja2** (Templates)
- **Football-Data.org API**

---

## 📂 Project Structure
coursera-flask-demo/
│
├── app.py # Main Flask application
├── templates/
│ ├── index.html # Home page
│ └── scores.html # Live scores page
├── venv/ # Virtual environment (ignored by Git)
└── .gitignore


---

## ⚙️ Setup & Installation

1. **Clone this repository:**
   git clone https://github.com/sangoyapi/flask-live-scores.git
   cd flask-live-scores

python -m venv venv
venv\Scripts\activate   # On Windows
# source venv/bin/activate  # On Mac/Linux

pip install Flask requests schedule

api_key = "YOUR_API_KEY"

python app.py

🖼️ Demo

Example Output:

⚽ Live Soccer Scores
Manchester United vs Chelsea FC
Score: 2 - 1
Status: LIVE

📡 API Reference

Base URL: https://api.football-data.org/v4/matches

You’ll need a free API key from Football-Data.org
.
Use the key in your HTTP request headers:

headers = {'X-Auth-Token': 'your_api_key_here'}

🧩 Future Improvements

Add team logos and competition filters.

Include match schedules or past results.

Integrate a refresh timer for auto-updates.

Deploy to Render, Railway, or Vercel.

👨‍💻 Author

Sango Yapi
Frontend & Python Developer
📍 Johannesburg, South Africa
🔗 LinkedIn
 • GitHub