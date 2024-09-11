# Weather App

## Overview

The Weather App is a React-based web application that provides real-time weather information for cities around the world. Users can search for a city to get the current temperature and weather description. The app features a clean and modern user interface with a background image to enhance the visual experience.

## Features

- **Real-Time Weather Data:** Fetch current weather information using the OpenWeatherMap API.
- **Search Functionality:** Users can search for weather updates by entering the name of a city.
- **Responsive Design:** The app is designed to be responsive and look great on both desktop and mobile devices.
- **Background Image:** A beautiful background image sets the scene for the weather information.



## Technology Stack

- **React:** Frontend library for building user interfaces.
  - **Hooks:**
    - **`useState`**: Manages the state within functional components. Used to track the city name and weather data.
    - **`useEffect`**: Handles side effects such as fetching weather data from the API. Executes code when the component mounts or when dependencies change.
  - **Props:** Used to pass data and functions between components, enabling dynamic and reusable UI elements.
- **Axios:** HTTP client for making API requests to fetch weather data.
- **OpenWeatherMap API:** Provides weather data for cities. Accessed via API requests to get current weather conditions.
- **CSS:** Used for styling and layout of the application, including responsive design and component-specific styles.

Please look at the master branch for full code.

