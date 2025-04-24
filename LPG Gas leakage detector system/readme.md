Overview
Simulate an LPG gas leak detection system using MQ-4 sensor, LEDs, buzzer, and LCD. Alerts via visual/audible signals and LCD messages.

Files Included
ArduinoIDEcode.ino: Arduino code for gas detection
gas leakage detector.pdsprj: Proteus project file
sketch_apr14a.ino.hex: Compiled hex file
Setup Steps
Clone Repository :
bash
'''
git clone <your-repo-url>  
cd LPG_Gas_leakage_detector_syst...  '''

Compile Arduino Code :
Open ArduinoIDEcode.ino in Arduino IDE.
Compile for Arduino Uno.
Note the .hex file path.
Proteus Simulation :
Open gas leakage detector.pdsprj in Proteus.
Load sketch_apr14a.ino.hex into the Arduino Uno component.
Connect MQ-4 sensor (A0), LEDs (pins 9,10,11), and LCD (4-bit mode).
Run Simulation :
Click Play .
Trigger gas detection by setting MQ-4 output to HIGH (via Proteus logic).
Usage
No Gas : Green LED ON, LCD shows "NO GAS DETECTED".
Gas Detected : Red LED blinks, buzzer activates, LCD alerts.