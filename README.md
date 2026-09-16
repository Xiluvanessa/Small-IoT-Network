# Small-IoT-Network
This project focused on designing and simulating a secure Smart Greenhouse Monitoring System using Cisco Packet Tracer IoT devices. The assessment covered IoT sensor selection, communication methods, network design, MQTT-based device communication, automated actuators, IoT security measures, real-time monitoring, and risk assessment.
# Security Analysis of IoT Networks and Platforms – Smart Greenhouse Monitoring System

## Project Overview

This project was completed as part of the **ITSIA2-44: Security Analysis of IoT Networks and Platforms** module at Eduvos. The assessment focused on the design, simulation, security analysis, and risk assessment of an **IoT-based Smart Greenhouse Monitoring System** using Cisco Packet Tracer.

The purpose of the project was to demonstrate how Internet of Things (IoT) technologies can be used to monitor and automate environmental conditions within a greenhouse. The proposed system collects environmental information such as **temperature, humidity, soil moisture, and light intensity** using IoT sensors. The collected data is transmitted through a network to a central server or IoT controller, where it can be monitored and used to trigger automated actions.

## Project Objectives

The main objectives of the project were to:

* Identify appropriate IoT sensors for monitoring greenhouse conditions.
* Compare different IoT communication methods, including **Wi-Fi, Zigbee, and LoRaWAN**.
* Design a network architecture connecting sensors, actuators, controllers, servers, and network devices.
* Build and simulate the IoT environment using **Cisco Packet Tracer**.
* Configure communication between IoT devices and a central server.
* Demonstrate automation based on environmental thresholds.
* Identify security measures that can protect IoT devices and communications.
* Apply IoT security standards and best practices.
* Conduct a security risk assessment and propose mitigation strategies.

## Smart Greenhouse Design

The simulated greenhouse uses four primary environmental monitoring sensors:

* **Temperature Sensor** – monitors the greenhouse temperature and can be used to activate cooling equipment when temperatures become too high.
* **Humidity Sensor** – monitors the level of moisture in the air to help maintain suitable growing conditions.
* **Soil Moisture Sensor** – measures the moisture level in the soil and can be used to determine when irrigation is required.
* **Light Sensor** – measures light intensity and can support the control of shading or lighting systems.

The system also includes automated actuators such as a **cooling fan and irrigation pump**. These devices allow the greenhouse to respond automatically when environmental conditions reach predefined thresholds.

## Network and IoT Communication

The project examines different communication technologies that can be used to transfer sensor data within an IoT environment. **Wi-Fi, Zigbee, and LoRaWAN** were compared based on factors such as data rate, communication range, power consumption, reliability, and their suitability for greenhouse environments.

Within the simulated network, IoT devices communicate through an **IoT/Home Gateway**, which provides connectivity between the IoT devices and the central server. The design demonstrates how sensor data can be collected, transmitted, processed, and used to control connected devices.

## Cisco Packet Tracer Implementation

Cisco Packet Tracer was used to create and simulate the Smart Greenhouse environment. The topology includes IoT sensors, actuators, a gateway/controller, a server, and a monitoring device.

The simulation demonstrates the flow of information from environmental sensors to the central system. Automation scenarios are also included, such as:

**Soil moisture below a defined threshold → Irrigation pump activated**

and

**Temperature above a defined threshold → Cooling fan activated**

This demonstrates how IoT systems can use sensor data to make automated decisions without requiring constant manual intervention.

## IoT Security

Security was an important part of the project because IoT devices can introduce vulnerabilities into a network. The assessment considered security measures such as **device authentication, strong credentials, encrypted communication, network segmentation, firmware updates, and access controls**.

The project also examined IoT security standards and best practices, including **ETSI EN 303 645** and **ISO/IEC 27001**, to demonstrate how security requirements can be incorporated into an IoT implementation.

## Risk Assessment

A security risk assessment was conducted to identify potential threats and vulnerabilities affecting the greenhouse system. Risks considered included issues such as:

* Unauthorized access to IoT devices.
* Interception of sensor data.
* Sensor data spoofing or manipulation.
* Device malfunction or disruption.
* Denial-of-service attacks.
* Unauthorized access to the central server.

Each identified risk was considered in terms of its potential severity, and appropriate mitigation strategies were proposed to reduce the likelihood and impact of successful attacks.

## Skills Demonstrated

This project demonstrates practical knowledge and skills in:

* Internet of Things (IoT)
* Cisco Packet Tracer
* Network topology design
* IoT device configuration
* Wireless communication
* Sensor and actuator integration
* MQTT-based communication concepts
* Network and IoT security
* Security standards and best practices
* Risk assessment
* Threat and vulnerability identification
* Security mitigation strategies
* Automated IoT systems

## Project Outcome

The completed project demonstrates how an IoT-based greenhouse can combine **environmental monitoring, network communication, automation, and cybersecurity** into a single system. It provides a practical example of how sensor data can be collected and used to automatically control greenhouse equipment while considering the security risks associated with connected IoT devices.
