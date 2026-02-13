# Station Météo React

Weather dashboard built with React, featuring real-time weather data and forecasts.

## Features

- **Current Weather**: Temperature, humidity, wind, conditions
- **Forecast**: 7-day weather forecast
- **Location Search**: Search by city name
- **Responsive Design**: Mobile-friendly interface
- **Weather Icons**: Visual weather representations

## Architecture

```
Station-Meteo-React/
├── public/           # Static assets
├── src/             # React components
├── package.json     # Dependencies
└── README.md
```

## Getting Started

### Prerequisites

- Node.js 18+
- npm or yarn

### Installation

```bash
npm install
```

### Development

```bash
npm start
```

Open http://localhost:3000

### Build for Production

```bash
npm run build
```

## API

Uses OpenWeatherMap API for weather data. Get your free API key at https://openweathermap.org/api

Configure in `.env`:
```
REACT_APP_API_KEY=your_api_key
REACT_APP_BASE_URL=https://api.openweathermap.org/data/2.5
```

## Tech Stack

- **React 18** - UI library
- **Create React App** - Build setup
- **Axios** - HTTP client
- **CSS Modules** - Styling

## License

MIT
