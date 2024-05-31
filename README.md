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

