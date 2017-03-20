Customized Arduino core for WEMOS XI Boards
===========================================
### Difference
* AREF pin to be used as digital IO (E6)
* Added analogReadResolution function, and 12bit ADC can be used.

### WEMOS XI Boards
- [WEMOS XI](https://wemos.cc "WEMOS XI")

### Installation
- Install Arduino IDE
- Go to Arduino IDE installation directory
- Clone this repository into **hardware/wemos/XI** directory (or clone it elsewhere and create a symlink)
```bash
cd hardware
mkdir wemos
cd wemos
git clone https://github.com/wemos/Arduino_XI.git XI
```
- Restart Arduino
