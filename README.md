# 2018-NodeMCU-LolinV3-Setup
How to set up and run the board

#NodeMCU Lolin V3

Manual:
http://bibliothek.az-delivery.de/wp-content/uploads/2018/02/NodeMCU-Lua-V3-Lolin_Englisch.pdf

Install drivers:
- Windows: http://www.wch.cn/download/CH341SER_ZIP.html
- Mac: http://www.wch.cn/download/CH341SER_MAC_ZIP.html

Open Arduino, preferences, add additional devices url:
http://arduino.esp8266.com/versions/2.4.0/package_esp8266com_index.json

On Arduino IDE, add board definition and configure it:
- Arduino > Tools > Board Manager > Add esp8266
- Arduino > Tools > Flash Size > 4M (3M SPIFFS)
- Arduino > Tools > CPU Frequency > 80 MHz
- Arduino > Tools > Upload Speed > 115200

Select your port on:
- Arduino > Tools > Port

Test your board compiling and running the provided blink example ;)


