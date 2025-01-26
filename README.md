# Weather App

A feature-rich weather application built with modern web development technologies to provide users with accurate and visually appealing weather data.

## Features

- **Real-Time Weather Updates**: Displays current weather data for any location.
- **Search Functionality**: Allows users to search for weather details by city name.
- **5-Day Forecast**: Provides a detailed weekly weather forecast.
- **Data Visualization**: Beautifully designed charts using Recharts for temperature trends and other weather metrics.
- **Responsive Design**: Fully optimized for desktop and mobile devices.

## Tech Stack

This application leverages the following technologies:

### Frontend
- **React**: For building the user interface.
- **TypeScript**: Ensures type safety and improved developer experience.
- **Shadcn**: Provides pre-styled components for a polished UI.
- **React-Router-Dom**: For efficient client-side routing.

### Data Management
- **React Query**: For fetching, caching, and updating data from the OpenWeather API seamlessly.

### API Integration
- **OpenWeather API**: Supplies real-time and forecasted weather data.

### Visualization
- **Recharts**: Used to create interactive and informative charts for weather metrics.

## Installation and Setup

Follow these steps to run the application locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/weather-app.git
   ```

2. Navigate to the project directory:
   ```bash
   cd weather-app
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Create a `.env` file in the root directory and add your OpenWeather API key:
   ```env
   REACT_APP_WEATHER_API_KEY=your_api_key_here
   ```

5. Start the development server:
   ```bash
   npm start
   ```

6. Open your browser and navigate to `http://localhost:3000` to view the app.

## Project Structure

```
weather-app/
├── public/
├── src/
│   ├── components/      # Reusable UI components
│   ├── pages/           # Application pages (Home, Forecast, etc.)
│   ├── services/        # API calls and data-fetching logic
│   ├── hooks/           # Custom React hooks (e.g., for React Query)
│   ├── assets/          # Static assets like images and icons
│   ├── App.tsx          # Main application file
│   ├── index.tsx        # Entry point
├── .env                 # Environment variables
├── package.json         # Project metadata and dependencies
```

## Usage

1. Enter the name of a city in the search bar to fetch weather details.
2. View real-time weather metrics, including temperature, humidity, and wind speed.
3. Navigate to the "Forecast" page to explore the 7-day forecast.
4. Interact with the charts to understand weather trends visually.

## Future Enhancements

- Add support for multiple languages.
- Allow users to save favorite locations.
- Implement dark mode for improved usability in low-light environments.
- Introduce additional weather metrics like air quality and UV index.

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Open a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

---

Happy coding! If you have any questions or feedback, feel free to open an issue.

