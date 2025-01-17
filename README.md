# WeatherWebApp
# Weather API Project

This project uses the OpenWeather API to fetch and display weather information based on user input. The application is built using HTML, CSS, and JavaScript.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup](#setup)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project demonstrates how to integrate the OpenWeather API into a simple web application to display current weather information. Users can enter a city name, and the application will fetch and display the weather data for that location.

## Features

- Fetches current weather data from OpenWeather API
- Displays weather information including temperature, humidity, wind speed, and weather description
- User-friendly interface

## Technologies Used

- HTML
- CSS
- JavaScript
- OpenWeather API

## Setup

To set up the project locally, follow these steps:

1. Clone the repository:

    ```bash
    git clone https://github.com/abdulnafih27/WeatherWebApp.git
    cd WeatherWebApp
    ```

2. Obtain an API key from OpenWeather:

    - Go to [OpenWeather](https://openweathermap.org/api)
    - Sign up or log in to your account
    - Navigate to the API section and generate an API key

3. Create a `config.js` file in the root directory and add your API key:

    ```javascript
    // config.js
    const API_KEY = 'your_openweather_api_key';
    ```

4. Open `index.html` in your web browser to run the application.

## Usage

1. Enter a city name in the input field.
2. Click the "Get Weather" button.
3. The application will display the current weather information for the entered city.

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request with your changes.
