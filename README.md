# Weather Web App

## Overview
The **Weather Web App** is a real-time weather forecasting application built with **Spring Boot and Thymeleaf**. It fetches live weather data using the **OpenWeather API** and presents it through a responsive web interface.

## Features
- **Real-Time Weather Data**: Fetches and displays current weather conditions from OpenWeather API.
- **Spring Boot & MVC Architecture**: Ensures efficient backend processing.
- **RESTful API Integration**: Implements API calls for seamless data retrieval.
- **Responsive UI**: Designed using **HTML, CSS, and Thymeleaf** for an interactive user experience.

## Tech Stack
- **Spring Boot**: Backend framework for Java-based web applications.
- **Thymeleaf**: Server-side templating engine for dynamic content rendering.
- **OpenWeather API**: Provides real-time weather data.
- **HTML & CSS**: Frontend design for a clean and responsive UI.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Nirvighna04/Weather-Web-App.git
   cd Weather-Web-App
   ```

2. Set up your **OpenWeather API key** in `application.properties`:
   ```
   weather.api.key=your_openweather_api_key
   ```

3. Build and run the application:
   ```bash
   mvn clean install
   mvn spring-boot:run
   ```

4. Open your browser and navigate to:
   ```
   http://localhost:8080
   ```

## Usage
- Enter a city name in the search bar.
- View real-time weather details, including temperature, humidity, and weather conditions.

## Future Enhancements
- Add 7-day weather forecasts.
- Implement geolocation-based weather detection.
- Improve UI with JavaScript and Bootstrap.

## Contributions
Contributions are welcome! Feel free to fork the repository and submit a pull request.
