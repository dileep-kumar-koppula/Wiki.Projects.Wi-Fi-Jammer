1. Download the platform [Arduino IDE](https://www.arduino.cc/en/main/software). Install it and open the Arduino IDE Application.
2. [Download](https://github.com/SpacehuhnTech/esp8266_deauther/archive/v2.zip) the source code for this project.
3. Extract the `.zip` file, navigate to `esp8266_deauther` folder and open `esp8266_deauther.ino` with Arduino.
4. In Arduino go to `File` > `Preferences` add this URL to the `Additional Boards Manager URLs` :
[https://raw.githubusercontent.com/SpacehuhnTech/arduino/main/package_spacehuhn_index.json]()
5. Go to `Tools` > `Board` > `Boards Manager`, search `deauther` and install `Deauther ESP8266 Boards`.
6. Select your board at `Tools` > `Board` and be sure it is at `Deauther ESP8266 Boards` (and not at ESP8266 Modules).
7. Depending on your board, you might have to select a configuration setting at `Tools` > `Deauther Config`
8. If you need to reset the settings from a prior installation, make sure to select `Tools` > `Erase Flash` > `All Flash Contents`
9. Check your upload settings and press upload.
