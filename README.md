# **ESP8266 NodeMCU WebServer**

I used ESP8266 NodeMCU, but it can be used in other versions.You can find esp8266_WebServer examples in the examples folder

    
## Arduino IDE Settings
I assume you have Arduino IDE on your system. However, the ESP8266 we will be using does not come in the standard installation of the IDE, so we will have to do some additional processing.

Let's add the following address to the `Additional Circuit Boards Manager URLs` section from the `File>Preferences` menu.

http://arduino.esp8266.com/stable/package_esp8266com_index.json    
    
Then find and install ESP8266 from `Tools>Card>Card` Manager:

<img src="https://user-images.githubusercontent.com/109466846/198565319-19e2d64e-f06d-45c4-9466-2b85cd11ef6f.png" width="720" height="415" />

    
Next we need to add ESP8266WebServer, the only library we will use. `Draft > add library > manage libraries`
    
<img src="https://user-images.githubusercontent.com/109466846/198567317-30eaa4e2-0a3d-4f4b-a474-1445bd58a2e7.png" width="720" height="415" />
    

