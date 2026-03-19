# 🔥 IoT-Based Fire Detection & Alerting System

## 📌 Overview

This project is an IoT-based fire detection system designed to provide real-time hazard monitoring and alerting. It integrates flame and gas sensors with an Arduino microcontroller to detect fire or smoke conditions and trigger immediate alerts.

## ⚙️ Features

* Real-time fire and smoke detection using **flame sensor** and **MQ-2 gas sensor**
* Threshold-based detection logic implemented on **Arduino**
* Local alert system using **buzzer and LED indicators**
* Remote alerting via **SMTP-based email notifications**
* Serial communication between Arduino and Python for data transmission

## 🛠️ Tech Stack

* **Hardware:** Arduino UNO, MQ-2 Gas Sensor, Flame Sensor, Buzzer, LEDs
* **Software:** Arduino C/C++, Python
* **Protocols:** Serial Communication (9600 baud), SMTP

## 🔄 System Workflow

1. Sensors continuously monitor environmental conditions
2. Arduino processes analog inputs using threshold logic
3. On detection:

   * Activates buzzer and LED (local alert)
   * Sends signal via serial communication
4. Python script listens to serial input and triggers email alerts via SMTP

## 📊 Key Highlights

* Dual-layer alert system (local + remote)
* Real-time processing without cloud dependency
* Low-cost and easily deployable solution

## ⚠️ Note

Sensitive credentials (email/password) are not included in this repository for security reasons. Environment variables should be used for configuration.

## 📎 Future Improvements

* Integration with cloud platforms for remote monitoring
* Mobile app notifications
* Machine learning-based false alarm reduction

---
