# Drone-Based BTS Communication & Survivor Detection System

## 📌 Overview

In the wake of natural disasters such as floods, earthquakes, and cyclones, the immediate breakdown of communication infrastructure significantly hampers rescue operations and endangers lives. This project proposes an innovative drone-based system that utilizes aerial Base Transceiver Stations (BTS) integrated with advanced sensing and communication technologies to restore emergency connectivity, detect survivors, and assist in smart rescue coordination.

---

## 🎯 Key Features

### 📡 1. Aerial BTS (Base Transceiver Station)
Drones act as temporary mobile towers using **OpenBTS** or **srsRAN** with SDR modules to create a mobile network in disaster-hit areas. Nearby mobile phones connect automatically, enabling basic SMS communication and emergency calls — even without internet access.

### 📍 2. Survivor Detection System
The system passively detects survivors by analyzing:
- Signal strength (RSSI)
- Mobile device connection attempts (passive IMSI catching)
- GPS triangulation

Survivor locations are mapped in real time and displayed on a live rescue dashboard.

### 🔥 3. AI-Based Health Monitoring
Drones are outfitted with **thermal cameras**, **microphones**, and an **NVIDIA Jetson Nano** for onboard AI processing. The system identifies body heat, sound signals, and vital signs to assess survivor health conditions. Critical cases are automatically flagged and prioritized for rescue teams.

### 📦 4. Smart Supply Delivery
Drones carry modular payload systems for targeted supply drops, including:
- First aid kits
- Food supplies
- BLE beacon devices (to expand the communication mesh)

### 📶 5. Offline Communication Network
An offline mesh-based communication network built on **BLE Mesh** and **LoRa** supports the companion mobile app, **DisasterChat**, which enables peer-to-peer text messaging among survivors — no internet required.

### 🌐 6. Remote Monitoring & Control
Portable ground gateways relay drone data to remote command centers via **satellite uplinks**, eliminating dependency on existing infrastructure. Features include:
- Real-time 3D terrain mapping
- GPS tracking dashboard for rescue teams
- Live audio/video feeds
- Integration with government and NGO disaster response platforms

---

## 🛠️ Technology Stack

| Category | Technologies |
|---|---|
| **SDR Modules** | LimeSDR, USRP |
| **Embedded Platforms** | Raspberry Pi 4, NVIDIA Jetson Nano |
| **Sensors** | Thermal Camera, Microphone, GPS, BLE |
| **Communication** | OpenBTS, srsRAN, LoRa, BLE Mesh |
| **Software** | Flutter (mobile app), Node.js (dashboard), OpenAirInterface |

---

## 🚀 How It Works

1. Drones are deployed in disaster-affected zones
2. They establish a temporary mobile network (aerial BTS)
3. Survivors' devices automatically connect to the network
4. The system detects and maps survivor locations in real time
5. AI analyzes health conditions and flags critical cases
6. Rescue teams receive real-time updates via the dashboard
7. Drones perform targeted supply drops where needed

---

## 📊 Applications

- Disaster management and search & rescue operations
- Military emergency communication
- Remote medical missions
- Crowd management in high-density events
- Remote area connectivity

---
![Architecture Diagram](Architecture.png)
## 🔮 Future Improvements

- Autonomous drone swarm coordination
- Deeper integration with government disaster response systems
- Enhanced AI for medical diagnosis and triage
- Extended battery life and flight endurance

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repository, open issues, or submit pull requests to help improve the system.

---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 👨‍💻 Author

**Ragul Balaji**  
Electronics and Communication Engineering Student 
