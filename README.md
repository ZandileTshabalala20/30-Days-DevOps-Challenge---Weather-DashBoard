30 Days DevOps Challenge - Weather Dashboard
Day 1: Building a Weather Data Collection System using AWS S3 and OpenWeather API

Project Overview
The Weather Data Collection System is a hands-on project that aligns with essential DevOps practices, incorporating the following:

API Integration: Pulls real-time weather data from the OpenWeather API.
Cloud Storage: Utilizes AWS S3 to store weather data.
Infrastructure as Code (IaC): Implements best practices in provisioning cloud resources.
Version Control: Managed using Git for seamless collaboration and version history.
Error Handling & Logging: Ensures robust error detection and logging for reliable operations.
Environment Management: Utilizes environment variables for configurable settings across environments.

Features
Fetches real-time weather data for selected cities
Displays key weather metrics, including temperature (°F), humidity, and overall weather conditions
Automatically stores the data in AWS S3 for persistence
Supports tracking for multiple cities with unique data
Captures timestamps for each data point, enabling historical analysis and tracking

Technical Architecture
Programming Language: Python 3.x
Cloud Provider: AWS (S3)
External API: OpenWeather API

Key Dependencies
boto3: AWS SDK for Python to interact with S3
python-dotenv: To manage environment variables for configuration
requests: To make HTTP requests to the OpenWeather API

Project Structure:
weather-dashboard/
├── src/
│   ├── __init__.py
│   └── weather_dashboard.py
├── tests/
├── data/
├── .env
├── .gitignore
└── requirements.txt
