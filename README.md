# 🕷️ Spider_Robot_001

> A bio-inspired spider robot designed for **surveillance in challenging environments**, integrating ultrasonic sensors and Bluetooth for real-time navigation and remote control.

## 📌 Overview

**Spider_Robot_001** is a modular, low-cost, and scalable surveillance robot engineered to assist in environments that are hazardous or difficult for humans to access. Inspired by spider locomotion, the robot uses multiple servo legs for maneuverability, and integrates obstacle detection using ultrasonic sensors.

- 🔍 **Project Duration:** Jan 2025 – May 2025  
- 🏛️ **Institution:** Chitkara University, Himachal Pradesh  
- 🧠 **Guided by:** Mr. Gaurav Mehta  
- 👥 **Team Members:**  
  - Eishan Nangia  
  - Gagan Verma  
  - Hemant Kumar  
  - Harman Singh

## 🎯 Objectives

- Design and develop a spider robot using Arduino Nano.
- Integrate ultrasonic sensors for obstacle avoidance.
- Enable Bluetooth-based remote control.
- Ensure modularity and cost-effectiveness for scalability.

## 🧰 Tech Stack

| Component        | Description                        |
|------------------|------------------------------------|
| Microcontroller  | Arduino Nano                 |
| Programming      | Embedded C / C++                   |
| Sensors          | Ultrasonic Sensors (HC-SR04)       |
| Actuators        | SG90 Servo Motors (12x)            |
| Communication    | Bluetooth Module (HC-05)           |
| Power            | 7.4V Li-ion Rechargeable Battery   |

## 🧠 System Architecture

- Sensors detect obstacles in real time
- Arduino processes distance data and controls movement logic
- Bluetooth enables manual override and status reporting

## 📈 Performance Highlights

| Metric                   | Value              |
|--------------------------|--------------------|
| Obstacle Detection Range | Up to 200 cm       |
| Reaction Time            | ~150 ms            |
| Servo Precision          | ±5° per command    |
| Bluetooth Range          | ~10 meters         |

## 🌐 SDG Mapping

- **SDG 9:** Industry, Innovation, and Infrastructure  
- **SDG 13:** Climate Action (via disaster response and surveillance)

## 💡 Unique Features

- Modular mechanical design for easy upgrades
- Real-time Bluetooth control for remote use
- Lightweight chassis suitable for disaster zones
- Low-cost build for academic and field deployment

## 🧪 Testing & Validation

- ✅ Obstacle avoidance within 20 cm
- ✅ Bluetooth communication via mobile
- ✅ Servo motor control and calibration
- ✅ Field testing on flat indoor terrain

## ⚠️ Challenges & Limitations

- Servo jitter due to inconsistent PWM signals (mitigated via software tuning)
- Sensor calibration needed across environments
- Limited to flat surfaces; struggles on rough terrains
- No onboard AI or autonomous navigation (future scope)

## 🚀 Future Work

- Integrate AI/ML for smart navigation
- Add thermal or infrared vision for surveillance
- Develop a mobile app UI for control
- Expand to multi-robot (swarm) coordination

## 📸 Screenshots

### Spider Robot Prototype
![Spider Robot on Flat Surface](spider_robot1.heic)


## 📚 References

- [Arduino](https://store.arduino.cc/products/arduino-rev3)
- [HC-SR04 Datasheet](https://cdn.sparkfun.com/datasheets/Sensors/Proximity/HCSR04.pdf)
- [Bluetooth SIG Spec](https://www.bluetooth.com/specifications/bluetooth-core-specification/)
- United Nations – [Sustainable Development Goals](https://sdgs.un.org/goals)

---

> 🤖 _Developed with passion for robotics and real-world problem-solving._


