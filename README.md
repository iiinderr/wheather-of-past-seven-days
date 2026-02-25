# 🌦️ Weather of Past Seven Days

This project fetches weather data for the past 7 days using the **Open-Meteo API**, analyzes it using **Pandas**, and visualizes temperature trends with **Matplotlib**.

---

## 📌 Project Overview

The script:

* Fetches weather data (max & min temperature)
* Stores data in a Pandas DataFrame
* Creates a temperature chart
* Saves data as a CSV file
* Saves the weather graph as an image

Location used: **Bathinda (Latitude: 30.21, Longitude: 74.94)**

---

## 🛠️ Technologies Used

* Python
* Requests
* Pandas
* Matplotlib
* Open-Meteo Weather API

---

## 📂 Project Structure

```
wheather-through-api/
│
├── wheather-in-tableform.py
├── weather_chart.png
├── data/
│   └── Bathinda_weather.csv
└── README.md
```

---

## ▶️ How to Run

### 1️⃣ Install dependencies

```bash
pip install requests pandas matplotlib
```

### 2️⃣ Run the script

```bash
python wheather-in-tableform.py
```

---

## 📊 Output

* Weather chart image (`weather_chart.png`)
* CSV file with temperature data (`data/Bathinda_weather.csv`)
* Console output of weather data

---

## 📈 Example Features

* Past 7 days weather analysis
* Data visualization using line charts
* Automatic CSV export
* Clean data handling with Pandas

---

## 👨‍💻 Author

Inder Pal Singh
