# Examples on how to control your Tello drone from laptop

## Steps to control the drone using Scratch
Windows:

1. connect to Tello via Wi-Fi
2. windows + R
3. cmd
4. cd THIS_FOLDER
5. node Tello.js
6. launch Scratch (https://scratch.mit.edu/download)
7. Shift + File->Import experimental HTTP extension
8. choose Tello.s2e
9. File -> Open -> keyboardcontrol
10. press "t" for takeoff

## Steps to control the drone using JavaScript
1. connect to Tello via Wi-Fi
2. launch Packet Sender (https://packetsender.com/)
3. Send 'command' to drone
4. Send 'battery?' to drone
5. python Tello3.py
6. start flying using commands from the Tello SDK 2.0 User Guide:
	(example)
	* takeoff
	* up 100
	* down 50
	* left 100
	* right 100
	* land
