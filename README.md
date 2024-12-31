# Weather App
1. Overview
A responsive weather app built with React and Vite, providing real-time weather updates for any location.

2. Features
- Real-time weather data
- Responsive design
- City search functionality
- Detailed weather info (temperature, humidity, wind speed)

3. Tech Stack
- React
- Vite
- CSS/SCSS or Tailwind CSS
- OpenWeatherMap API

## Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/weather-app.git
   cd weather-app
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Add your API key in `.env`:
   ```env
   VITE_WEATHER_API_KEY=your_api_key_here
   ```
4. Start the development server:
   ```bash
   npm run dev
   ```

## Build for Production
```bash
npm run build
```

## Project Structure
```
weather-app/
├── src/
│   ├── components/  # Reusable components
│   ├── pages/       # Page components
│   ├── styles/      # CSS/SCSS files
│   ├── App.jsx      # Main app component
│   ├── main.jsx     # Entry point
├── .env             # Environment variables
└── vite.config.js   # Vite configuration
```

## License
This project is licensed under the MIT License.

