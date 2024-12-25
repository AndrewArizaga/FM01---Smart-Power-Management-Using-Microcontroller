# FM01: Smart Power Management Using Microcontroller

## Overview
The **Smart Power Management Using Microcontroller** project is a practical solution designed to automate the switching of lights and appliances based on room occupancy and individual iris recognition. Leveraging the ESP32 microcontroller, this project aims to provide energy efficiency, ease of use, and enhanced security.

---

## Key Objectives
- **Energy Efficiency:** Automatically turn off unused appliances and lights to conserve energy.
- **Convenience:** Enable seamless automation for modern smart homes.
- **Enhanced Security:** Incorporate iris recognition for selective activation.

---

## Hardware Components
- **ESP32-WROOM-32D:** Core microcontroller for processing and control.
- **IR Sensors:** Detect room occupancy.
- **Relay Modules:** Control high-power devices such as lights and appliances.
- **Iris Recognition Module:** Authenticate user identity.
- **Power Supply:** Provides power for the microcontroller and connected peripherals.
- **Push Buttons:** For manual override and system programming.

---

## System Workflow
1. **Occupancy Detection:**
   - IR sensors detect room occupancy and send signals to the ESP32.
2. **Iris Recognition:**
   - The iris recognition module authenticates the user.
3. **Appliance Control:**
   - Upon successful detection and authentication, the ESP32 activates relays to power appliances and lights.
4. **Energy Optimization:**
   - When the room is unoccupied, the system automatically turns off the connected devices.

---

## Project Focus
This project emphasizes:
- **Practical Implementation:** Integrating automation with embedded systems for smart homes.
- **Energy Conservation:** Reducing energy waste through smart automation.
- **User Security:** Ensuring only authorized users can access specific features.

---

## Future Applications
- **Smart Homes:** Enhance home automation with personalized settings and energy tracking.
- **Industrial Automation:** Implement efficient power management systems in factories and offices.
- **IoT Ecosystems:** Integrate with IoT platforms for real-time monitoring and control.

---

## How to Use
1. Power the system using a suitable power supply.
2. Approach the room to trigger the **occupancy detection** system.
3. Authenticate your identity using the **iris recognition module**.
4. The system will automatically switch on the connected appliances.
5. When leaving the room, ensure no occupancy to enable the **auto-off** feature.

---

Feel free to suggest further improvements or request additional functionality!
