# wildcard
compass for safer adventures.

*Your compass for safer adventures — a connected pocket + wearable safety system for travel and forest treks.*

## How the system works

Forest Guardian is a two device safety system being developed for travellers, trekkers, campers, and outdoor users.

The project combines a **Raspberry Pi 5 pocket/bag module** with an **ESP32-S3 wearable watch**.

### Pocket / Bag Module — Raspberry Pi 5

The Raspberry Pi 5 acts as the main processing unit of Forest Guardian.

The current prototype is being developed to handle:

- PIR motion sensing
- DHT11 temperature and humidity monitoring
- Raspberry Pi Camera capture
- local event logging
- warning and SOS events
- sensor data processing
- a local dashboard
- communication with the wearable module

The dashboard is planned to run locally on:

```text
http://PI_IP_ADDRESS:8080
```

Some of these functions are still being integrated and tested.

### Wearable Watch — ESP32-S3

The ESP32-S3 wearable is designed to provide quick access to personal safety functions.

The current development includes:

- SOS push button
- 2-second SOS activation
- MPU6050 motion sensing
- raw pulse-sensor monitoring
- OLED status display
- red warning LED
- white LED
- vibration alert
- future communication with the Raspberry Pi

The watch firmware is being designed to send structured data to the Raspberry Pi so both modules can eventually operate as one connected system.

## Prototype and future production system

Forest Guardian is being developed in two stages.

### Prototype

The first version uses hardware that is already available and can be tested directly.

Examples include:

- Raspberry Pi 5
- ESP32-S3
- Raspberry Pi Camera
- PIR sensor
- DHT11
- MPU6050
- MQ-2
- hobby pulse sensor
- OLED display
- LEDs
- push buttons
- vibration motor
- phone-assisted location

### Future production version

Later versions may use more advanced hardware such as:

- dedicated GNSS
- LTE / 4G communication
- LoRa communication
- thermal imaging
- low-light cameras
- professional air-quality sensors
- higher-quality PPG sensors
- battery fuel gauges
- waterproof enclosures
- secure encrypted logging
- authenticated remote communication

These features are part of the roadmap and should not be considered installed until they have actually been integrated and tested.

## Project status

**WILDCARD is currently under active development.**

The hardware prototype is not finished yet.

The repository will be updated as each sensor, module, communication method, and software feature becomes physically tested and working.
