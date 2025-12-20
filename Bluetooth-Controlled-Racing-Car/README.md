# 🏎️ Bluetooth-Controlled Racing Car using Arduino

Final Examination Project for  
**CpE 417 – Microprocessors**  
2nd Semester A.Y. 2024–2025

---

## 📌 Project Overview

This project demonstrates the design and implementation of a **Bluetooth-controlled racing robot** using an **Arduino Uno**, **HC-05 Bluetooth module**, and a **motor booster** for enhanced speed. The robot is wirelessly controlled via a mobile application, allowing real-time directional movement such as forward, backward, left, and right.

The system highlights the integration of **wireless communication**, **motor control**, and **power management** in embedded systems.

---

## 🎯 Objectives

- Implement Bluetooth-based wireless control
- Control DC motors using L298N motor driver
- Enhance speed using MT3608 DC-DC step-up converter
- Apply microprocessor concepts in a real-world system

---

## 🧰 Components Used

- Arduino Uno
- HC-05 Bluetooth Module
- L298N Motor Driver
- MT3608 DC-DC Step-Up Converter
- DC Motors & Robot Car Chassis
- Lithium Battery & Battery Holder
- Jumper Wires
- Mobile Bluetooth Controller App

---

## ⚙️ System Operation

1. Mobile app sends directional commands via Bluetooth  
2. HC-05 receives data and forwards it to Arduino  
3. Arduino processes commands  
4. L298N controls motor speed and direction  
5. MT3608 boosts voltage for high-speed performance  

---

## 🔌 Circuit Diagram

📷 See `docs/Circuit_Diagram.png`  
📷 Actual circuit setup available in `images/`

---

## 💻 Source Code

The Arduino source code can be found here:

