
## Application Overview

This project is a dynamic web application that allows users to retrieve real-time weather data for any city, view forecasts for the next five days, and get a detailed breakdown of current weather conditions such as temperature, humidity, wind speed, and more. The application is powered by the OpenWeatherMap API and provides users with the option to switch between Celsius and Fahrenheit for temperature display.

## Key Features

- **Real-Time Weather Data:** Fetches the latest weather data for any city using the OpenWeatherMap API.

![Screenshot 2024-10-24 155002](https://github.com/user-attachments/assets/38b501fc-0263-40da-8689-7612059d8f51)
- **5-Day Forecast:** Displays a forecast for the next five days, showing weather trends for better planning.
  
![image](https://github.com/user-attachments/assets/f62b3a60-0842-4544-b41e-51980e5ec380)

- **Temperature Unit Conversion:** Users can switch between Celsius and Fahrenheit based on their preference.
  
![IMG_20241024_165822](https://github.com/user-attachments/assets/6b24abec-e384-477b-9e1d-2fa3f03443b6)

- **Detailed Weather Information:** Includes additional weather parameters such as humidity, wind speed, and atmospheric pressure.
  
![Screenshot 2024-10-24 165036](https://github.com/user-attachments/assets/562d86c3-eda2-4fed-a252-1b5059dd3d6e)


- **User-Friendly Interface:** Easy-to-use search functionality to quickly get weather updates by city name.
- **Responsive Design:** The application adjusts seamlessly across different screen sizes and devices.

## Design and Implementation

- **API Integration:** The weather data is fetched from the OpenWeatherMap API with API calls that retrieve the current weather and the five-day forecast. 
- **Modular Structure:** The application is organized into functions that handle API requests, temperature conversions, and the display of weather information, making it easy to scale or modify.
- **Dynamic Content Rendering:** Weather information and forecasts are dynamically updated based on user input, with real-time data refreshing upon new searches.
- **Error Handling:** Proper error handling is implemented to notify users when the requested city is not found or when there are issues fetching data from the API.

## Project Requirements

- **OpenWeatherMap API Key:** You'll need an API key from OpenWeatherMap to fetch weather data.
- **Node.js (Optional):** Required for running the application locally with a live server setup.

## Setup and Installation

### Prerequisites

Ensure that the following tools are installed:

- **Node.js** (for running the app locally)

### Installation

1. **Clone the Repository**
   ```bash
   git clone " https://yenniprasad.github.io/Weather-Application/"
   ```
2. **Install Dependencies**
   If you are running the app locally and need to install any dependencies:
   ```bash
   npm install
   ```

3. **Run a Local Server**
   If you prefer to run the application using a live server locally:
   ```bash
   npm install http-server -g
   http-server -p {any port number}
   ```

## Usage

1. Search for any city using the search bar.
2. Select the desired temperature unit (Celsius/Fahrenheit/Kelvin) from the dropdown menu.
3. View the current weather conditions, along with a five-day forecast.

## Running Tests

You can add and run tests to ensure everything is working correctly.
