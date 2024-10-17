# weather_app
 
Weather App 🌤
This Flutter application allows users to check the current weather conditions of any city worldwide. The app integrates with the OpenWeatherMap API to provide real-time weather data, including temperature, weather descriptions, humidity levels, and wind speed. It features a clean, responsive UI that adapts seamlessly across both mobile and tablet devices.

Features
Real-time Weather Data: Fetches current weather conditions for any city globally using the OpenWeatherMap API.
Detailed Information: Displays:
Temperature
Weather description (e.g., cloudy, sunny)
Humidity level
Wind speed
User-Friendly Interface: Clean and minimalistic UI with responsive design for mobile and tablet devices.
Search Functionality: Easily search for and view weather data for different cities.

Screenshots
Folder is created on repo

Getting Started
Prerequisites
To run this project, you need:

Flutter SDK: Install Flutter
An API key from OpenWeatherMap
Installation
Clone this repository:


git clone https://github.com/yourusername/weather-app.git
cd weather-app
Install the dependencies:


flutter pub get
Set up the OpenWeatherMap API key:

Create a .env file in the project root and add your OpenWeatherMap API key:

OPENWEATHER_API_KEY=your_api_key_here
Run the app:


flutter run
API Integration
This app uses the OpenWeatherMap API to retrieve weather information. You'll need to register and obtain an API key from their website.

Example API Call:

https://api.openweathermap.org/data/2.5/weather?q={city_name}&appid={your_api_key}
Packages Used
http: For making API calls to OpenWeatherMap.
flutter_dotenv: For managing API keys securely in environment variables.
provider: For state management across the app.
Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue to discuss any changes or improvements.

License
This project is licensed under the MIT License - see the LICENSE file for details.
