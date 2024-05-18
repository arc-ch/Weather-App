
# Weather App

![image_2024-05-18_18-51-56](https://github.com/arc-ch/Weather-App/assets/134518231/2afb2cb9-340c-49c2-93b3-35334f9c8f4a)

## Introduction
The Weather App provides weather information based on the user's location or a searched city using the OpenWeatherMap API.

## Features
- Weather info based on user's current location.
- Search weather by city name.
- Loading screen while fetching data.
- Error handling with retry option.
- Responsive design.

## Technologies Used
- HTML5
- CSS3
- JavaScript
- OpenWeatherMap API

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/weather-app.git
   ```
2. Navigate to the project directory:
   ```sh
   cd weather-app
   ```
3. Open `index.html` in a web browser.


## Usage
1. Open the app in your browser.
2. Allow location access to get local weather info.
3. Use tabs to switch between local weather and search.
4. Enter a city name and search for weather info.

## API Reference
- **Base URL:** `https://api.openweathermap.org/data/2.5/weather`
- **Parameters:**
  - `lat`, `lon` for coordinates
  - `q` for city name
  - `appid` for API key
  - `units` for metric system

## License
This project is licensed under the MIT License.
