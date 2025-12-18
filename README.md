Room Temperature Monitoring System using Modbus TCP, MQTT and OpenSCADA
 Overview :
This project implements an embedded room temperature monitoring and control system using a BeagleBone Black and DHT11 temperature sensor.
The system integrates Modbus TCP and MQTT protocols for industrial communication and uses OpenSCADA as the Human-Machine Interface (HMI) for real-time monitoring and visualization.

System Architecture :

Sensor Layer:

DHT11 temperature sensor connected to BeagleBone Black

Custom Linux kernel module for sensor interfacing

Communication Layer:

Modbus TCP server for industrial data access

MQTT for lightweight data publishing and messaging

Protocol bridging between Modbus TCP and MQTT

SCADA Layer:

OpenSCADA for real-time data visualization

HMI configuration for remote monitoring and control

Hardware: BeagleBone Black, DHT11

Protocols: Modbus TCP, MQTT

Software & Tools:

Embedded Linux

C (Linux kernel module development)

Python (MQTT client/server)

OpenSCADA

📂 Project Structure
Openscada_project/
│
├── MQTT_TCP/        # MQTT client/server and Modbus TCP integration
├── RTU_Mobus/       # Modbus RTU / TCP implementation
├── README.md        # Project documentation


Features :

Real-time temperature acquisition from DHT11 sensor

Modbus TCP server implementation for industrial communication

MQTT-based data publishing for scalable monitoring

OpenSCADA HMI for live visualization and user interaction

Linux kernel module for low-level sensor access
