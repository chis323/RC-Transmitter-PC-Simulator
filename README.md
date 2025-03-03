Tought it would be nice to share a little project that I really enjoyed making and using day to day. So to start things off, this is for people that want to get into RC Racing and they do not want to spend alot of money and then finding out they don't actually enjoy it that much or for those that want to practice at home for when it is raining outside or even if you just don't have the chance to go to the track in some days. The VRC PRO simulator is free to use (with limited tracks and classes) but you will indeed need an adaptor in order to use your own RC Radio. Searching trough the internet you will find that the original USB device is out of stock and that there are some 30 euro versions for sale on Ebay, etc. Well you can make your own adapter with few easy steps and get started in the RC world.



Steps:
1. Install Arduino IDE 2.3.2.
2. Add the Joystick library from the ArduinoJoystickLibary folder. I did this by copying the Joystick folder and pasting it into the Libraries folder of my Arduino documents.
3. Start Arduino IDE and open the RCUSB sketch.
4. Plug in Arduino Micro into USB port.
5. Select Tools>Board>Arduino/Genuino Micro.
6. Select Tools>Port>Arduino Micro.
7. Select the “Check” Verify button to compile the sketch.
8. Select the “Arrow” Upload button to upload to the Arduino.
9. Search in the Windows Search bar for "Set up USB game controllers".
10. Properties>settings>calibrate.
11. Start Radio.
12. Start VRC and open the Controller Options menu in order to finish the setup of the Radio there ( eg. End Points ).



For the Software part I will drop the necessary links:
Arduino download: https://www.arduino.cc/en/software
Simulator: https://vrcworld.com/ (or buy using a Steam Account)
ARDUINO AND LIBRARIES are inside the folder

P.S. I know that there are other tutorials, but they are more complicated and/or for 4ch+ Receivers and so that's why I decided that there should be no biggie to make a simplified and clear version of tutorial to create the VRC adapter. Also this simulator is not the only one that can use the Radio transmitter, it works with other games too and it can be adapted to pretty much any Receiver-Transmitter Combo even if it they are for other Drone / Aero / Boat RC simulators.
