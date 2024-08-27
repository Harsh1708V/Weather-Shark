Weather Shark

Weather Shark is an Android application that provides real-time weather updates using the OpenWeather API. It allows users to check the current weather conditions, including temperature, humidity, and weather descriptions.
Features

    Current Weather: Get real-time weather updates for any location.
    Location Search: Search for weather information by city name.
    Weather Details: View detailed weather information, including temperature, humidity, and weather conditions.

Prerequisites

    Android Studio (latest version recommended)
    An OpenWeather API key (sign up at OpenWeather to get your API key)

Installation

    Clone the Repository:

    bash

git clone https://github.com/Harsh1708V/Weather-Shark.git

Open the Project in Android Studio:

    Open Android Studio.
    Select "Open an existing project."
    Navigate to the directory where you cloned the repository and select it.

Add Your API Key:

    

    Add your OpenWeather API key to the file:

    xml

        <string name="api_key">YOUR_API_KEY</string>

    Sync the Project:
        Click on "Sync Project with Gradle Files" in Android Studio to ensure all dependencies are correctly set up.

    Run the App:
        Connect an Android device or start an emulator.
        Click on the "Run" button in Android Studio to build and run the app.

Usage

    Open the App: Launch Weather Shark on your Android device.
    Search for Location: Enter a city name in the search bar to get weather updates.
    View Weather Details: The app will display the current weather conditions for the searched location.

API Integration

The app uses the OpenWeather API to fetch weather data. The API requests are handled in the app’s network module, which processes the JSON responses and updates the UI accordingly.
Project Structure

    MainActivity.java: Entry point of the application; handles user input and displays weather data.
    res/layout/activity_main.xml: Layout file for the main activity.

License

This project is licensed under the MIT License. See the LICENSE file for details.
Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.
Contact

For any questions or issues, please contact:

    Email: harshwaibhav69@gmail.com
    GitHub: Harsh1708V
