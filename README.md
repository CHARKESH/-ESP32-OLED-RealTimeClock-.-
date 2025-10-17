# ESP32 Real-Time Digital Clock with OLED Display

This project uses an ESP32 microcontroller, a 128x64 SSD1306 OLED display, and WiFi/NTP to show the current time in real-time.
It is designed for easy testing in the Wokwi online simulator.

## Circuit Connections

| OLED Pin | ESP32 Pin |
|----------|-----------|
| VCC      | 3.3V      |
| GND      | GND       |
| SCL      | GPIO 22   |
| SDA      | GPIO 21   |

## Features

- Fetches current time from NTP server over WiFi
- Displays time on 128x64 OLED screen
- Designed for Wokwi simulator (use "Wokwi-GUEST" WiFi)

## Usage

1. Clone this repository or download the code file below.
2. Open in Arduino IDE or Wokwi simulator.
3. No password is required for WiFi in Wokwi: use SSID "Wokwi-GUEST".

## Libraries Needed
- Adafruit SSD1306
- Adafruit GFX
- NTPClient (ESP8266)
