# 🌦️ IoT-Based Weather Monitoring System

## 📝 Overview
Simulate a weather monitoring system using DHT11, LDR, soil moisture sensor, rain sensor, and LCD.  
It displays real-time temperature, humidity, light, soil moisture, and rain status on the LCD.

## 📂 Files Included
- `ArduinoIDEcode.ino` – Arduino code for sensor readings  
- `Weather Monitoring Circuit.pdsprj` – Proteus project file  
- `sketch_apr18a.ino.hex` – Compiled hex file

## ⚙️ Setup Steps

Clone Repository:
-----------------
git clone <your-repo-url>
cd Design_of_IoT_based_weather_s...

Compile Arduino Code:
---------------------
- Open ArduinoIDEcode.ino in Arduino IDE
- Select Arduino Uno as the board
- Click Verify to compile
- Note the .hex file path generated after compilation

Proteus Simulation:
-------------------
- Open Weather Monitoring Circuit.pdsprj in Proteus 8
- Load sketch_apr18a.ino.hex into the Arduino Uno component

Run Simulation:
---------------
- Click the Play button in Proteus
- Observe LCD updates every 2 seconds

Usage:
------
LCD displays:
- Temperature (°C)
- Humidity (%)
- Light Intensity (ADC value)
- Soil Moisture (ADC value)
- Rain Status on LCD:
    "RAINING..." if rain is detected
    "NO RAIN" if dry

## ✅ Notes 
- Ensure Proteus 8 Professional is installed to run simulations.
