---
title: "NASA Student Launch: Avionics & Telemetry System"
excerpt: "Lead Electrical Engineer for high-altitude rocket payload integration and real-time data telemetry."
collection: portfolio
---

**Project Overview:**
As Lead Electrical Engineer for the Boomer Rocket Team (BRT), I designed the avionics architecture for our NASA Student Launch competition vehicle, ensuring robust data collection and recovery system actuation.

**Technical Specifications & Contributions:**
* **SBC Integration:** Configured a **Linux AML-S905X Single Board Computer** to handle high-level data processing and sensor management via GPIO.
* **Long-Range Telemetry:** Integrated **RYLR998 LoRa Transmitters** for 900MHz wireless data transmission of flight-critical telemetry.
* **Power Distribution:** Engineered a dual-rail power system using **4S Li-po batteries** and **DFR0379 Buck Converters** to provide stable 5V and 3.3V logic power.
* **Sensor Fusion:** Utilized I2C/UART protocols to interface **BNO085 IMUs** and **MPL3115A2 Altimeters** for real-time orientation and altitude tracking.
* **Actuation:** Managed recovery systems via **L298N Dual H-Bridges** and **Nema 17 stepper motors** for mechanical payload deployment.

![BRT Schematic](/images/brt-schematic.png)
