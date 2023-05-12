# PLEASE READ FIRST BEFORE COPYING THE CODE: Arduino-ESP8266-Store-Data-To-Firestore
A code for arduino ESP8266 to store data from the microcontroller and sends it to the Firestore; Tested on Wemos Arduino D1 R1/R2/D3 ESP8266 

Reminders:
1. Make sure to install the necessary Libraries for your Sensors.
2. Make sure you have the correct board type (LOLIN Wemos D1 R1/R2 & Mini).
   > To install the correct board type
   > click "files"
   > select "preferences"
   > find additional board manager URL
   > copy this path and put it in the board manager URL: http://arduino.esp8266.com/stable/package_esp8266com_index.json
   > click "apply" or "ok"
   > go to tools
   > go to board manager
   > search and find "LOLIN Wemos D1 R1/R2 & Mini" (that is, if your board is the Arduino Wemos D1 R3 or the ESP8266)
3. Make sure you connected your board to your Laptop / PC with a USB cable (make sure your USB cable is not broken and is detected by your PC / Laptop.
4. For Libraries (you can go and click tools then manager libraries). 
   > For DHT11 you can install
      *Simple DHT11
      *DHT11 for Arduino,
   > For Soil Moisture Sensor
      *Soil Moisture Sensor Library,
   > For Firestore / Firebase (Very Important)
      *Find "Firebase RTDB Arduino Library for ESP8266 and RP2040 Pico" by mobizt (I specifically use this one)
      or Find "ESP8266 for Firebase" by mobizt
5. Copy and Paste all the code into your Arduino IDE, don't forget to save it before editing the code, always read the comments in the code to avoid errors.
6. After you are done with your code, you can press "Upload", "Upload" is simliar to "build / run" in VSCODE. 


Note:
We do not have the same sensors and pin wirings, you have to figure that out on your own about what libraries you need for specific sensors you have and figure the map of your ESP8266 board, you also need to familiarize your wirings as they are important to your code, I also do not use a breadboard, you can search about that breadboard connections if you are using one. REMEMBER: if you encounter and error, just search it in google.
    
