# LPG-Gas-Leakage-Detector-Using-Node-MCU-With-Blynk-Application

How It Works:-
Here we use an MQ-2 gas sensor that detects the LPG, Alcohol, Smoke, etc, gases. If there is a gas in the air the resistance between two electrodes of the gas sensor gets increased according to the gas presence. We use node MCU as a microcontroller or a wifi development board that reads the analog values from the gas sensor. In the code, we set the gas value [200]. The node MCU sends these analog values to the Smartphone to the Blynk application. when the gas value gets increased above 200 the app shows the notification "Gas Detected".

_____________________________________________________________________________
To make this project we need some components (Best Buy Links are Provided):-
1.	NodeMcu ESP8266
2.	MQ-2 Gas Sensor
3.	Breadboard
4.	Jumper Wires

_____________________________________________________________________________
Refer to the above circuit diagram to make a connection
NodeMcu ---- MQ-2 Sensor
A0 >> A0 (Analog Pin)
G >> GND
3v3 >> VCC

______________________________________________________________________________
Let's Setup the BLYNK app:-
1.	Install Blynk App from google play store.
2.	Create Account On Blynk.
3.	Create New Project.
4.	You will get Token on your E-Mail.
5.	Give Name to Project.
6.	Select Hardware (NodeMcu) & Connection Type (WIFI)& click on Create Button.
7.	Add gauge using Widget Box.
8.	Gave name to the Gauge as "Gas Value", Select Pin > Virtual > V2, Push > 1Sec.
9.	Add Notification using Widget box.
10.	Now Application Setup is done.

______________________________________________________________________________

