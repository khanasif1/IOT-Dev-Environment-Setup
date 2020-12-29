# IOT Dev Environment Setup
![Arduino](https://github.com/khanasif1/IOT-Dev-Environment-Setup/blob/main/images/Banner7_Arduino.png)
#### This repository has steps on configuring the Arduino IDE environment, for building solution with :
* Arduino Board
* ESP8266 Board
* ESP 32 Board
  
<hr/>

# Steps to Setup
* Install Arduino from [Arduino Downloads](https://www.arduino.cc/en/Main/OldSoftwareReleases#00xx) I used V-1.8.8 Windows
`http://arduino.esp8266.com/stable/package_esp8266com_index.json`

* Under Preferences-->Settings updated Board Manager URL 
![Arduino](https://github.com/khanasif1/IOT-Dev-Environment-Setup/blob/main/images/ESP8266JsonUrl.PNG)

* Using Tool--> Board Manager install ESP8266 board
![Arduino](https://github.com/khanasif1/IOT-Dev-Environment-Setup/blob/main/images/AddBoard.PNG)

* Verify the ESP8266 baord version - 2.5.0 the code sample I have build and library references works perfect with this version.
![Arduino](https://github.com/khanasif1/IOT-Dev-Environment-Setup/blob/main/images/Esp8266BoardVersion.PNG)

* Copy the [library folder](https://github.com/khanasif1/IOT-Dev-Environment-Setup/blob/main/images/CopyLibraryFoldertoThis.PNG) to your Arduino libraries folder location.
![Arduino](https://github.com/khanasif1/IOT-Dev-Environment-Setup/blob/main/images/CopyLibraryFoldertoThis.PNG)

* You are all set to build solution for Arduino or ESP8266 board