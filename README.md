
 React Weather App Introduction

 Overview

The React Weather App is a simple yet powerful application designed to provide users with real-time weather information for a specified location. Built using React, it leverages the OpenWeatherMap API to fetch weather data and displays it in an intuitive and visually appealing manner.

Key Features

1. **Location-Based Weather:** The app utilizes the user's geolocation to fetch weather information for their current location when the app loads.

2. **Search Functionality:** Users can search for weather details in any city worldwide. The app dynamically updates the weather data based on the user's input.

3. **Live Weather Updates:** The app provides live updates on various weather parameters, including temperature, humidity, wind speed, and more.

4. **Weather Icons:** Distinctive icons represent different weather conditions, enhancing the user experience and making it easy to grasp the current weather at a glance.



Technical Implementation

1. **React Components:** The app is structured using React components, ensuring a modular and maintainable codebase. Each feature, such as the search bar, weather display, and error handling, is encapsulated in its respective component.

2. **API Integration:** The app integrates with the OpenWeatherMap API to fetch accurate and up-to-date weather information. It supports both geolocation-based and city-specific weather queries.

3. **Asynchronous Operations:** JavaScript's `async/await` is employed to handle asynchronous operations, such as fetching weather data from the API.

4. **Styling with CSS:** CSS is used to style the app, providing an aesthetically pleasing and user-friendly interface. Different weather conditions are visually represented using appropriate icons.

5. **Error Handling:** The app incorporates robust error handling to gracefully manage scenarios where weather data cannot be retrieved, ensuring a smooth user experience.

 Usage

1. **Default Location:** Upon loading the app, the user's default location is fetched automatically, providing immediate weather information.

2. **Search:** Users can input a city name in the search bar to get weather details for that specific location.

3. **Visual Weather Representation:** Weather conditions are visually represented with icons, making it easy for users to understand the current climate.

Default Page:
   By default it will fetch the user brower location
    
![image](https://github.com/dheerajpatnala/weather_app/assets/159060960/0e66bfc2-1086-47c5-af9d-31d039c57582)

Search Location Page:
   If user searches for any location we will get the data from api which is configured
   
![image](https://github.com/dheerajpatnala/weather_app/assets/159060960/7a875d70-b684-4664-b013-cd8d8f3a08ac)

If City Not Found:
   If user mispelled any city name we will show an error message
   
![image](https://github.com/dheerajpatnala/weather_app/assets/159060960/0f749d93-1627-4bdd-add4-1dd336ac1736)


 Conclusion

The React Weather App is a user-friendly and informative tool for checking the weather, whether you're planning your day or curious about conditions in different locations worldwide. Its simplicity and effectiveness make it a valuable resource for users of all levels.



To run locally:

Clone repository:

git clone https://github.com/dheerajpatnala/weather_app.git

Move to folder:

cd weather_app

Install dependencies:

npm install

Run application:

npm run dev

Navigate to http://localhost:5173 The application will automatically reload if you change any of the source files.

Build
Run ng build to build the project. The build artifacts will be stored in the dist/ directory.
