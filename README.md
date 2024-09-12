## Forecastify - Weather App
Forecastify is a weather forecast web app that allows users to search for the current weather conditions of any city, providing details such as temperature, humidity, and wind speed.

## Features
- Search for real-time weather information by city.
- Displays temperature, humidity, and wind speed.
- Dynamic weather icons based on the current conditions (e.g., clouds, rain, clear sky).
- Error handling for invalid city names.
  
## Tech Stack
- **HTML** - Structure of the webpage.
- **CSS** - Styling and layout for the weather card and background.
- **JavaScript** - Fetching weather data from the OpenWeather API.
- **OpenWeather API** - Provides the weather data.
 
## How to Run Locally
- Clone the repository:
  ```
  git clone https://github.com/your-username/forecastify.git
  ```

- Navigate to the project directory:
  ```
  cd forecastify
  ```
  
- Open index.html in your browser to see the app in action.

- API Key Setup
Visit OpenWeather and generate an API key.\
Replace the apiKey in the JavaScript code with your own API key:

```
const apiKey = "your_api_key_here";
```

## Future Improvements
- Add a loading spinner while fetching data.
- Allow users to see forecasts for the next few days.
- Add unit switching between Celsius and Fahrenheit.
