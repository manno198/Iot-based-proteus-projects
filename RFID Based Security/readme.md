Overview
Simulate an RFID-based locking system using Arduino and Proteus. Valid RFID tags display user names on an LCD and activate a green LED; invalid tags trigger a red LED and buzzer.

Files Included
ArduinoIDEcode.ino: Arduino code for RFID validation
Card Numbers.txt: List of valid RFID IDs
Circuit.DSN: Proteus circuit design
sketch_apr18b.ino.hex: Compiled hex file
Setup Steps
Clone Repository :
bash
'''
git clone <your-repo-url>  
cd RFID_Based_Security  '''

Compile Arduino Code :
Open ArduinoIDEcode.ino in Arduino IDE.
Select Arduino Uno as the board.
Click Verify to compile.
Note the .hex file path (e.g., C:\Users\<YourName>\AppData\Local\Temp\...).
Proteus Simulation :
Open Circuit.DSN in Proteus 8 Professional.
Double-click the Arduino Uno component → Load sketch_apr18b.ino.hex.
Connect components as per the schematic (refer to Circuit.DSN).
Run Simulation :
Click Play to start.
Use the Virtual Terminal to input RFID strings (e.g., HJKL9753QLCD).
Usage
Valid ID : Green LED glows, LCD shows name.
Invalid ID : Red LED + buzzer activate.