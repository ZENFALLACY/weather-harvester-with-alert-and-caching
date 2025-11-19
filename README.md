Weather Harvester with Alert & Caching

A powerful, modular, and beginner-friendly Python Weather App that fetches real-time weather data including temperature, humidity, wind speed, and sky conditions using a public weather API.
This project focuses on clean architecture, efficient caching, CLI usage, error handling, and alerting—making it ideal for learning API integration, modular Python, and building production-ready scripts.

🚀 Features
✅ Real-Time Weather Fetching

Fetches current weather conditions for any city worldwide.

Uses reliable APIs (OpenWeatherMap or similar).

⚡ Smart Caching System

Stores previously fetched results to reduce API calls.

Faster responses if data is already cached.

🚨 Weather Alerts (Optional)

Get alerts for extreme weather conditions such as:

High wind speed

Very high/low temperatures

Stormy conditions

Alert thresholds can be customized.

🛠️ Clean Code & Modular Architecture

Structured into separate modules:

api_client.py

cache_manager.py

alert_system.py

utils.py

main.py

Easy to maintain, expand, and debug.

🖥️ CLI (Command Line Interface) Support

Uses argparse for user-friendly command options.

Example:

python main.py --city "Mumbai"

🔐 Error Handling

Graceful handling of:

Invalid city names

API failures

Missing internet

Unexpected data formats

📦 Configurable Settings

Configuration via config.ini or JSON:

API Key

Cache duration

Alert thresholds

📁 Project Structure
weather-harvester-with-alert-and-caching/
│── api_client.py
│── cache_manager.py
│── alert_system.py
│── main.py
│── config.ini / config.json
│── requirements.txt
│── README.md
