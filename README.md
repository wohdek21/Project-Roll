[Русская версия](https://github.com/wohdek21/Project-Roll/blob/main/READMErus.md)

# Project Roll
### Welcome to world rolling.
This is the handheld mini pc with raspberry pi 4 inside. It's fully customizable and open source. Also functions as a pentester

## System
You can install Any system you want from Windows 11 ARM to Kali linux.          
For Windows 11 thanks to [WoR Flasher](github.com/Botspot/wor-flasher) team.           
Linux is supported natively.            

## RollUI
Also, Project Roll uses RollUI as a program to work with other modules.  

### RollOS
RollOS is a system based on Windows that runs RollUI in full-screen mode and on startup.    
In this system, RollUI has a function called "Leave to Desktop". It simply closes RollUI and displays the basic Windows desktop.     
It's like SteamOS!    

# Functions
This project also contains Flipper Zero features such as:

- emulation, reading and writing of RFID cards at 13.56 Mhz.
- emulate, read, and write NFC tags.
- emulation and reading of the IR signal.
- receiving and transmitting a radio signal at a frequency of 433MHz.

If you want Roll to be without these features, well, it's all up to you.   
And also there are some USB Type-C and Mini HDMI for connecting keyboard, mouse and monitor.   

# Parts
- First and main part is Raspberry Pi 4. This is the brains of our Roll.
> [!WARNING]
> Do not install a Raspberry Pi with less than 4 GB of RAM. Some systems may experience boot issues.
- Second is a Touchscreen. You can install version with 4inch screen size or 3.5 inches or smaller! I recomending to install 4 inched for best image size and quality. Display connects by SPI on Raspberry's GPIO pins.
> [!NOTE]
> Next 2 parts are not necessary.
- Third is PN532 module. He gives you powers to emulate, write and read 13.56 Mhz RFID card and NFC points.  
- and last is Radio CC1101 module. He can transmit or receive signal from 433 Mhz frequency.  

# Goals
- [x] Select hardware to use
- [ ] Get and assemble hardware
- [ ] Make all of the functions
- [ ] Try installing both linux and windows for some tests
- [ ] Make RollUI and add it to system iso
- [ ] Add some aesthetic to project 🤩
- [ ] Make RollOS
> [!NOTE]
> Goals may be updated some times
