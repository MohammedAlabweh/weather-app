🌦️ Weather App

A modern weather forecast web application built using HTML, CSS, and JavaScript, powered by the OpenWeatherMap API.
The application allows users to search for any city and view real-time weather information along with a 5-day forecast, presented in a clean glassmorphism-inspired interface.

⸻

✨ Features
	•	🔍 Search weather by city name
	•	🌡️ Display current temperature in Celsius
	•	☁️ Show current weather condition (Clear, Clouds, Rain, etc.)
	•	💧 Display humidity percentage
	•	🌬️ Display wind speed
	•	📅 Show current date
	•	📆 5-day weather forecast (midday data)
	•	🖼️ Dynamic weather icons based on conditions
	•	🧊 Glassmorphism UI design
	•	❌ Error handling for invalid city searches

⸻

🛠️ Tech Stack
	•	HTML5 – Application structure
	•	CSS3 – Styling, glassmorphism effects, layout
	•	JavaScript (ES6+) – Logic, DOM manipulation, API integration
	•	OpenWeatherMap API – Weather and forecast data

⸻

📸 UI Overview

The application has three main states:
	1.	Search City
Initial screen prompting the user to search for a city.
	2.	Weather Information
Displays current weather details and a 5-day forecast.
	3.	Not Found
Displayed when a city search returns no results.

⸻

🔑 API Usage

This project uses the OpenWeatherMap API.

Current Weather Endpoint

https://api.openweathermap.org/data/2.5/weather

5-Day Forecast Endpoint

https://api.openweathermap.org/data/2.5/forecast

Weather data is fetched using the JavaScript fetch() API and rendered dynamically.

⸻

⚙️ Setup & Run Locally

1️⃣ Clone the repository

git clone https://github.com/your-username/weather-app.git

2️⃣ Navigate into the project directory

cd weather-app

3️⃣ Add your OpenWeatherMap API key

Open script.js and replace:

const apiKey = 'YOUR_OPENWEATHER_API_KEY';

4️⃣ Run the application

Open index.html directly in your browser.
No server or build tools are required.

⸻

📁 Project Structure

weather-app/
├── index.html
├── style.css
├── script.js
├── assets/
│   ├── bg.jpg
│   ├── message/
│   │   ├── search-city.png
│   │   └── not-found.png
│   └── weather/
│       ├── clear.svg
│       ├── clouds.svg
│       ├── rain.svg
│       ├── snow.svg
│       ├── thunderstorm.svg
│       └── atmosphere.svg

⸻

🚀 Future Improvements
	•	🌍 Auto-detect user location
	•	🌙 Dark / light mode toggle
	•	🔄 Loading animations
	•	🌡️ Temperature unit toggle (°C / °F)
	•	🔐 Secure API key handling
	•	📱 Additional mobile optimizations

⸻

👤 Author

Mohammed Alabweh
Computer Science Student

⸻

⭐ Acknowledgements
	•	OpenWeatherMap￼ for the weather API
	•	Google Fonts & Material Symbols

⸻
