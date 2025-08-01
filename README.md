# 📝 Text Sentiment Analyzer

A simple, full-stack web app to detect the sentiment of any text snippet. Built with React (frontend) and Flask + TextBlob (backend).

---

## 🚦 Live Demo

> [Add your live site link here after deploying!]

---

## ✨ Features

- Paste or type any text and analyze its sentiment (Positive, Negative, Neutral)
- Instant visual feedback with color coding and emoji
- Shows the sentiment score for deeper analysis
- Clean, responsive UI
- Fast and beginner-friendly tech stack!

---

## 🛠️ Tech Stack

| Frontend    | Backend          | NLP Library    |
|-------------|------------------|---------------|
| React (JSX) | Flask (Python)   | TextBlob      |

---

## ⚙️ How It Works

1. User enters text and clicks "Analyze Sentiment".
2. Frontend sends a POST API request with the text to the backend.
3. Backend uses TextBlob for sentiment analysis (score from -1 to 1).
4. Result (“Positive”, “Negative”, “Neutral” + score) is sent back and displayed.

---

## 🖥️ Quick Start

### **Backend Setup**
git clone https://github.com/YOUR_USERNAME/sentiment-backend.git
cd sentiment-backend
python -m venv venv
source venv/bin/activate # (Windows: venv\Scripts\activate)
pip install -r requirements.txt # Or pip install flask flask-cors textblob
python -m textblob.download_corpora
python app.py


### **Frontend Setup**
git clone https://github.com/YOUR_USERNAME/sentiment-frontend.git
cd sentiment-frontend
npm install
npm start

- The app runs at [http://localhost:3000](http://localhost:3000)  
  Ensure backend is running at `http://127.0.0.1:5000`

---

## 📦 Example Response

{
"sentiment": "Positive",
"score": 0.73
}


---

## 🚀 Deployment

- **Frontend:** Deploy to Vercel or Netlify (just drag-and-drop your `build` folder after `npm run build`).
- **Backend:** Deploy to Render, Railway, or Heroku.
- Update the frontend API URL to match your backend’s deployed URL.
- Link both in the README!

---