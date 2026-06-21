# Smart-Environment-Dashboard---Node-Red
A live IoT monitoring and control system developed with Node-RED and AWS IoT Core. The project collects multi-sensor data streams via MQTT, processes them into environmental parameters (temperature, humidity, air quality, etc.), and provides a responsive dashboard with alarms and actuator control (LEDs, audio).

# Smart-Environment-Dashboard---Node-Red
A live IoT monitoring and control system developed with Node-RED and AWS IoT Core. The project collects multi-sensor data streams via MQTT, processes them into environmental parameters (temperature, humidity, air quality, etc.), and provides a responsive dashboard with alarms and actuator control (LEDs, audio).

## Introduction
SmartEnv Dashboard is an IoT project that integrates Node-RED with AWS IoT Core to provide a live monitoring and control system. It collects multi-sensor data streams (Temperature, Humidity, Pressure, CO2, UV, Light, Soil, Air Quality) and enables real-time visualization and actuator control (LEDs, audio alerts).

## Features
- Real-time sensor data streaming via MQTT.
- Interactive dashboard for environmental parameters.
- Automated alarms and notifications (LED indicators + audio).
- Cloud integration with AWS services for data storage and processing.
- Modular Node-RED flow for easy customization and expansion.

## Tech Stack
- Node-RED (IoT orchestration & dashboard)
- MQTT protocol (data communication)
- AWS IoT Core (cloud integration)
- JavaScript functions (custom logic)

## Demo
**Sensors**: Temperature, Humidity, Pressure, Light, Soil, CO2, UV, Air Quality
**Outputs**: LEDs (status indicators), Audio alerts

## Setup
1. Install Node-RED locally or on a server.
2. Configure MQTT broker and connect sensors.
3. Deploy AWS IoT Core for cloud integration.
4. Import the provided Node-RED flow JSON.
5. Run the dashboard and start monitoring.

## Future Work
- Add predictive analytics with Machine Learning models.
- Enhance UI with advanced charts and responsive design.
- Extend support for mobile-friendly dashboards.
