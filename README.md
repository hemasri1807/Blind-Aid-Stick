# 🦯 Blind Aid Stick

A smart walking stick designed to assist visually impaired individuals in detecting obstacles using ultrasonic sensors and providing real-time feedback through a buzzer or vibration motor. This project leverages basic embedded systems and Arduino to build a cost-effective mobility aid.

---

## 🚀 Overview

Navigating unfamiliar environments is one of the biggest challenges for people with visual impairments. This project aims to enhance their safety and independence by building a simple, low-cost device that alerts them of nearby obstacles using distance sensors and audio/haptic signals.

---

## 🛠️ Features

- **Ultrasonic Obstacle Detection:** Senses objects within a predefined distance range (e.g., 2 meters).
- **Buzzer or Vibration Alerts:** Triggers an alert if an object is detected within the range.
- **Portable and Rechargeable:** Runs on a small battery pack; can be attached to any walking stick.
- **Customizable Range:** Easily adjustable threshold via code.

---

## 🧰 Technologies Used

- **Hardware:**
  - Arduino Uno
  - Ultrasonic Sensor (HC-SR04)
  - Buzzer or Vibration Motor
  - Battery Pack
  - Jumper Wires
  - Breadboard or PCB

- **Software:**
  - Arduino IDE
  - Embedded C

---

## 🔌 Circuit Diagram

![Blind Aid Stick Schematic](Images/demo_image.jpg)  
*Add an actual image or diagram of your setup here*

---

## 💻 How It Works

1. The ultrasonic sensor continuously measures distance to the nearest object.
2. If the distance falls below a set threshold (e.g., 100 cm), the Arduino triggers a buzzer or vibration motor.
3. The user is alerted in real-time about obstacles ahead.

---

## 📂 File Structure

```bash
blind-aid-stick/
├── Code/
│   └── blind_aid_stick.ino        # Arduino source code
├── Images/
│   └── demo_image.jpg             # Circuit diagram or real device photo
├── Components.txt                 # Bill of materials
├── README.md
