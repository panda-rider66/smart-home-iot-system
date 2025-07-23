# Smart Home Automation System

This project is a smart home automation system designed using ESP32, Raspberry Pi 4B, and AWS IoT Core. It allows real-time environmental monitoring and appliance control with cloud integration and local visualisation.

## 🚀 Features

- Sensor data collection (temperature, humidity, gas, rain, motion)
- Appliance control (relays, servos, LEDs, buzzers)
- MQTT communication via Mosquitto broker
- Local InfluxDB storage with Grafana dashboards
- Cloud publishing to AWS IoT Core via TLS-secured Python bridge
- Resilience via local fallback storage and auto-reconnect logic

## 🛠️ Technologies

- Arduino IDE (ESP32 programming)
- Python 3 (MQTT bridge)
- InfluxDB + Grafana
- AWS IoT Core
- Mosquitto MQTT Broker
