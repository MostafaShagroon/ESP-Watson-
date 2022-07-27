# ESP-Watson-
connecting the ESP piece into my personal laptop with Arduino and to the phone



# ESP Watson 32
## the physical connection
###  connecting a USB to micro-USB cable from the ESP by a micro into a laptop using the USB and making sure that the blinkers on the ESP is on and a notification on the laptop should appear connected if not connected go to next step where I will explain this problem and how to fix it other than that skip the next step 
## if the port is not visible 
### After connecting the ESP with a usb the laptop might doesn't recognize the device to get it configured using Arduino (we will talk about in the next step ) so to fix that problem we are going to the setting on your operating system in our matter is Windows 10 from the Windows button to setting and then look for (About your PC) on that page on the top right you will find Device Manager you will find under universal serial bus controllers a port that have yellow exclamation mark just right Click and update the driver manually and search on google for the driver and download it from https://www.silabs.com/developers/usb-to-uart-bridge-vcp-drivers and place the path of it in the section to update the driver thin it will appear everywhere even on Arduino
## Setting Arduino
### download Arduino from https://www.arduino.cc/en/software choose to correct link based on your system this is just an IDE that connects to robots and it uses C based language for the script.
## adjusting ESP 32 on Arduino 
### to make Arduino identify the ESP 32 to have to select Tools > Board > Board Manager > then Search for a ESP 32 to press install it is actually a package that allow you to controls the ESP 
### after that you have to do other step from file > preference > next to additional board Manager URLs: to paste this one https://dl.espressif.com/dl/package_esp32_index.json
## starting the script 
### in Arduino it has a simple Example of codes you can select from, in our task we want to make sure the ESP32 is working and since it has a led on it we want from the led to blink in a deferent frequencies to do that from file >  examples > Basic > Blink . That to initiate the code that makes the blinker goes on and off in a deferent frequencies as you write the speed in ms . 

made by mostafa as a task on IOT for the Summer Training with Smart Methods  
   
