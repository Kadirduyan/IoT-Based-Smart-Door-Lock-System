# IoT Based Smart Door Lock System 🔐

## 📌 Project Overview

This project is an IoT-based Smart Door Lock System designed to eliminate the need for physical keys and provide secure, remote access control via a mobile device.

The system allows users to unlock and lock a door remotely through Wi-Fi communication using a NodeMCU (ESP8266) microcontroller. The project integrates embedded systems, power electronics, and IoT communication technologies into a fully functional prototype.

🎥 **Project Demo Video:**  
https://youtu.be/eWPyiDIZVXw?si=0YcrkwzMBleNU2ty

---

## 🎯 Project Objectives

- Enable remote door control via smartphone
- Provide secure and reliable wireless communication
- Integrate low-voltage control with high-current locking mechanism
- Ensure stable power management for both microcontroller and actuator
- Develop a scalable IoT-based access control prototype

---

## ⚙️ Technologies Used

- NodeMCU (ESP8266)
- Wi-Fi Communication
- 12V Magnetic Solenoid Lock
- 5V Relay Module
- LM2596 Voltage Regulator
- 12V 2A Power Supply
- Embedded C / Arduino IDE

---

## 🧠 System Architecture

Mobile Device  
⬇  
Wi-Fi Network  
⬇  
NodeMCU (ESP8266)  
⬇  
Relay Module  
⬇  
12V Solenoid Lock  

The NodeMCU connects to a Wi-Fi network and waits for commands.  
When the user presses the "Unlock" button from the mobile interface:

1. A signal is sent over Wi-Fi.
2. NodeMCU processes the command.
3. Digital output (D1) triggers the relay.
4. Relay completes the 12V circuit.
5. Solenoid retracts the locking mechanism.
6. The door unlocks.

---

## 🔌 Power Management Design

The system operates using a single 12V 2A adapter.

- 12V directly powers the solenoid lock.
- LM2596 step-down converter reduces 12V to regulated 5V.
- 5V powers NodeMCU and relay module.

This design ensures:
- Voltage stability
- Protection against fluctuations
- Efficient energy distribution

---

## 🔐 Key Features

- Remote door lock/unlock functionality
- Real-time wireless control
- Integrated power management
- Electromechanical locking system
- IoT-based architecture
- Expandable for cloud integration

---

## 📊 Technical Analysis

During testing:

- Relay module successfully handled high-current switching.
- Solenoid consumed approximately 1A–1.5A peak current.
- 12V 2A adapter provided stable operation.
- Voltage regulation protected the microcontroller from electrical noise.

---

## 💰 Estimated Cost

| Component | Cost (Approx.) |
|-----------|---------------|
| NodeMCU ESP8266 | 180 TL |
| 12V Solenoid Lock | 250 TL |
| 5V Relay Module | 60 TL |
| LM2596 Regulator | 50 TL |
| 12V 2A Adapter | 150 TL |
| Cables & Materials | 100 TL |
| **Total** | **~790 TL** |

---

## 🚀 Future Improvements

- Mobile application with authentication
- Cloud-based logging system
- Access history tracking
- Biometric integration
- Encryption for secure communication
- Battery backup system

---

## 👨‍💻 Team Members

- Kadir Duyan
- Ömer Yazıcıgil
- Eyüp Erol

---

## 🏷️ Keywords

IoT, Smart Lock, ESP8266, NodeMCU, Embedded Systems, Relay Control, Solenoid Lock, Wireless Access Control
