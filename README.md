# 🏎️ Bluetooth-Controlled Racing Car using Arduino

Final Examination Project for  
**CpE 417 – Microprocessors**  
2nd Semester A.Y. 2024–2025

---

## 📌 Project Overview

This project presents the design and implementation of a **Bluetooth-controlled racing car** using an **Arduino Uno**, **HC-05 Bluetooth module**, and a **motor speed booster** for enhanced performance. The robot is wirelessly controlled via a mobile application, allowing real-time directional movement such as forward, backward, left, and right.

The system demonstrates the integration of **wireless communication**, **motor control**, and **power management**—key concepts in microprocessor-based embedded systems.

---

## 🎯 Objectives

- Implement wireless control using Bluetooth (HC-05)
- Control DC motors using the L298N motor driver
- Enhance motor performance using an MT3608 DC-DC step-up converter
- Apply microprocessor concepts in a real-world robotic system

---

## 🧰 Components Used

- Arduino Uno  
- HC-05 Bluetooth Module  
- L298N Motor Driver  
- MT3608 DC-DC Step-Up Converter  
- DC Motors & Robot Car Chassis  
- Lithium Battery & Battery Holder  
- Jumper Wires  
- Mobile Bluetooth Controller Application
- Breadboard

---

## ⚙️ System Operation

1. The mobile application sends movement commands via Bluetooth  
2. The HC-05 module receives the data  
3. Arduino processes the received commands  
4. L298N motor driver controls motor speed and direction  
5. MT3608 boosts voltage to achieve higher speed and stability  

---

## 🔌 Circuit Diagram

📷 Circuit diagram: `docs/Circuit_Diagram.png`  
📷 Actual hardware setup available in the `images/` folder

---

## 💻 Source Code

The Arduino source code is located at src file.


<img width="492" height="345" alt="image" src="https://github.com/user-attachments/assets/9c553fee-2965-4644-a3fd-015c5c63ee65" />


