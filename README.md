The command is a "Quick and Easy" way to get a WiFi password. It's just up to you how are you going
to use it.

The command is legal and it may be removed from future Windows versions. It works only on known WiFi's, so an attempt to use this on WiFi that the device was previously not connected at will not work. 
Basically it displays information regarding to SSID you have choosen with password being in plain readable text.

To use this command, go to CMD on Windows. and type:

/: netsh wlan show profile "NAME OF WIFI" key=clear
