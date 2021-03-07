# Home-Automation-using-ESP8266-and-Alexa

Home Automation has become vital in today's busy world but not all of us have smart appliance which has inbuilt wifi module in them, and buying one newly is going to shoot up the cosst

ESP8266 is a wifi module with 12 gpio pins this can be used to get instruction from an Alexa or google assisstant device.

The wifi module communicates with the Alexa through http protocol. once the wifi module gets instruction it then processes and triggers the Ir sensor to produce the particular infrared signal to switch the devices on and off.

nodered platform is also setup to couple up with the espmodule which is running on a ec2 instance(AWS), this provides the instataneous and permonth data of units of current consumed, provides a graphical data and the appliances can also be used from any part of the world through internet


You can download the board for ESP8266 NodeMCU (2.5.1) from : https://github.com/esp8266/Arduino


**libraries:**
* ESPWIFI
* Espalexa
* WIFI
* Irremote
