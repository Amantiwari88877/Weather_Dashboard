
# 🌦️ Weather Dashboard (ReactJS)

A responsive **Weather Dashboard** built with **React.js** that integrates with the **Open-Meteo API** to display real-time weather information, hourly forecasts, and historical weather trends using interactive charts.

The application automatically detects the user's location using **browser GPS** and displays weather data for the current date or a selected date.

## 🚀 Features

### 📍 Automatic Location Detection
- Fetches user location using browser GPS
- Displays weather data based on current coordinates

### 🌡️ Current Weather Information
Displays key weather parameters:
- Temperature (Min, Max, Current)
- Precipitation
- Relative Humidity
- UV Index
- Sunrise & Sunset
- Maximum Wind Speed
- Precipitation Probability

### 🌫️ Air Quality Data
- PM10
- PM2.5
- CO (Carbon Monoxide)
- CO2 (Carbon Dioxide)
- NO2 (Nitrogen Dioxide)
- SO2 (Sulphur Dioxide)

### 📊 Hourly Weather Graphs
For a selected date the dashboard shows hourly charts for:
- Temperature
- Relative Humidity
- Precipitation
- Visibility
- Wind Speed (10m)
- PM10 & PM2.5

### 📅 Historical Weather Analysis
Users can select a **date range up to 2 years** to view historical trends including:
- Mean, Max, and Min Temperature
- Sunrise & Sunset timings
- Precipitation
- Maximum Wind Speed
- Dominant Wind Direction
- PM10 & PM2.5 trends

### 📈 Interactive Graphs
- Horizontal scrolling
- Zoom in / Zoom out
- Mobile responsive charts

## 🛠️ Tech Stack

- React.js
- JavaScript (ES6)
- HTML5
- CSS3 / Tailwind CSS
- Open-Meteo API
- Chart Library (Recharts / Chart.js / ECharts)

## ⚡ Performance
- Optimized API calls
- Data rendering under **500ms**
- Responsive UI for desktop and mobile devices

## 🌐 API Used
https://open-meteo.com

## 📱 Responsive Design
The application is fully responsive and works smoothly across:
- Desktop
- Tablet
- Mobile devices

## 📦 Installation

```bash
git clone https://github.com/your-username/weather-dashboard.git
cd weather-dashboard
npm install
npm start
