# Weather App with Django

## 📌 Overview
A simple **Weather App** built using **Python Django**.  
The app fetches real-time weather data using an API and displays it for user-selected locations.

---

## 🚀 Features
- Search weather by city name.
- Display temperature, humidity, and weather conditions.
- Uses an external weather API (e.g., OpenWeatherMap).
- Clean and simple user interface.
- Error handling for incorrect city names.

---

## 🛠 Tech Stack
- **Backend**: Python (Django)
- **Frontend**: HTML, CSS, Bootstrap
- **API**: OpenWeatherMap API
- **Database**: SQLite (default)

## 📂 Project Setup
### 1. Clone the repository
git clone https://github.com/your-username/Weather-App-with-Python-Django.git
cd Weather-App-with-Python-Django
2. Create Virtual Environment
python -m venv env
source env/bin/activate   # Linux/macOS
env\Scripts\activate      # Windows
3. Install Requirements
pip install -r requirements.txt
4. Apply Migrations
python manage.py migrate
5. Get API Key
Sign up on OpenWeatherMap

Get an API key and add it to your project settings.

6. Run Server
python manage.py runserver
Open: http://127.0.0.1:8000


