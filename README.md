# Arduino RFID Card Reader with OLED Display

This project implements an RFID card reader using an Arduino, MFRC522 RFID module, and an OLED display. It provides a user-friendly interface for reading RFID cards and displaying their information.

## Table of Contents

- [Features](#features)
- [Hardware Requirements](#hardware-requirements)
- [Software Requirements](#software-requirements)
- [Pin Connections](#pin-connections)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- Reads RFID cards using the MFRC522 module
- Displays card information on an OLED screen
- Shows card UID, type, size, and SAK value
- Attractive UI with framed display
- Serial output for debugging

## Hardware Requirements

- Arduino board (Uno, Nano, Mega, etc.)
- MFRC522 RFID module
- SSD1306 OLED display (128x64 pixels)
- RFID cards/tags (Mifare 1K, etc.)
- Jumper wires

## Software Requirements

- Arduino IDE
- Required libraries:
  - SPI
  - Wire
  - Adafruit_GFX
  - Adafruit_SSD1306
  - MFRC522

## Pin Connections

| Component | Arduino Pin |
|-----------|-------------|
| MFRC522 RST | 9 |
| MFRC522 SDA (SS) | 10 |
| MFRC522 MOSI | 11 |
| MFRC522 MISO | 12 |
| MFRC522 SCK | 13 |
| OLED SDA | A4 |
| OLED SCL | A5 |

Note: Pin connections may vary depending on your Arduino board. Please refer to the datasheet of your specific board for accurate pin mapping.

## Installation

1. Clone this repository or download the ZIP file.
2. Open the Arduino IDE.
3. Install the required libraries through the Library Manager.
4. Open the `RFID_Reader_OLED.ino` file.
5. Select your Arduino board and port in the IDE.
6. Upload the sketch to your Arduino.

## Usage

1. Power up your Arduino with the connected MFRC522 module and OLED display.
2. The OLED screen will show a waiting message.
3. Present an RFID card to the MFRC522 module.
4. The card's information will be displayed on the OLED screen and sent to the Serial Monitor.
5. To read another card, simply present it to the module.

## Contributing

Contributions to this project are welcome. Please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature.
3. Make your changes and commit them with descriptive messages.
4. Push your changes to your fork.
5. Submit a pull request.

## License

This project is released under the MIT License. See the [LICENSE](LICENSE) file for details.
<img src="promo1" alt="Wardriver project" width="300"/>
<br>
<img src="promo2" alt="Wardriver project" width="300"/>
