# varnalab-rfid-controller

## Modules
* RC522 Reader - [go to Aliexpress](https://www.aliexpress.com/wholesale?isFreeShip=y&SearchText=arduino+RC522+module&SortType=price_asc)
* ENC28J60 Ethernet - [go to Aliexpress](https://www.aliexpress.com/wholesale?isFreeShip=y&SearchText=arduino+ENC28J60+module&SortType=price_asc)

## Libraries
Install from Sketch > Include Library > Manage Libraries
* MFRC522
* UIPEthernet
* thinger.io

## Wiring

Wiring will change when project evolves as currently we're testing this separately.

### RC522 Reader
Pin	| Wiring to Arduino Uno
--- | ---------------------
SDA | Digital 10
SCK | Digital 13
MOSI | Digital 11
MISO | Digital 12
IRQ | unconnected
GND | GND
RST | Digital 9
VCC | 3V3 or 5V5 depending on your module

### ENC28J60 Ethernet
Pin	| Wiring to Arduino Uno
--- | ---------------------
CS | Digital 10
SI | Digital 11
SO | Digital 12
SCK | Digital 13
INT | Digital 2
VCC | 3V3 or 5V5 depending on your module
GND | GND

## Credits
MFRC522 Project url: https://randomnerdtutorials.com/security-access-using-mfrc522-rfid-reader-with-arduino/
- Created by FILIPEFLOP
- Modified by Rui Santos
- Modified by Ivan Popjelev (added networking support & improvements)
