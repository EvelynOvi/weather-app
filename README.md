# Weather App

This is a simple weather application that allows users to fetch and display weather information for a given city. It utilizes the OpenWeatherMap API to retrieve weather data.

## Getting Started

The weather app provides a simple interface for users to search for weather information. It displays the weather icon, description, temperature, humidity, and wind speed for the specified city.

### Searching for Weather

To search for weather information, you have two options:

1. Enter a city name in the search bar and click the search button.

The app will retrieve the weather data from the OpenWeatherMap API and display it on the page.

## Example

By default, the weather app fetches and displays weather information for Lagos. You can modify this default city by changing the argument in the last line of the `script.js` file:

```javascript
weather.fetchWeather("Lagos");
```

Replace `"Lagos"` with the desired city name to fetch weather information for that location.

## License

This weather app is licensed under the [MIT License](https://opensource.org/licenses/MIT).