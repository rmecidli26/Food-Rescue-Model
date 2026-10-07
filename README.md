# 🍏 Food Rescue AI

Food Rescue AI is an intelligent web application designed to minimize food waste by predicting food spoilage risks using machine learning and providing analytical insights through interactive dashboards.

## 🚀 Features
- **ML-Powered Risk Prediction:** Predicts whether food items are safe or at risk based on inventory parameters using machine learning models.
- **Flask Backend:** A fast and lightweight web server handling user requests and rendering dynamic web pages.
- **Interactive Dashboards:** Visualizations and analytics for tracking food waste trends and inventory status.
- **Render Deployment:** Fully hosted and live on cloud infrastructure.

## 🛠️ Tech Stack
- **Backend:** Python, Flask, Gunicorn
- **Machine Learning:** Scikit-Learn, Pandas, NumPy, Torch, Ultralytics
- **Frontend:** HTML5, CSS3, Bootstrap
- **Deployment:** Render, Git & GitHub

## 📂 Project Structure
```text
food-rescue-ai/
│
├── app.py               # Main Flask application routes
├── model.py             # Machine learning prediction logic
├── requirements.txt     # Python dependencies
├── Procfile             # Gunicorn deployment configuration
├── static/              # CSS and static assets
└── templates/           # HTML templates (index, powerbi, etc.)
