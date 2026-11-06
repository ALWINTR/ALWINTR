# Alwin T R

**Embedded Systems & Robotics Engineer**  
Kochi, India • [Portfolio](https://alwintr.github.io) • [LinkedIn](https://linkedin.com/in/alwin-t-r-) • [GitHub](https://github.com/ALWINTR) • [Email](mailto:alwintr2003@gmail.com)

---

### Profile Overview

Embedded Systems and Robotics Engineer specializing in real-time firmware architecture (FreeRTOS / Bare-Metal C++), ROS 2 autonomous navigation, and industrial sensor systems. Proven track record across STM32 (ARM Cortex-M), ESP32 (Xtensa Dual-Core), and PIC microcontrollers, implementing multi-axis closed-form kinematics, 24GHz FMCW radar signal processing, and deterministic hardware communication protocols (CAN, UART, SPI, I2C).

---

### Core Competencies

* **Microcontrollers & Hardware Platforms**: STM32 (ARM Cortex-M), ESP32 Dual-Core, PIC16F877A, ATmega328P, Raspberry Pi 4, PCA9685 PWM drivers, L298N / A4988 motor drivers
* **Firmware & Real-Time OS**: FreeRTOS (Dual-Core Tasks, Queues, Semaphores, Mutexes), Bare-Metal C, Modern C++ (C++17), PIC Assembly / XC8, Python, Interrupt Service Routines (ISR), Hardware Timers, Watchdog Timers
* **Robotics, Kinematics & SLAM**: ROS 2 (Humble), Nav2, 2D SLAM (Cartographer / AMCL), Gazebo dynamic simulation, RViz2, 2D/3D Inverse Kinematics, quintic zero-jerk trajectory generation, LiDAR and wheel odometry sensor fusion
* **Industrial Protocols & Wireless**: CAN Bus, UART, I2C (Fast Mode 400kHz), SPI, ESP-NOW peer-to-peer (<10ms latency), MQTT, Wi-Fi 802.11, BLE
* **Tools & Toolchains**: STM32CubeIDE, ESP-IDF, PlatformIO, MPLAB X, Arduino IDE, Proteus, Git, GitHub CLI, Ubuntu Linux

---

### Featured Engineering Projects

#### 1. [ESP32 6-DOF Bipedal Walking Robot with FreeRTOS Kinematics](https://github.com/ALWINTR/ESP32-6-DOF-Bipedal-Walking-Robot-with-FreeRTOS-Kinematics)
* **Stack**: ESP32 Dual-Core • FreeRTOS • C++17 • PCA9685 • 400kHz I2C • AsyncWebServer
* **Engineering Highlights**:
  * Engineered a 6-DOF humanoid bipedal walking robot using dual-core ESP32 with strict FreeRTOS task isolation.
  * Implemented a dedicated 50Hz locomotion loop on Core 1 calculating closed-form 2D Inverse Kinematics and quintic polynomial zero-jerk swing trajectories for 6 high-torque metal-gear servos.
  * Offloaded real-time telemetry and wireless command handling to Core 0 via an asynchronous web server, eliminating servo jitter and timing contention.

#### 2. [24GHz mmWave Human Presence & Micro-Motion Radar Monitor](https://github.com/ALWINTR/24GHz-mmWave-Human-Presence-and-Micro-Motion-Radar-Monitor)
* **Stack**: ESP32 • HLK-LD2410C 24GHz FMCW Radar • UART • C++
* **Engineering Highlights**:
  * Designed a sub-millimeter presence, micro-motion, and respiration tracking monitor using 24GHz FMCW radar.
  * Developed a deterministic, non-blocking UART frame protocol parser (115200 baud) extracting motion energy states across 8 discrete spatial range gates up to 6 meters.
  * Achieved 99.2% detection reliability under varying environmental noise floor conditions.

#### 3. [Autonomous Reconnaissance Rover with Gas & Metal Detection](https://github.com/ALWINTR/Autonomous-Reconnaissance-Rover-with-Gas-and-Metal-Detection)
* **Stack**: ESP32-CAM • Arduino • MQ-2 Sensor • Inductive Metal Detector • 4WD Chassis
* **Engineering Highlights**:
  * Engineered an all-terrain tele-operated surveillance rover featuring low-latency wireless video transmission over local Wi-Fi UDP streams.
  * Integrated multi-sensor hazard detection fusing MQ-2 combustible gas monitoring with inductive metallic anomaly detection via edge-triggered alert interrupts.
  * Implemented fail-safe motor drive control across dual H-bridge drivers with automatic emergency braking on signal drop.

#### 4. [RFID Secure Access Control & Authentication System (PIC16F877A)](https://github.com/ALWINTR/RFID-Secure-Access-Control-and-Authentication-System-PIC16F877A)
* **Stack**: Microchip PIC16F877A • RC522 RFID • SPI Protocol • PIC Assembly / XC8 • 16x2 LCD
* **Engineering Highlights**:
  * Implemented bare-metal access control firmware interfacing a 13.56MHz MFRC522 RFID reader over SPI on a resource-constrained 8-bit PIC MCU.
  * Engineered interrupt-driven timing routines for authentication state machines and credential validation against internal EEPROM storage.

---

### Connect

* **Portfolio**: [alwintr.github.io](https://alwintr.github.io)
* **LinkedIn**: [linkedin.com/in/alwin-t-r-](https://linkedin.com/in/alwin-t-r-)
* **GitHub**: [github.com/ALWINTR](https://github.com/ALWINTR)
* **Email**: [alwintr2003@gmail.com](mailto:alwintr2003@gmail.com)
