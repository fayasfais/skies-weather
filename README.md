# 🌤️ Skies — Weather Dashboard

A beautiful, modern weather dashboard built with React and Tailwind CSS. Features adaptive gradient backgrounds based on weather conditions, dark/light mode, and a 5-day forecast.

![Skies Weather Dashboard](https://img.shields.io/badge/React-18-blue?style=flat-square&logo=react) ![Tailwind CSS](https://img.shields.io/badge/Tailwind-3-38bdf8?style=flat-square&logo=tailwindcss) ![OpenWeatherMap](https://img.shields.io/badge/OpenWeatherMap-API-orange?style=flat-square)

## ✨ Features

- 🔍 Search any city worldwide
- 🌡️ Current temperature, feels like, high/low
- 💧 Humidity, wind speed, visibility, pressure
- 📅 5-day forecast
- 🎨 Dynamic gradients per weather condition (sunny → amber, storm → purple, rain → cyan)
- 🌙 Auto day/night detection + manual dark/light toggle
- 🌡️ Celsius / Fahrenheit toggle
- 📱 Fully responsive (mobile-first)
- ⚡ Smooth loading skeletons

## 🚀 Quick Start

### 1. Clone & install
```bash
git clone https://github.com/YOUR_USERNAME/skies-weather.git
cd skies-weather
npm install
```

### 2. Add your API key
```bash
cp .env.example .env
```
Open `.env` and replace the placeholder with your free key from [openweathermap.org/api](https://openweathermap.org/api).

```
REACT_APP_WEATHER_API_KEY=your_key_here
```

### 3. Run
```bash
npm start
```
Open [http://localhost:3000](http://localhost:3000).

## 🏗️ Project Structure

```
skies-weather/
├── public/
│   └── index.html
├── src/
│   ├── components/
│   │   └── WeatherDashboard.jsx   # Main dashboard (all components)
│   ├── App.js
│   └── index.css                  # Tailwind directives
├── .env.example                   # API key template
├── .gitignore
├── package.json
├── tailwind.config.js
└── postcss.config.js
```

## 🔑 API Key

This project uses the [OpenWeatherMap API](https://openweathermap.org/api). The free tier includes:
- Current weather data
- 5-day / 3-hour forecast
- 60 calls/minute

**Never commit your `.env` file** — it's in `.gitignore` by default.

## 🛠️ Tech Stack

| Tech | Purpose |
|------|---------|
| React 18 | UI framework |
| Tailwind CSS 3 | Styling |
| OpenWeatherMap API | Weather data |

## 📄 License

MIT — free to use, modify, and distribute.
