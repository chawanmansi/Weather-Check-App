This Weather Check App is a simple Java application that allows users to check the current weather conditions for a specific location using a weather data API. With this app, users can quickly get information about the temperature, humidity, wind speed, and other relevant weather data for a chosen location.
**Features**
**Current Weather Data:** Retrieve real-time weather data for a specified location.
**User-Friendly Interface:** A straightforward command-line interface for ease of use.
**Customizable:** Users can input their desired location for weather information.
**API Integration:** Utilizes a weather data API to fetch accurate and up-to-date information.

Getting Started
Follow these steps to set up and run the Weather Check App:

**Clone the Repository:**
shell
Copy code
**git clone https://github.com/chawanmansi/weather-check-app.git
cd weather-check-app**

**API Key:**
Obtain an API key from a weather data provider. You may need to sign up for an account on their website to get the key.

**Configure API Key:**
Open the WeatherApiClient.java file and replace the placeholder 'YOUR_API_KEY' with your actual API key.

Copy code
private static final String API_KEY = "YOUR_API_KEY";
Compile and Run:

**Compile and run the Java application using the following commands:**

shell
Copy code
javac WeatherApp.java
java WeatherApp
Input Location:

Enter the location for which you want to check the weather. The app will fetch and display the current weather data.

**Dependencies**
This app uses the following dependencies:

Gson: A Java library for working with JSON data. You can find it at https://github.com/google/gson.
API Used
This app relies on a weather data API to provide weather information. You can replace the API with any other weather data provider of your choice. The app currently uses OpenWeatherMap API as an example.

Contributions
Contributions to this Weather Check App project are welcome! Feel free to fork the repository, make changes, and submit pull requests.

**License**
This Weather Check App is licensed under the MIT License - see the LICENSE file for details.

**About**
This project was created as a demonstration of building a Java application that utilizes an API for fetching real-time weather data. It can serve as a starting point for more advanced weather-related projects or as a learning tool for those new to Java and API integration.

For any questions or feedback, please feel free to open an issue or contact the project maintainers.

**Happy Weather Checking!** 🌦️☀️🌧️
