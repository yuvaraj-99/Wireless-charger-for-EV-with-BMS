# ⚡ Wireless Charging for Electric Vehicles (EVs) with Battery Management System (BMS)

This project demonstrates a wireless charging system for Electric Vehicles (EVs), integrated with a Battery Management System (BMS) to ensure safe, efficient, and smart charging. The system enables contactless power transfer, real-time monitoring of battery parameters, and automatic control of charging cycles.

---

## 🚀 Overview

- **Wireless Power Transfer (WPT):** Uses inductive coupling to transmit power from the charger to the EV without physical connectors.
- **Battery Management System (BMS):** Monitors and controls charging, preventing overcharging, overheating, and voltage imbalance.
- **Smart Control:** Optional integration with IoT for real-time data visualization and safety alerts.

---

## 🧩 Key Features

- ⚡ Contactless EV charging via inductive coils
- 🔋 Real-time battery monitoring (voltage, current, temperature)
- 🛑 Auto cut-off on overvoltage, undervoltage, or overheating
- 📡 Optional wireless data transmission to dashboard/mobile app
- 🔌 Modular design, scalable for different EV capacities

---

## ⚙️ Hardware Components

- Transmitting Coil (TX) and Receiving Coil (RX)
- High-Frequency Inverter Circuit
- Rectifier + Voltage Regulator (on RX side)
- Li-ion Battery Pack (or simulated cell)
- Battery Management System Module (BMS, e.g., 3S/4S BMS)
- Microcontroller (Arduino / NodeMCU / STM32)
- Sensors: Voltage, Current (INA219 / ACS712), Temperature (LM35 / DHT11)
- OLED / LCD Display (for local monitoring)
- Optional: ESP8266/ESP32 for IoT dashboard

---

## 🧠 Software & Libraries

- Arduino IDE
---

## 🛠️ How It Works

1. **Wireless Charging:**
   - Power is transmitted from the TX coil to the RX coil using inductive resonance.
   - On the receiver side, AC is converted to DC to charge the battery.

2. **Battery Management:**
   - BMS constantly monitors battery health.
   - Microcontroller reads sensor data and decides whether to continue or cut off charging.

3. **Smart Features:**
   - Data like battery percentage, charging current, temperature, and fault status can be displayed or sent to a web/mobile app.

---

