# homekit-forqueta-salaarea

This repository is based on the code and the examples provided by Maxim Kulkin.

https://github.com/maximkulkin/esp-homekit-demo

Detailed instructions on how to use the code found here can be found on Maxim's repository. It is the first thing to do before trying the code here.

The hardware used to this project is a BH1750 lux sensor that uses SCL and SCA pins in the ESP8266. It uses the ota-update and the LCM from https://github.com/HomeACcessoryKid/life-cycle-manager/tree/master/homekit%20integration


This code is set up to control 5 relays. 2 in one accessory and 3 as another one. So I can configure to 2 rooms in Home app. 2 toogles for the 2 relays; and a button (1, 2 and 3 presses) to control the other 3.
A custom pcb was designed.
