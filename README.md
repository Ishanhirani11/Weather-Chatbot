# 🌤️ Simple Weather App (CLI)

A lightweight Command Line Interface (CLI) Python script that fetches and displays real-time weather information for any city in the world. It uses the OpenWeatherMap API to retrieve accurate data including temperature (in Celsius), humidity, and weather conditions.

---

## ✨ Features

* **Real-Time Weather Data:** Fetches up-to-date temperature, humidity, and weather descriptions.
* **Continuous Loop:** Allows you to check the weather for multiple cities in a single session without restarting the script.
* **Secure API Key Management:** Uses `python-dotenv` to keep your OpenWeatherMap API key secure and hidden from the source code.
* **Error Handling:** Gracefully alerts you if a city is not found or spelled incorrectly.

---

## 🛠️ Prerequisites

Before running the script, make sure you have the following:
* **Python 3.6** or higher installed on your system.
* A free **OpenWeatherMap API Key** (You can sign up and get one at [openweathermap.org](https://openweathermap.org/)).

---

## 🚀 Installation & Setup

### 1. Clone or download the repository**
```
git clone https://github.com/Ishanhirani11/Weather-Chatbot.git
cd Weather-Chatbot
```

### 2. Create virtual environment

```
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
```

### 3. Install dependencies

```
pip install -r requirements.txt
```

### 4. Add Your API Key

Create a .env file in the root directory:
```
API_KEY=your_API_KEY
```

### 5. Run the Application
```
python Weater.py
```
You will see:
```
Enter city name (or 'exit'): London

Weather in London:
Temperature: 15.4°C
Humidity: 72%
Condition: scattered clouds

Enter city name (or 'exit'): exit
```

## 📜 License
This project is open-source and available under the MIT License.
