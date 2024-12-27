# Solenoid Door Lock System
<P align="center">
   <img width="640" alt="Screenshot 2024-12-27 at 8 55 59 PM" src="https://github.com/user-attachments/assets/d1428d21-b1f7-40f3-b4af-10bfde93230d" />
</P>

## Table of Contents
1. [Introduction](#introduction)
2. [Components Required](#components-required)
3. [Components Overview](#components-overview)
   - [16x2 LCD Display](#16x2-lcd-display)
   - [LCD Display Module](#lcd-display-module)
   - [EM-18 RFID Reader Module](#em-18-rfid-reader-module)
   - [Solenoid Door Lock](#solenoid-door-lock)
4. [Setup and Usage](#setup-and-usage)
   - [Hardware Connections](#hardware-connections)
   - [Software Implementation](#software-implementation)
   - [Testing and Deployment](#testing-and-deployment)
5. [License](#License)
6. [Conclusion](#conclusion)

## Introduction
This project involves creating a solenoid door lock system using an EM-18 RFID reader and a keypad. The system provides enhanced security and controlled access using RFID cards and a keypad.

## Components Required
1. **16x2 LCD Display**
2. **LCD Display Module**
3. **EM-18 RFID Reader Module**
4. **Solenoid Door Lock**
5. **Relay Module**
6. **Arduino Board**
7. **3x3 Keypad**

## Components Overview

### 16x2 LCD Display
<p align = "center">
<img width="640" src="https://github.com/user-attachments/assets/936b2ad0-e99e-46e1-89de-cc10ff3d7c10"/>
</p>

- **Description:** Displays up to 32 characters on two lines.
- **Operating Voltage:** 4.7V to 5.3V.
- **Pixel Resolution:** 5x8 per character.

### LCD Display Module

- **Description:** Detachable module for easy replacement.
- **Features:** Includes potentiometer for brightness control.

### EM-18 RFID Reader Module
<p align = "center">
<img width="340" src="https://github.com/user-attachments/assets/a7bbc91b-69bb-43b6-88b9-63c18c14d7e1">
</p>

- **Operating Frequency:** 125 KHz.
- **Interface:** UART communication with microcontrollers.

### Solenoid Door Lock
<p align = "center">
<img width="340" src="https://github.com/user-attachments/assets/422c5991-b073-458f-b5d1-de40e255687e">
</p>

- **Description:** Electromechanical device controlling access through electromagnetism.

## Setup and Usage

### Hardware Connections
1. **LCD Display:** Connect the 16x2 LCD display to the Arduino, ensuring correct pin alignment.
2. **RFID Reader:** Interface the EM-18 RFID reader with the Arduino using UART pins.
3. **Solenoid Lock:** Connect the solenoid lock to a relay module which is controlled by the Arduino.
4. **Keypad:** Attach the 3x3 keypad to the Arduino for input.

### Software Implementation
1. **Arduino Code:** Write the code to manage RFID reading and keypad input.
2. **Control Logic:** Program the Arduino to control the solenoid lock based on authorized RFID tags and keypad codes.

### Testing and Deployment
1. **System Testing:** Test the system by scanning RFID tags and entering keypad codes.
2. **Deployment:** Deploy the system for controlled access to secure areas.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Conclusion
This project provides a secure and efficient way to control access using a combination of RFID and keypad authentication.

---

For detailed code and schematic diagrams, please refer to the repository files.
