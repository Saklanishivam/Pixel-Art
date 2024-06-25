# Addressable LED 8x8 Matrix Pixel Art Using ESP


## Project Overview
The **Addressable LED 8x8 Matrix Pixel Art Using ESP** project creates a visually captivating 8x8 LED matrix for displaying pixel art. Leveraging the ESP8266 microcontroller and WS2812B addressable LEDs, this project allows for the programming of custom animations and visual effects using the FastLED library, enhancing visual creativity and user interaction.

## Technologies Used
- **Microcontroller:** ESP8266
- **LEDs:** WS2812B Addressable LEDs
- **Programming Environment:** Arduino IDE
- **Library:** FastLED

## Features
- **Custom Animations:** Programmed various custom animations and visual effects.
- **High Brightness:** Utilizes WS2812B LEDs for bright and vivid displays.
- **User Interaction:** Allows for dynamic updates and interaction through ESP8266.

## Getting Started

### Prerequisites
* ESP8266 microcontroller (NodeMCU or similar)
* WS2812B addressable LEDs
* Arduino IDE installed on your computer
* FastLED library installed in Arduino IDE

### Installation

1. **Set up Arduino IDE:**
   * Install the Arduino IDE from [here](https://www.arduino.cc/en/Main/Software).
   * Open Arduino IDE and go to `File > Preferences`. In the "Additional Board Manager URLs" field, add:
     ```
     http://arduino.esp8266.com/stable/package_esp8266com_index.json
     ```
   * Go to `Tools > Board > Board Manager` and search for "ESP8266". Install the latest version.

2. **Install Necessary Libraries:**
   * In Arduino IDE, go to `Sketch > Include Library > Manage Libraries`.
   * Search for and install the following libraries:
     * ESP8266WiFi
     * FastLED

3. **Circuit Assembly:**
   * Connect the WS2812B LEDs to the ESP8266 according to the pin configuration.
   * Ensure proper power supply to the LEDs and the microcontroller.

### Code

1. **Download or clone this repository:**
   ```sh
   git clone https://github.com/Saklanishivam/Pixel-Art.git

