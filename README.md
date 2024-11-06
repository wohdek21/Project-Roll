[Русская версия](https://github.com/wohdek21/Project-Roll/blob/main/READMErus.md)

# Project Roll
### Welcome to world rolling.
This is the handheld mini pc with raspberry pi 4 inside. It's fully customizable and open source.

## System
You can install Any system you want from Windows 11 ARM to Kali linux.          
For Windows 11 thanks to [WoR Flasher](github.com/Botspot/wor-flasher) team.           
Linux is supported natively.            
## RollUI
Also, Project Roll uses RollUI as a program to work with other modules.  

# Functions
This project also contains Flipper Zero's functions such as RFID Cloning or emulating, NFC Reading and Writing, IR Reading and emulating and Radio reading and emulating.    
If you want for Roll to be without these functions, alright it's all your selection. Also there are some USB Type-C and Mini HDMI for connecting keyboard, mouse and monitor.

# Parts
- First and main part is Raspberry Pi 4. This is the brains of our Roll. Also do not install version with RAM smaller than 4GB, some systems may not boot.  
- Second is a Touchscreen. You can install version with 4inch screen size or 3.5 inches or smaller! I recomending to install 4 inched for best image size and quality. Display connects by SPI on Raspberry's GPIO pins.
> [!NOTE]
> Next 2 parts are not necessary.
- Third is PN532 module. He gives you powers to emulate, write and read 13.56 Mhz RFID card and NFC points.  
- and last is Radio CC1101 module. He can transmit or receive signal from 433 Mhz frequency.  

#Ending
This is not a normal PC. Roll can not replace normal computers, but work as handheld station he does at 100%.
