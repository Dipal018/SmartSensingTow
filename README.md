Title: Smart Sensing Tow

Description: An IoT application which detects the presence of car and sends SMS to towing company once the parking time limit is expired. Used proximity sensors, Samsung ARTIK boards as hardwares,  Node-red, node.js as backend, MongoDB, ARTIK cloud for data management and NodeJS and ExpressJS for web interface.
Implemented a mechanism which enables the user to park their car for a limited amount of time as per the rule. Used motion sensor to measure the movements of car parked at a parking space which has bounded time restriction.  If the car is parked for more than X time then a message will be sent to the towing company to tow the car from that parking spot. Therefore, it will mainly focus on reducing the time and efforts of towing company and also it avoids accidental death in parked car.

Components:

Microcontroller-based sensor module
ARTIK cloud
User-facing web application

Prerequisites:

Samsung ARTIK 520 board
Proximity Sensors
Node-Red
Twilio

Screenshots:

Final Node-red Flow:

![Alt text](https://i0.wp.com/dipalsblog.files.wordpress.com/2018/04/dd.png?ssl=1&w=450 "Optional title") 

Web interface:

![Alt text](https://i2.wp.com/dipalsblog.files.wordpress.com/2018/04/ddd.jpeg?ssl=1&w=450 "Optional title")

(1) For windows user : pre-install PuTTY.
PuTTY (http://www.putty.org/) – SSH and Telnet client, for serial console access

(2) Establish an ARTIK Cloud user portal account: We will stream data to ARTIK Cloud service. Create an account at ARTIK Cloud user portal (https://artik.cloud/).

Setup:
(1) Access ARTIK from your serial console. Instructions is at https://developer.artik.io/documentation/developer-guide/artik-ide/serial-debug.html

(2) Set up WiFi on your ARTIK
https://developer.artik.io/documentation/developer-guide/ethernet-wifi/wifi.html

(3) Install MongoDB and setup.

(4) Create rules in ARTIK cloud and connect it with Node-red nodes.

(5) Write codes for Node-red nodes in Node.js 

Demo:
https://www.youtube.com/watch?v=6xzf1go26Vw&feature=youtu.be
