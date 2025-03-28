# Modern Weather Application

A beautiful and responsive weather application built with React, TypeScript, and Tailwind CSS. This application provides real-time weather information and forecasts with a stunning user interface that adapts to different weather conditions.

## Features

- Real-time weather data from WeatherAPI
- Beautiful, responsive design
- Dark/light mode support
- 5-day weather forecast with interactive charts
- Animated backgrounds based on weather conditions
- Local storage for remembering the last searched location
- Fully customizable with environment variables

## Getting Started

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Create a `.env` file in the root directory and add your WeatherAPI key:
   ```
   VITE_WEATHER_API_KEY=your_weatherapi_key_here
   ```
4. Start the development server:
   ```bash
   npm run dev
   ```

## Environment Variables

- `VITE_WEATHER_API_KEY`: Your WeatherAPI API key (required)

## Technologies Used

- React
- TypeScript
- Tailwind CSS
- Axios
- React Query
- Recharts
- Lucide React

## Customization

You can customize the application by:

1. Modifying the Tailwind configuration in `tailwind.config.js`
2. Adjusting the theme colors in `src/index.css`
3. Updating the weather conditions and background gradients in `App.tsx`

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License.