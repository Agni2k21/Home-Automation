# Home-Automation System with Voice Control

This project aims to control electrical and electronic devices such as Light, fan, TV, etc. 
This is done using Arduino and the relay circuit which is installed at each room of the house. 
The Data will be published to Arduino via Bluetooth module and further implementations can be made.
The primary task would be acquiring the data and publishing it to the Arduino using a mobile.
And later with the data, a control can be made to switch on/off the devices.

### Step 1: Parts and Material

The Components needed for this project are:

•Arduino
•Relay Breakout board
•Bluetooth Module - HC-05
•Jumper Cables

### Step 2: Connections
The Following connections are made using the Jumper cables. 
For this demo, I've used four relays which means four devices can be controlled using the APP.

#### * Arduino -> BT MODULE *

TX -> RX
RX -> TX
VCC -> 3.3v
GND -> GND

#### * Arduino -> Relay Board *

IN1 -> D2
IN2 -> D3
IN3 -> D4
IN4 -> D5
VCC -> VCC
GND -> GND

### Step 3: The Code

### Step 4: Application

For now we will use the ready-made application.

#### BT Voice Control for Arduino created by SimpleLabsIN:
(https://apkpure.com/bt-voice-control-for-arduino/robotspace.simplelabs.amr_voice/download?from=details)
