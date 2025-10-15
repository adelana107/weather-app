# 🌦️ Classy Weather

Classy Weather is a simple and elegant React weather app built with class components.  
It lets users search for any city and displays a 7-day forecast using the **Open-Meteo API**.

---

## ✨ Features

- 🌍 Search weather by city name  
- 🧭 Automatically fetches geographic coordinates via **Open-Meteo Geocoding API**  
- 🌤 Displays daily max/min temperature and weather icons  
- 💾 Saves your last searched location using **localStorage**  
- ⚡ Built entirely with **React class components**  

---

## 🛠️ Tech Stack

- **React** (Class Components)
- **Open-Meteo API**
- **JavaScript (ES6+)**
- **CSS**

---

## 🚀 Getting Started

### 1️⃣ Clone this repository
```bash
git clone https://github.com/<your-username>/classy-weather.git
cd classy-weather
2️⃣ Install dependencies
bash
Copy code
npm install
3️⃣ Start the app
bash
Copy code
npm start
App will run at http://localhost:3000

🌐 APIs Used
Geocoding API:
https://geocoding-api.open-meteo.com/v1/search?name={city}

Weather Forecast API:
https://api.open-meteo.com/v1/forecast?latitude={lat}&longitude={lon}&timezone={tz}&daily=weathercode,temperature_2m_max,temperature_2m_min

🧩 Components Overview
Component	Purpose
App	Manages state, API calls, and renders main layout
Input	Handles user input for city search
Weather	Displays forecast data
Day	Renders a single day's weather (icon + temps)

🧠 Learning Highlights
This project demonstrates:

Using React class components instead of hooks

Handling async API calls in class components

Using localStorage to persist user preferences

Clean and modular component design

📸 Preview
(Optional: Add a screenshot here)

🏗️ Author
Developed by Adelana Oluwafunmibi
Built with ❤️ using React
