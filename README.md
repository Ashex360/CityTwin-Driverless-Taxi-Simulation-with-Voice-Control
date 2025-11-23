# 🚖 CityTwin: Driverless Taxi Simulation with Voice Control

*A Digital Twin–based Virtual Testing Environment for Autonomous Taxis*

---

## 🌆 Overview

**CityTwin** is a **Digital Twin–driven virtual city simulator** designed to **safely test autonomous (driverless) taxi systems** without risking real-world damage.
The simulator supports:

* **Autonomous taxi navigation** in a realistic virtual city
* **Voice commands** for manual high-level control (e.g., *left*, *right*, *stop*, *start*)
* **Dynamic traffic and pedestrian environments**
* **Accident and collision event visualization**
* **Customizable real-world conditions for training AI models**

This project acts as a **risk-free testbed** for researchers, developers, and learners working on **autonomous driving, AI safety, and intelligent transportation systems**.

---

## 🎯 Key Features

### 🧠 1. Autonomous Driving (AI Mode)

* The virtual taxi drives automatically using predefined or AI-generated routes
* Obstacle detection, path following, and event handling

### 🎤 2. Voice Control (Human Override Mode)

Control the taxi using natural speech commands:

* “Start”
* “Stop”
* “Turn left”
* “Turn right”
* “Slow down”
* “Speed up”

### 🌍 3. Realistic Digital Twin City

* Roads, intersections, traffic signals
* Buildings, lanes, signboards
* Spawn points for pedestrians and vehicles

### 🚦 4. Dynamic Traffic & Pedestrians

* Add/remove traffic
* Customize number and speed of vehicles
* Add pedestrian movement for realistic urban behavior

### 💥 5. Accident Visualization

* See how the taxi reacts to near-collision scenarios
* Stress-test AI navigation under bad conditions
* Record simulation logs for later analysis

---

## 🧪 Why CityTwin? (Problem Statement)

Testing autonomous taxis in real cities is **expensive, risky, and often unsafe**.
Real-world failures can cause:

* legal issues
* property damage
* injury risk
* model overfitting to limited conditions

**CityTwin solves this by providing a safe, low-cost, controlled virtual world** that represents a real environment using digital twin principles.

---

## 🧱 Architecture

```
+---------------------------+
|  Voice Command Module     |
| (Speech-to-Text + Intent) |
+-------------+-------------+
              |
              v
+---------------------------+
|  Control Manager          |
| (AI Mode + Voice Mode)    |
+-------------+-------------+
              |
              v
+---------------------------+
|  CityTwin Simulation Engine|
| (Environment + Physics)    |
+-------------+-------------+
              |
              v
+---------------------------+
|  Visualization Layer       |
| (Unity/Unreal UI)          |
+---------------------------+
```

---

## 🛠️ Tech Stack

* **Game Engine:** Unity / Unreal Engine (choose one)
* **AI Navigation:** Python / C# (NavMesh, custom logic)
* **Voice Recognition:**

  * Google Speech API / Vosk / Whisper ASR
* **Simulation:**

  * Unity Physics / Unreal Chaos Physics
* **Digital Twin Logic:**

  * Custom JSON-based city data
  * Dynamic event generators

---

## 🚀 Future Enhancements

* Real-time sensor simulation (LiDAR, camera, radar)
* Reinforcement Learning integration
* Multi-taxi coordination
* Real-world map import (OSM / GIS)
* Cloud-based simulation from browser

---

## 📸 Screenshots (Add Later)

> You can include images of your simulation
> `/assets/screenshot1.png`
> `/assets/screenshot2.png`

---

## 📂 Folder Structure

```
CityTwin/
 ├── Assets/
 ├── Scripts/
 ├── VoiceEngine/
 ├── Models/
 ├── Scenes/
 ├── Docs/
 └── README.md
```

---

## 🤝 Contributing

Pull requests are welcome!
If you want to contribute:

1. Fork the project
2. Create your feature branch
3. Commit your changes
4. Open a pull request

---

## 📜 License

MIT License
Feel free to use, modify, and experiment.

---

## 👨‍💻 Author

**Ashish (Ash)**
Driven by building impactful digital solutions for real-world problems.

