# 🚀 Smart Fleet Management System

An autonomous warehouse fleet orchestration simulation inspired by modern industrial robotics platforms.

This project simulates multi-robot coordination, path planning, mission allocation, and real-time state visualization using a C++ simulation core with a Python backend and web-based dashboard.

---

## 🧠 Project Overview

Smart Fleet Management System is a modular simulation framework designed to emulate real-world warehouse robot fleet orchestration systems.

The system includes:

- Multi-robot simulation
- Path planning engine
- Fleet manager
- Grid-based warehouse model
- Backend state server
- Web dashboard visualization

---

## 🏗 System Architecture

The system is divided into three main layers:

### 1️⃣ Simulation Core (C++)
- Robot logic
- Fleet manager
- Path planner
- Grid system

### 2️⃣ Backend Server (Python)
- Serves robot state
- Handles mission updates
- Communicates with frontend

### 3️⃣ Frontend Dashboard (HTML)
- Displays live robot state
- Visualizes missions
- Shows simulation status

## 📂 Project Structure
'''
Smart-Fleet-Management-System/
│
├── src/ # C++ Simulation Core
├── backend/ # Python Backend
├── frontend/ # Web Dashboard
├── data/ # Missions and state files
├── docs/ # Architecture documentation
├── assets/ # Screenshots and demo files
│
├── CMakeLists.txt
├── README.md
└── LICENSE
'''

## ⚙️ Technologies Used

- C++
- CMake
- Python
- HTML
- JSON
- Object-Oriented Design

---

## 🚀 How to Build

### Clone Repository

```bash
git clone https://github.com/hiArthansh/Smart-Fleet-Management-System.git
cd Smart-Fleet-Management-System

mkdir build
cd build
cmake ..
make
