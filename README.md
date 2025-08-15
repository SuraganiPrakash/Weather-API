# Weather-API
# 🌦 Responsive Weather App

A modern, responsive weather application built with **HTML**, **CSS**, and **JavaScript**.  
It fetches live weather data using the [WeatherAPI](https://www.weatherapi.com/) and displays:

- **Current weather**
- **24-hour forecast**
- **3-day forecast**
- Feels-like temperature
- Humidity and wind speed

## 📸 Features

- 📍 **Search by city name**
- 🌡 **Current temperature in Celsius & Fahrenheit**
- 🕒 **Hourly forecast for the next 24 hours**
- 📅 **3-day forecast in a horizontal layout**
- 💨 **Additional info:** Feels-like temperature, humidity, and wind speed
- 🎨 Stylish, responsive UI with smooth animations
- 📜 Scrollable forecast sections

## 🛠 Technologies Used

- **HTML5** – Structure
- **CSS3** – Styling & animations
- **JavaScript (ES6+)** – API fetching & DOM updates
- **WeatherAPI** – Weather data source

## 📂 Project Structure

.
├── index.html # Main HTML file containing layout and scripts
└── README.md # Project documentation

bash
Copy
Edit

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/weather-app.git
cd weather-app
2. Open the App
Simply open the index.html file in your browser.

3. API Key Setup
This project uses WeatherAPI.
You need your own API key:

Sign up at WeatherAPI.

Replace the placeholder API key in index.html:

javascript
Copy
Edit
const apiKey = "YOUR_API_KEY";
📌 Usage
Enter a city name in the search bar.

Click Search.

View the current weather, hourly forecast, and 3-day forecast.

📷 Screenshot

⚠️ Note
Ensure you have a valid WeatherAPI key.

The app will display an error if the location is invalid or the API key is wrong.

📜 License
This project is open-source and available under the MIT License.
