# 🔥 LPG Gas Leakage Detection System

## 📝 Overview
Simulate an LPG gas leak detection system using an MQ-4 sensor, LEDs, buzzer, and LCD.  
The system provides alerts via visual (LEDs, LCD) and audible (buzzer) signals when gas is detected.

## 📂 Files Included
- `ArduinoIDEcode.ino` – Arduino code for gas detection  
- `gas leakage detector.pdsprj` – Proteus project file  
- `sketch_apr14a.ino.hex` – Compiled hex file

## ⚙️ Setup Steps

Clone Repository:
-----------------
git clone <your-repo-url>
cd LPG_Gas_leakage_detector_syst...

Compile Arduino Code:
---------------------
- Open ArduinoIDEcode.ino in Arduino IDE
- Select Arduino Uno as the board
- Click Verify to compile
- Note the .hex file path generated after compilation

Proteus Simulation:
-------------------
- Open gas leakage detector.pdsprj in Proteus 8
- Load sketch_apr14a.ino.hex into the Arduino Uno component

Run Simulation:
---------------
- Click the Play button in Proteus
- Simulate gas leakage by setting MQ-4 output to HIGH (use logic toggle or manual override)

Usage:
------
- No Gas:
    Green LED is ON
    LCD displays "NO GAS DETECTED"
- Gas Detected:
    Red LED blinks
    Buzzer activates(Blue LED is used as buzzer)
    LCD displays gas alert message


## ✅ Notes
- Make sure Proteus 8 Professional is installed for simulation.
