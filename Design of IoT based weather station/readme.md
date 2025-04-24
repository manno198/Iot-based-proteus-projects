Overview
Simulate a weather monitoring system using DHT11, LDR, soil moisture, rain sensors, and LCD. Displays real-time temperature, humidity, light, soil moisture, and rain status.

Files Included
ArduinoIDEcode.ino: Arduino code for sensor readings
Weather Monitoring Circuit.pdsprj: Proteus project file
sketch_apr18a.ino.hex: Compiled hex file
Setup Steps
Clone Repository :
bash
'''
git clone <your-repo-url>  
cd Design_of_IoT_based_weather_s...  '''

Compile Arduino Code :
Open ArduinoIDEcode.ino in Arduino IDE.
Compile for Arduino Uno.
Note the .hex file path.
Proteus Simulation :
Open Weather Monitoring Circuit.pdsprj in Proteus.
Load sketch_apr18a.ino.hex into the Arduino Uno component.
Connect sensors:
DHT11 → Pin D4
LDR → A1 (with 10kΩ resistor)
Soil Moisture → A2
Rain Sensor → D2
Run Simulation :
Click Play .
Observe LCD updates every 2 seconds.
Usage
Displays: Temperature (°C), Humidity (%), Light (ADC value), Soil Moisture (ADC value).
Rain status: "RAINING..." or "NO RAIN" on LCD.