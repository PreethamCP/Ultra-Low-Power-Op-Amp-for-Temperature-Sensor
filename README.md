# 🧊 Ultra-Low-Power Op-Amp for Temperature Sensor

Status: Under Active Development

This project aims to design and implement an **ultra low power operational amplifier (op-amp)** optimized for **temperature sensor applications**, where **minimum power consumption**, **precision**, and **stability across temperature** are critical.

---

## 📌 Project Overview

- **Application:** Interface and amplify signals from a temperature sensor
- **Goal:** Achieve **ultra-low power operation** while maintaining acceptable **gain**, **bandwidth**, and **accuracy**
- **Design Style:** Analog integrated circuit design (suitable for IoT / battery-powered sensor nodes)

---

## 🧱 Block-Level Architecture

> Overall architecture / schematic:

![alt text](<Screenshot (1243).png>)

Key blocks typically include:

- **Input stage:** High input impedance differential pair to sense small changes from the temperature sensor
- **Gain stage:** Provides required amplification with low quiescent current
- **Output stage:** Drives the load (ADC input or further analog chain) with minimal power

---

## 📊 Simulation Waveforms

![alt text](<Screenshot .png>)
