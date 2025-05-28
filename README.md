# Weather Dashboard

## Overview

This project is a React.js-based weather dashboard that fetches and displays real-time weather data. It demonstrates React fundamentals, API integration, component structure, hooks, and state management.

## Features

-   **Search**: Allows users to search for weather information by city.
-   **Current Weather**: Displays current weather details, including temperature, humidity, wind speed, and weather conditions, with corresponding icons.
-   **API Polling**: Updates weather data every 30 seconds using API polling.
-   **Error Handling**: Gracefully handles API errors such as incorrect city names or network failures.

**Bonus Features:**

-   **5-Day Forecast:** Displays a 5-day weather forecast.
-   **Temperature Unit Switching:** Allows users to switch between Celsius and Fahrenheit.

## Technologies Used

-   React.js
-   CSS Modules / Styled Components
-   OpenWeatherMap API (or alternative free weather API)
-   React Context API / Redux (for state management)

## Setup

1.  **Clone the repository:**

    ```shell
    git clone https://github.com/Shreykumar1/weather-dashboard
    ```

2.  **Navigate to the project directory:**

    ```shell
    cd weather-dashboard
    ```

3.  **Install dependencies:**

    ```shell
    npm install
    # or
    yarn install
    # or
    bun install
    ```

4.  **Obtain an API key**
    
    Sign up for a free account at [OpenWeatherMap](https://openweathermap.org/api) or another weather API provider and obtain an API key.

5.  **Set up environment variables:**

    Create a `.env` file in the project root and add your API key:

    ```
    VITE_API_KEY=your_api_key_here
    ```

6.  **Start the development server:**

    ```shell
    npm start
    # or
    yarn start
    # or
    bun run start
    ```

7.  **Open your browser and navigate to `http://localhost:3000` (or the appropriate port).**
