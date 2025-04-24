# 🔐 RFID-Based Security/Lock System

## 📝 Overview
Simulate an RFID-based locking system using Arduino and Proteus.  
Valid RFID tags display user names on an LCD and activate a green LED.  
Invalid tags trigger a red LED and buzzer as an alert.

## 📂 Files Included
- `ArduinoIDEcode.ino` – Arduino code for RFID validation  
- `Card Numbers.txt` – List of valid RFID tag IDs  
- `Circuit.DSN` – Proteus circuit design file  
- `sketch_apr18b.ino.hex` – Compiled hex file for simulation

## ⚙️ Setup Steps


Clone Repository:
-----------------
git clone <your-repo-url>
cd RFID_Based_Security

Compile Arduino Code:
---------------------
- Open ArduinoIDEcode.ino in Arduino IDE
- Select Arduino Uno as the board
- Click Verify to compile
- Note the .hex file path generated after compilation
  (e.g., C:\Users\<YourName>\AppData\Local\Temp\...)

Proteus Simulation:
-------------------
- Open Circuit.DSN in Proteus 8 Professional
- Double-click the Arduino Uno component
- Load the sketch_apr18b.ino.hex file into the Arduino

Run Simulation:
---------------
- Click the Play button in Proteus
- Use the Virtual Terminal to enter RFID strings
  Example: HJKL9753QLCD

Usage:
------
- Valid RFID Tag:
    - Green LED lights up
    - LCD displays the associated user name
- Invalid RFID Tag:
    - Red LED turns on
    - Buzzer activates


## ✅ Notes
- Ensure you have Proteus 8 Professional installed for running the simulation.
