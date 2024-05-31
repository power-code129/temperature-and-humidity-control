# temperature-and-humidity-control
To check the temperature and humidity control in the esp32 wifi module and dht11sensor

## 1) Hardware Connections:
i) Esp32 GND to Dht11 GND

ii) Esp32 3V3 to Dht11 VCC

iii) Esp32 Digital pin 27 to Dht11 DATA

## 2) Software Connection:
i) Create a new Arduino sketch and include the DHT.h library.

ii) Initialize the DHT object with the appropriate PIN and sensor type (DHT11 or DHT22).

iii) In the setup() function, initialize the DHT object and set up the serial monitor.

iv) In the loop() function, read the temperature and humidity values using the DHT object methods and print them to the serial monitor.

## 3)Program code
Please take a look at the code on code.cpp

## 4)Upload the Code:
i) Connect your ESP32 to your computer via USB.

ii) Select the correct board (e.g., DOIT DEV ESP-32) and COM port in the Arduino 
IDE.

iii) Upload the code to your ESP32.

## 5) Monitor the Readings:
i) Open the Serial Monitor in the Arduino IDE (baud rate: 9600).

ii) You’ll see the temperature and humidity readings displayed in real time.

## 6) Testing:
i) Open and log in to the Blynk IoT app 

ii) Create the web template and get the auth token 

iii) Then the copy and paste to the Arduino code 

iv) Run the code

