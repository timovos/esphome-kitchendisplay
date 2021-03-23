# ESPHome Kitchen display

The purpose of this display is to show the dishwasher time (based on electricity measurement of plug) and showing the amount of days until a waste container needs to be offered for emptying.

In idle, it shows the garbage, when service `start_vaatwasser` with parameter `running_time_seconds` is called, a countdown is shown. Upon finished, garbage is shown again.

## Hardware

- Espressif ESP32 (WROOM32 / NodeMCU / devkit v1)
- Wemos 2.4 inch TFT Shield (driver: ili9341)

## Software

- HomeAssistant
- ESPHome 1.16.2
