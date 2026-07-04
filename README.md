
# Defect Detection in Residential Photovoltaic Systems Using STM32

## Overview

This project presents an intelligent monitoring system for residential photovoltaic (PV) installations using an STM32 microcontroller. The system continuously measures electrical parameters, stores sensor data, and enables machine learning-based defect detection to identify faults affecting solar panel performance.

The project was developed as part of the Sustainable Development Goal 7 (Affordable and Clean Energy) initiative at RV College of Engineering.

---

## Features

- Real-time voltage monitoring
- Current measurement
- STM32-based embedded system
- Sensor data acquisition
- SD card data logging
- Machine learning-based defect detection
- Early fault identification
- Cost-effective PV monitoring solution

---

## System Architecture

```
Solar Panel
      │
      ▼
Voltage & Current Sensors
      │
      ▼
STM32 Microcontroller
      │
      ├────────► SD Card Data Logging
      │
      ▼
Collected Dataset
      │
      ▼
Machine Learning Model
      │
      ▼
Defect Detection & Analysis
```

---

## Hardware Used

- STM32 Microcontroller
- Voltage Sensor
- Current Sensor
- SD Card Module
- Residential Photovoltaic Panel
- Power Supply

---

## Software & Tools

- STM32CubeIDE
- Embedded C
- Machine Learning
- Data Logging
- Microsoft Excel (Dataset Analysis)

---

## Working Principle

1. The STM32 continuously acquires voltage and current readings from the PV system.
2. Sensor data is stored on an SD card.
3. The collected dataset is analyzed using machine learning techniques.
4. The trained model identifies abnormal operating conditions.
5. Faults such as voltage drops, current irregularities, and degraded panel performance are detected.

---

## Objectives

- Monitor photovoltaic system health
- Detect faults at an early stage
- Improve energy efficiency
- Reduce maintenance costs
- Support sustainable renewable energy systems

---

## Project Outcomes

- Successful acquisition of real-time PV data
- Reliable embedded monitoring using STM32
- Data logging for offline analysis
- Accurate identification of PV defects using machine learning
- Low-cost monitoring solution for residential solar installations

---

## Applications

- Residential solar plants
- Rooftop photovoltaic systems
- Renewable energy monitoring
- Smart energy management
- Predictive maintenance

---

## Future Improvements

- IoT-based cloud monitoring
- Mobile application integration
- Real-time alerts
- Wireless communication (Wi-Fi/LoRa)
- Advanced deep learning models
- Dashboard visualization

---



---



## License

This repository is intended for academic and educational purposes.
