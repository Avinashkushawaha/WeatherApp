# Weather App

A responsive Weather App built with **HTML**, **CSS**, and **React.js**, utilizing a weather API for real-time weather updates. This project provides users with current weather information based on their location or a specified city.

## Features

- **Real-time Weather Data**: Fetches and displays the current weather conditions.
- **Location-Based Search**: Get weather information based on your current location.
- **City Search**: Search for weather details of any city worldwide.
- **Responsive Design**: Optimized for all devices including mobile, tablet, and desktop.
- **Dynamic Backgrounds**: Backgrounds change based on weather conditions.

## Technologies Used

- **HTML5**: For the structure of the application.
- **CSS3**: For styling and creating a visually appealing user interface.
- **React.js**: For building a dynamic and interactive user experience.
- **Weather API**: Fetching real-time weather data.
- **Netlify**: Hosting the project for live access.

## Getting Started

### Prerequisites

Before you begin, ensure you have the following installed on your system:

- Node.js (v14 or higher)
- npm or yarn

### Installation

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
   # or
   yarn install
   ```

4. Get an API key from [OpenWeatherMap](https://openweathermap.org/api) or your preferred weather API provider.

5. Create a `.env` file in the root directory and add your API key:
   ```env
   REACT_APP_WEATHER_API_KEY=your_api_key_here
   ```

6. Start the development server:
   ```bash
   npm start
   # or
   yarn start
   ```

### Live Demo

Check out the live project here: [Weather App on Netlify](https://deft-mermaid-c3da82.netlify.app/)

## Project Structure

```
weather-app/
|-- public/
|   |-- index.html
|-- src/
|   |-- components/
|   |   |-- WeatherCard.js
|   |   |-- SearchBar.js
|   |-- styles/
|   |   |-- App.css
|   |   |-- WeatherCard.css
|   |-- App.js
|   |-- index.js
|-- .env
|-- package.json
|-- README.md
```

## How It Works

1. Users can enter the name of a city in the search bar to get the current weather details.
2. Alternatively, users can allow location access for fetching weather data based on their geographic location.
3. The app makes a request to the weather API and displays the relevant weather information including temperature, humidity, wind speed, and more.
4. Dynamic backgrounds and icons enhance the user experience based on the current weather condition.

## Contributing

Contributions are welcome! If you'd like to contribute:

1. Fork the repository.
2. Create a new branch for your feature:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add some feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

**Developed By**: Avinash Kushawaha

Feel free to contact me for feedback or suggestions!

