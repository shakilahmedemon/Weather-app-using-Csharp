#  Weather App using C# (Console Application)

> A real-time command-line weather application built in C# that fetches and displays current weather data for any city worldwide using the OpenWeatherMap API.

##  Features

* **Real-time Data:** Fetches the latest temperature, weather conditions, humidity, and wind speed.
* **City Search:** Allows users to search for weather by city name.
* **Metric Units:** Displays temperature in Celsius (°C) and wind speed in meters per second (m/s).
* **User-Friendly Interface:** Provides clear console output with weather emojis for easy reading.
* **Error Handling:** Gracefully handles invalid city names or API connection issues.

##  Technology Stack

* **Language:** C#
* **Framework:** .NET 9.0 (Console Application)
* **Dependencies:** `System.Net.Http` for API calls and `System.Text.Json` for JSON parsing.
* **External API:** [OpenWeatherMap API](https://openweathermap.org/api)

##  Getting Started

### Prerequisites

To run this application, you must have the following installed:

* [.NET 9.0 SDK](https://dotnet.microsoft.com/download/dotnet/9.0) or later.
* A code editor like Visual Studio 2022 or Visual Studio Code.

### Installation and Setup

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/YOUR-USERNAME/Weather-app-using-csharp.git](https://github.com/YOUR-USERNAME/Weather-app-using-csharp.git)
    cd Weather-app-using-csharp
    ```

2.  **API Key Configuration (Crucial Step)**

    The application currently uses an API key embedded in the `Program.cs` file:
    
    ```csharp
    string apiKey = "5c05e502387370283e249b6857d8b621"; // THIS IS THE KEY USED IN THE UPLOADED CODE
    ```
    
    ** Security Warning:** Embedding the API key directly in the source code is **not** a secure practice for public repositories. For better security and to ensure the app works for others, please **create your own free API key** from [OpenWeatherMap](https://openweathermap.org/api) and **replace the value** in `Program.cs` with your personal key.

3.  **Run the Application:**
    Navigate to the project directory containing the `.csproj` file and execute:
    ```bash
    dotnet run
    ```

##  How to Use

1.  The welcome message will display, prompting you for a city name.
2.  Type the name of any city (e.g., `London`, `Dhaka`, `Tokyo`).
3.  The application will display the current weather details.
4.  You will be prompted to check another city or type `exit` to close the application.

##  Contribution

This project was built as part of the CST 2021 curriculum by **AHMED MD SHAKIL**.

If you have suggestions for improvement, please open an issue or submit a pull request!

---
