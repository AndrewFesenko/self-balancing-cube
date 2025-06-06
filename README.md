# Self-Balancing Cube (ESP32 Version with Custom PCB)

This is my personal version of a self-balancing cube, inspired by [remrc’s original project](https://github.com/remrc/Self-Balancing-Cube). While the control logic is similar, I designed my own PCB and made a few adjustments to the setup and code to match my parts.

> ⚠️ This repo is **not** a full build guide. If you want to follow a full step-by-step tutorial, check out [remrc’s GitHub project](https://github.com/remrc/Self-Balancing-Cube) and his video:
>
> 📺 https://youtu.be/ZU0oTBRDgOE

---

## 🔩 Hardware Components

- **ESP32 Dev Board**
- **MPU6050 IMU**
- **3× Nidec 24H Brushless Motors**
- **Custom-designed PCB (KiCad)**
- **3S LiPo Battery (11.1V)**
- **Voltage Regulator (e.g. 7805)**
- **3D-printed frame and mounts**

---

## ✨ Features

- Balances on multiple edges and vertices
- Real-time motor control using PID
- Bluetooth-based parameter tuning
- Compact layout using custom PCB
- Modular firmware structure in C++

---

## 🖼️ Photos

### 🧠 System Schematic
![mWyU0HM](https://github.com/user-attachments/assets/cc4e3e46-3443-488b-b648-f23d786e0000)

### 🔌 Stripboard Wiring
![image](https://github.com/user-attachments/assets/76b47fb1-1fd6-46ed-b147-ce12c260564d)

### 🛠️ Custom PCB  
![IMG_2582](https://github.com/user-attachments/assets/82261f8a-0f51-4e18-a804-9199f6640139)

### 🤖 Final Build

---

## 🔗 Credits

Big thanks to [remrc](https://github.com/remrc/Self-Balancing-Cube) for the original concept, inspiration, and firmware structure.

---

Built for fun and personal learning
