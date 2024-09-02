# Smart-Home-Garden

## Overview
This project involves the development of a smart home garden system that automates plant watering based on soil moisture levels and simulates fertilizer dispensing. The system uses an Arduino Uno microcontroller to monitor and control various sensors and actuators, ensuring optimal plant care with minimal human intervention.

## Features 

**1. Automated Plant Watering** 
The system continuously monitors soil moisture levels and automatically waters the plants when the soil is dry. The water pump is turned on when the soil moisture is low and off when it reaches a satisfactory level.
  
**2. Fertilizer Dispensing Simulation** 
A trimmer potentiometer is used to simulate fertilizer levels. When the simulated level above 400, an LED turns on to indicate that fertilizer would be dispensed.
 
**3. Environmental Monitoring** 
The system uses a DHT11 sensor to measure the temperature and humidity of the environment, providing useful data for optimizing plant growth. 
 
## Components Used  
 
- **Arduino Uno**: The main microcontroller that controls the system.
- **Soil Moisture Sensor**: Measures the moisture content in the soil.
- **DHT11 Sensor**: Monitors environmental temperature and humidity.
- **Trimmer Potentiometer**: Simulates the PH sensor.
- **3V DC Water Pump**: Waters the plants as needed.
- **5V Relay Module**: Controls the water pump.
- **LED**: Indicates the activation of the solenoid valve.

## Flow Chart
![alt text](https://github.com/Skiye34/Smart-Home-Garden/blob/main/FlowChart.JPG)

## Work Completed

### System Design and Planning 
- Finalized the system design, including component selection and circuit design. 
 
- Selected components: soil moisture sensor, DHT11 temperature and humidity sensor, trimmer potentiometer (simulating fertilizer sensor), relay, water pump, and LED. 
 
### Hardware Setup and Wiring 
- Successfully connected all sensors and actuators to the Arduino Uno. 
 
- Ensured stable power and accurate wiring connections. 
 
### Software Development and Testing

- Developed Arduino code to monitor sensor readings and control the water pump and LED. 
 
- Implemented logic for soil moisture thresholds
 
- - High: < 400
- - Mid: 400-600
- - Low: > 600

- Integrated the potentiometer as a simulated fertilizer sensor to trigger the LED. 
- Conducted initial and full system testing, confirming correct operation of all components. 
 
### System Calibration
- Calibrated the soil moisture sensor thresholds for accurate detection of moisture levels. 
-  Adjusted the potentiometer threshold to ensure reliable LED activation for fertilizer simulation. 
 
### System Demonstration

- Successfully demonstrated the system’s functionality, showcasing automated watering and simulated fertilizer dispensing. 
- Collected feedback and confirmed the system’s reliability.

## Current Status 
The system is fully operational, with all components working as intended. The Arduino code has been optimized for stability and performance, and the system successfully automates the watering process while simulating fertilizer dispensing. Environmental data (temperature and humidity) are also monitored in real-time.

## Challenges

**Sensor Accuracy** 
Initially faced issues with sensor accuracy, particularly with soil moisture readings fluctuating. - Resolved by recalibrating the sensor and refining the code to account for minor fluctuations. 

**Power Stability** 
 Ensured consistent power supply to all components, especially during pump operation, to avoid voltage drops affecting sensor readings.
