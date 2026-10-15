# Alwin T R

<div align="center">

<img src="banner.svg" alt="Alwin T R - Robotics and Embedded Systems Architect" width="100%">

<br>

[![Portfolio](https://img.shields.io/badge/Portfolio-alwintr.github.io-00f0ff?style=for-the-badge&logo=googlechrome&logoColor=black)](https://alwintr.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Alwin_T_R-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/alwintr)
[![GitHub](https://img.shields.io/badge/GitHub-ALWINTR-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ALWINTR)
[![Email](https://img.shields.io/badge/Email-alwintr2003%40gmail.com-ea4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:alwintr2003@gmail.com)
[![Status](https://img.shields.io/badge/Status-Available_for_Engineering_Roles-10b981?style=for-the-badge)](https://alwintr.github.io#contact)

</div>

---

## 👨‍💻 Executive Summary

Robotics & Automation Engineer specialized in architecting **intelligent autonomous mobile robots (AMR)**, **real-time embedded firmware (FreeRTOS / Bare-Metal C++)**, **industrial sensor fusion automation**, and **distributed wireless IoT telemetry systems**. 

Experienced across the full hardware-software engineering lifecycle—from circuit schematic validation (Proteus VSM) and low-level peripheral drivers (UART, SPI, I2C, CAN Bus, 16-bit PWM) to multi-joint kinematic trajectory generation, state-machine scheduling, and ROS2 Gazebo dynamic modeling.

- 🌐 **Interactive Portfolio**: [alwintr.github.io](https://alwintr.github.io) *(Features in-page ASCII architecture specs, Hardware BOM tables, and pinout interconnects)*
- 💼 **Primary Focus**: Autonomous Mobile Robots, Dual-Core FreeRTOS Microkernels, Industrial Machine Automation
- 🛠️ **Hardware Platforms**: ESP32 (Xtensa Dual-Core), STM32 (ARM Cortex-M), PIC16F877A, ATmega328P, Raspberry Pi 4

---

## 📐 End-to-End System Architecture

```
+---------------------------------------------------------------------------------------------------+
|                                  PHYSICAL SENSING & PERCEPTION                                    |
|   [24GHz mmWave Radar]   [MQ-2 Gas / Metal]   [MAX30102 PPG]   [ADXL335 IMU]   [Hall Flow Rate]   |
+-------------------------------------------------+-------------------------------------------------+
                                                  | Fast I2C / High-Speed UART / ADC ISRs
                                                  v
+---------------------------------------------------------------------------------------------------+
|                             REAL-TIME FIRMWARE & MICROKERNEL LAYER                                |
|   +------------------------------------+             +----------------------------------------+   |
|   |   ESP32 FreeRTOS Dual-Core Engine  | <=========> |   Microchip PIC16F877A / ATmega328P    |   |
|   |   Task Queues • Mutexes • Semaph   |             |   Hardware Timers • Pin-Change ISRs    |   |
|   +------------------------------------+             +----------------------------------------+   |
+-------------------------------------------------+-------------------------------------------------+
                                                  | 16-Bit Hardware PWM / Step Pulses / Direction
                                                  v
+---------------------------------------------------------------------------------------------------+
|                               ACTUATION & KINEMATICS CONTROL                                      |
|   [4-DOF Bipedal Gait (Inverse Kinematics)]   [NEMA 17 Stepper (A4988)]   [L298N 4WD Rover Drive]  |
+-------------------------------------------------+-------------------------------------------------+
                                                  | Wi-Fi 802.11 b/g/n / Blynk 2.0 / REST API
                                                  v
+---------------------------------------------------------------------------------------------------+
|                                TELEMETRY & CLOUD CONNECTIVITY                                     |
|   [Live Web HUD Slider]   [Blynk Virtual Pins]   [ROS2 Navigation2]   [Python Synchronization]    |
+---------------------------------------------------------------------------------------------------+
```

---

## 🛠️ Technical Competency Matrix

| Domain | Technologies, Microcontrollers & Protocols |
| :--- | :--- |
| **Microcontrollers & Processors** | **ESP32** (Xtensa Dual-Core 240MHz), **PIC16F877A** (Microchip), **STM32** (ARM Cortex-M), **Arduino Mega 2560**, **AVR ATmega328P**, **ESP8266**, **Raspberry Pi 4** (Linux SBC) |
| **Firmware & Languages** | **C** (C99, C11), **C++17** / Embedded C++, **FreeRTOS** Preemptive Kernel, **Bare-Metal C**, **PIC Assembly / XC8**, **Python 3.10+**, Shell / Bash Scripting |
| **Robotics & Kinematics** | **ROS2** (Humble), **Gazebo** Dynamic Physics Simulation, **Forward & Inverse Kinematics**, **Differential Drive Odometry**, **Bipedal Gait Coordination**, **OpenCV** |
| **Hardware Protocols & Busses** | **UART / USART Serial**, **SPI Bus** (High-Speed), **I2C Bus** (Fast-Mode), **CAN Bus**, **16-Bit Hardware PWM**, **ADC / DAC**, **Hardware Interrupts (ISR)** |
| **Wireless & Cloud IoT** | **Wi-Fi 802.11 b/g/n**, **Blynk 2.0 Cloud**, **ESPAsyncWebServer**, **ESP-NOW**, **HTTP REST APIs**, **MQTT Telemetry**, **BLE** |
| **EDA, Compilers & Toolchains** | **Proteus VSM Circuit Suite**, **PlatformIO**, **ESP-IDF Native**, **MPLAB X & XC8**, **VS Code**, **Git & GitHub CLI (`gh`)**, **Ubuntu 22.04 LTS** |

---

## 🏆 Featured Engineering Repositories

All 17 repositories are fully documented with circuit schematics, hardware Bill of Materials (BOM), and production-grade firmware source code.

### 🤖 1. Autonomous Robotics & Kinematics

| Project | Primary Stack | Key Highlights | Documentation |
| :--- | :--- | :--- | :--- |
| **[Autonomous Reconnaissance Rover with Gas and Metal Detection](https://github.com/ALWINTR/Autonomous-Reconnaissance-Rover-with-Gas-and-Metal-Detection)** | ESP32-CAM, Arduino Uno, Dual L298N, MQ-2 Gas, Inductive Metal Sensor | All-terrain surveillance rover with real-time Wi-Fi UDP video streaming, hazardous gas leak detection, and ferrous metal proximity sensing. | [Technical Guide](https://github.com/ALWINTR/Autonomous-Reconnaissance-Rover-with-Gas-and-Metal-Detection/blob/main/README.md) |
| **[ESP32 4-DOF Bipedal Walking Robot with FreeRTOS Kinematics](https://github.com/ALWINTR/ESP32-4-DOF-Bipedal-Walking-Robot-with-FreeRTOS-Kinematics)** | ESP32 Dual-Core, FreeRTOS Kernel, 4x MG996R Servos, 16-Bit Timers | Bipedal walking robot featuring synchronized hip-ankle inverse kinematics, dynamic center-of-mass balancing, and real-time serial telemetry. | [Technical Guide](https://github.com/ALWINTR/ESP32-4-DOF-Bipedal-Walking-Robot-with-FreeRTOS-Kinematics/blob/main/README.md) |
| **[Dynamic Angular Velocity Servo Controller with Smooth Easing](https://github.com/ALWINTR/Dynamic-Angular-Velocity-Servo-Controller-with-Smooth-Easing)** | Arduino Uno, ATmega328P, TowerPro SG90, Non-Blocking Timers | Cubic S-curve velocity interpolation preventing mechanical backlash, vibration, and current spikes in precision robotic joints. | [Technical Guide](https://github.com/ALWINTR/Dynamic-Angular-Velocity-Servo-Controller-with-Smooth-Easing/blob/main/README.md) |

### ⚙️ 2. Industrial Automation & Sorting Systems

| Project | Primary Stack | Key Highlights | Documentation |
| :--- | :--- | :--- | :--- |
| **[Automated Multi-Material Waste Classification System](https://github.com/ALWINTR/Automated-Multi-Material-Waste-Classification-System)** | Arduino Uno, NEMA 17 Stepper, A4988 Driver, Inductive Proximity | High-throughput classification carousel with precision angular indexing, inductive metal sensing, and high-speed servo diversion flaps. | [Technical Guide](https://github.com/ALWINTR/Automated-Multi-Material-Waste-Classification-System/blob/main/README.md) |
| **[Dual-Stream Automated Waste Segregation System](https://github.com/ALWINTR/Automated-Wet-and-Dry-Waste-Classification-System)** | Arduino Uno, Soil Moisture Probe, HC-SR04 Sonar, SG90 Servos | Automated municipal sorting station classifying wet organic and dry recyclable waste with acoustic bin volume telemetry. | [Technical Guide](https://github.com/ALWINTR/Automated-Wet-and-Dry-Waste-Classification-System/blob/main/README.md) |
| **[Automated Rain-Responsive Shutter and Protection Mechanism](https://github.com/ALWINTR/Automated-Rain-Responsive-Shutter-and-Protection-Mechanism)** | Arduino Uno, FC-37 Rain Plate, LM393 Comparator, TowerPro SG90 | Weather protection mechanism using software hysteresis debounce filters to eliminate false rain triggers and deploy protective barriers. | [Technical Guide](https://github.com/ALWINTR/Automated-Rain-Responsive-Shutter-and-Protection-Mechanism/blob/main/README.md) |

### ⚡ 3. Real-Time Embedded Firmware & Microcontrollers

| Project | Primary Stack | Key Highlights | Documentation |
| :--- | :--- | :--- | :--- |
| **[RFID Secure Access Control and Authentication System (PIC16F877A)](https://github.com/ALWINTR/RFID-Secure-Access-Control-and-Authentication-System-PIC16F877A)** | Microchip PIC16F877A, RC522 SPI RFID Reader, 16x2 LCD, Solenoid | Industrial access control firmware with hardware SPI card authentication, internal EEPROM credential validation, and Proteus VSM verification. | [Technical Guide](https://github.com/ALWINTR/RFID-Secure-Access-Control-and-Authentication-System-PIC16F877A/blob/main/README.md) |
| **[Precision Stepper Motor Angle Controller with Microstepping](https://github.com/ALWINTR/Precision-Stepper-Motor-Angle-Controller-with-Microstepping)** | Arduino Uno, NEMA 17 Stepper, A4988 1/16 Microstepping, Serial CLI | Motion control firmware executing trapezoidal acceleration ramps, 1/16 microstepping, and sub-degree (0.1125°) angular positioning. | [Technical Guide](https://github.com/ALWINTR/Precision-Stepper-Motor-Angle-Controller-with-Microstepping/blob/main/README.md) |
| **[ESP32 Embedded Systems and Firmware Architecture Laboratory](https://github.com/ALWINTR/ESP32-Embedded-Systems-and-Firmware-Architecture-Laboratory)** | ESP32, ESP-IDF Native C, FreeRTOS Queues, SPI/I2C/UART Drivers | Production-ready embedded laboratory containing reusable peripheral drivers, task pinning, ring buffers, and Non-Volatile Storage (NVS). | [Technical Guide](https://github.com/ALWINTR/ESP32-Embedded-Systems-and-Firmware-Architecture-Laboratory/blob/main/README.md) |

### 📡 4. Advanced Radar, Biometrics & Sensor Telemetry

| Project | Primary Stack | Key Highlights | Documentation |
| :--- | :--- | :--- | :--- |
| **[24GHz mmWave Human Presence and Micro-Motion Radar Monitor](https://github.com/ALWINTR/24GHz-mmWave-Human-Presence-and-Micro-Motion-Radar-Monitor)** | ESP32, Hi-Link HLK-LD2410C 24GHz FMCW Radar, UART Bus | High-precision spatial presence radar tracking micro-motions (respiration, subtle tremors) across 8 range gates up to 6 meters. | [Technical Guide](https://github.com/ALWINTR/24GHz-mmWave-Human-Presence-and-Micro-Motion-Radar-Monitor/blob/main/README.md) |
| **[Real-Time Seismic Vibration and Earthquake Early Warning System](https://github.com/ALWINTR/Real-Time-Seismic-Vibration-and-Earthquake-Early-Warning-System)** | Arduino Nano, ADXL335 3-Axis Accelerometer, I2C OLED, Siren | Tri-axial seismic vibration detection computing dynamic Euclidean acceleration deltas with analog low-pass filtering. | [Technical Guide](https://github.com/ALWINTR/Real-Time-Seismic-Vibration-and-Earthquake-Early-Warning-System/blob/main/README.md) |
| **[Smart Bidirectional People Counter and Room Occupancy Monitor](https://github.com/ALWINTR/Smart-Bidirectional-People-Counter-and-Room-Occupancy-Monitor)** | ESP32, Dual Infrared Beam Sensors, SSD1306 OLED Display | Directional entry/exit beam interruption counter tracking real-time room occupancy with overflow safety alarm thresholds. | [Technical Guide](https://github.com/ALWINTR/Smart-Bidirectional-People-Counter-and-Room-Occupancy-Monitor/blob/main/README.md) |
| **[Pipeline Water Flow Rate and Structural Tilt Monitor](https://github.com/ALWINTR/Pipeline-Water-Flow-Rate-and-Structural-Tilt-Monitor)** | ESP32, YF-S201 Hall Turbine, SW-520D Ball Tilt, Hardware ISR | Industrial telemetry station integrating interrupt pulse accumulation for volumetric flow calculation and angular tilt deviation detection. | [Technical Guide](https://github.com/ALWINTR/Pipeline-Water-Flow-Rate-and-Structural-Tilt-Monitor/blob/main/README.md) |
| **[Biometric Pulse Oximeter and Heart Rate Telemetry System](https://github.com/ALWINTR/Biometric-Pulse-Oximeter-and-Heart-Rate-Telemetry-System)** | ESP32, Maxim MAX30102 PPG Biosensor, I2C Fast-Mode, OLED | Optical photoplethysmography (PPG) system calculating Heart Rate (BPM) and blood oxygen saturation (SpO2) with live waveform rendering. | [Technical Guide](https://github.com/ALWINTR/Biometric-Pulse-Oximeter-and-Heart-Rate-Telemetry-System/blob/main/README.md) |

### 🌐 5. IoT & Cloud Actuation Frameworks

| Project | Primary Stack | Key Highlights | Documentation |
| :--- | :--- | :--- | :--- |
| **[ESP Asynchronous Web Server Real-Time Servo Controller](https://github.com/ALWINTR/ESP-Asynchronous-Web-Server-Real-Time-Servo-Controller)** | ESP32 / ESP8266, ESPAsyncWebServer, REST Endpoints, PWM Timers | Embedded asynchronous HTTP web server with responsive in-browser angle sliders and RESTful API for wireless actuation. | [Technical Guide](https://github.com/ALWINTR/ESP-Asynchronous-Web-Server-Real-Time-Servo-Controller/blob/main/README.md) |
| **[Blynk Cloud Connected Real-Time Servo Actuation Framework](https://github.com/ALWINTR/Blynk-Cloud-Connected-Real-Time-Servo-Actuation-Framework)** | ESP32, Blynk 2.0 Cloud Platform, Virtual Pin V0, Auto-Reconnect | Resilient cloud-connected actuator engine with bidirectional Virtual Pin sync and non-blocking Wi-Fi auto-reconnection. | [Technical Guide](https://github.com/ALWINTR/Blynk-Cloud-Connected-Real-Time-Servo-Actuation-Framework/blob/main/README.md) |
| **[Developer Repository and Conversation Synchronization Suite](https://github.com/ALWINTR/Developer-Repository-and-Conversation-Synchronization-Suite)** | Python 3.10+, GitHub CLI (`gh`), MinGit, Scheduled Automation | Automated synchronization engine preserving developer engineering session transcripts, scrubbed logs, and repository updates. | [Technical Guide](https://github.com/ALWINTR/Developer-Repository-and-Conversation-Synchronization-Suite/blob/main/README.md) |

---

## 📬 Direct Contact & Collaboration

Looking for full-time engineering roles in **Robotics Engineering**, **Embedded Firmware Development**, and **Autonomous Systems Architecture**.

- 💼 **LinkedIn**: [linkedin.com/in/alwintr](https://www.linkedin.com/in/alwintr)
- 🌐 **Interactive Portfolio**: [alwintr.github.io](https://alwintr.github.io)
- 🐙 **GitHub Repositories**: [github.com/ALWINTR](https://github.com/ALWINTR)
- ✉️ **Direct Email**: [alwintr2003@gmail.com](mailto:alwintr2003@gmail.com)

---

<div align="center">
  <sub>Copyright &copy; 2026 Alwin T R. Engineered with precision for robotics and embedded systems.</sub>
</div>
