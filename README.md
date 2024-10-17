# Flutter Weather App 🌦️

This Flutter application allows users to check the **current weather conditions** of any city worldwide. It leverages the **OpenWeatherMap API** to fetch real-time weather data, displaying essential information such as **temperature**, **weather description**, **humidity**, and **wind speed**. The app features a clean and **responsive UI** that adapts seamlessly across mobile and tablet devices.

## Features

- 🌍 **Global Weather Data**: Fetches weather information for cities across the globe using the OpenWeatherMap API.
- 📊 **Real-Time Weather Updates**: Displays current temperature, weather description, humidity levels, and wind speed.
- 💻 **Responsive Design**: Adapts smoothly to various screen sizes, offering a great user experience on both mobile phones and tablets.
- 🔍 **Search Functionality**: Allows users to search and view weather data for any city.
- 📱 **Simple & Clean UI**: Minimalistic interface focused on ease of use.

## Tech Stack

- **Flutter**: The app is built with the Flutter framework.
- **Dart**: Programming language used for Flutter.
- **OpenWeatherMap API**: Provides real-time weather data for any city.

## Screenshots

_Include some relevant screenshots of the app’s UI displaying weather data._

## Getting Started

### Prerequisites

- Flutter SDK: [Install Flutter](https://flutter.dev/docs/get-started/install)
- An OpenWeatherMap API key: [Get API Key](https://home.openweathermap.org/users/sign_up)

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/flutter-weather-app.git
    ```

2. Navigate to the project directory:
    ```bash
    cd flutter-weather-app
    ```

3. Install the required dependencies:
    ```bash
    flutter pub get
    ```

4. Set up the OpenWeatherMap API key:
   - Open `lib/services/weather_service.dart` (or the respective service file).
   - Replace `your_api_key_here` with your actual OpenWeatherMap API key.

5. Run the app:
    ```bash
    flutter run
    ```

## Usage

1. Enter the name of any city in the search bar to fetch its weather details.
2. View real-time temperature, weather conditions, humidity, and wind speed.

## Packages Used

- [`http`](https://pub.dev/packages/http): To make API requests to OpenWeatherMap.
- [`provider`](https://pub.dev/packages/provider): For state management across the app.
- [`flutter_spinkit`](https://pub.dev/packages/flutter_spinkit): For displaying loading indicators.

## API Integration

The app integrates with the **OpenWeatherMap API** to fetch weather data in real-time. To use the app, you must set up your API key as described above.

- [OpenWeatherMap API Documentation](https://openweathermap.org/api)

## Contributing

Contributions are welcome! If you'd like to contribute, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
