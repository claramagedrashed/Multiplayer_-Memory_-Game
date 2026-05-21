# 🎮 Multiplayer Memory Game

A microcontroller-based multiplayer gaming console developed using the Arduino Uno (ATmega328P) as part of the Programming Module (4FTC2168) at the University of Hertfordshire.

This project combines embedded systems programming, hardware interfacing, finite state machine (FSM) architecture, and real-time gameplay mechanics into a fully interactive multiplayer memory game platform.

---

# 📌 Project Overview

The system is designed as a multiplayer memory and reaction game console supporting multiple gameplay modes for one or two players.

The project integrates:
- LEDs
- Push Buttons
- LCD Display
- Passive Buzzer
- EEPROM Storage
- Non-Blocking Embedded Software

The main objective was to apply embedded systems concepts in a practical and interactive real-time application.

---

# 🚀 Features

- 🎮 4 Different Gameplay Modes
- ⚡ Real-Time Responsive Controls
- 🧠 Memory & Reaction Challenges
- 🔊 Audio Feedback using Passive Buzzer
- 💾 EEPROM High Score Saving
- 🌙 Automatic Sleep Mode
- 📟 LCD Menu Interface
- 🔁 Finite State Machine (FSM)
- ⏱ Non-Blocking Timing System
- 🔘 Software Button Debouncing
- 📈 Dynamic Difficulty Scaling

---

# 🕹 Gameplay Modes

## 1️⃣ Solo Sprint
A single-player memory challenge where the player repeats an increasingly difficult LED sequence.

## 2️⃣ Duo Mode
Two players compete simultaneously to reproduce the same LED sequence faster and more accurately.

## 3️⃣ Reaction Mode
Players race to press the correct button immediately after a random LED appears.

## 4️⃣ The Challenger
One player creates a hidden sequence while the other attempts to memorize and reproduce it.

---

# 🛠 Hardware Components

| Component | Quantity |
|---|---|
| Arduino Uno (ATmega328P) | 1 |
| Push Buttons | 8 |
| LEDs | 4 |
| 16x2 I2C LCD | 1 |
| Passive Buzzer | 1 |
| Breadboard & Jumper Wires | Multiple |

---

# ⚙️ Software Architecture

The software was developed using:
- Arduino C/C++
- Finite State Machine (FSM)
- Modular `.cpp` and `.h` files
- Non-Blocking Event Loop
- EEPROM Persistent Storage
- AVR Register Manipulation

### Main Software Modules
- `display.cpp`
- `gpio.cpp`
- `audio.cpp`
- `timer.cpp`
- `solo_mode.cpp`
- `duo_mode.cpp`
- `reaction_mode.cpp`
- `challenger_mode.cpp`

---

# 🔌 System Wiring

The project includes:
- 4 LEDs connected to digital pins
- 8 push buttons for player inputs
- I2C LCD connected using SDA/SCL
- Passive buzzer for sound effects

---

# 🧠 Embedded Systems Concepts Used

- AVR GPIO Register Manipulation
- Non-Blocking Timing using `millis()`
- Finite State Machine Design
- Software Debouncing
- EEPROM Memory Management
- Timer-Based Scheduling
- Sleep Mode Power Optimization
- Real-Time Event Handling

---

# 📷 Project Preview

## Hardware Setup
![Setup](images/setup.jpg)

## Wiring Diagram
![Wiring](images/wiring.jpg)

## Final Box Design
![Box](images/box_design.jpg)

---

# 📊 Testing & Validation

The system was tested through:
- Unit Testing
- Integration Testing
- Multiplayer Gameplay Testing

Validated functionalities include:
- Reliable button debouncing
- Accurate LED timing
- EEPROM persistence
- Sleep mode operation
- Responsive multiplayer interaction

---

# 🔮 Future Improvements

- Wireless multiplayer support
- OLED/TFT graphical display
- Custom PCB design
- Additional gameplay modes
- EEPROM wear leveling

---

# 📂 Repository Structure

```bash
Microcontroller-Gameplay/
│
├── src/
├── include/
├── images/
├── report/
├── README.md
└── LICENSE
```

---

# 👥 Team Members

### Team ID: 24

- Youssef Elfouly
- Clara Maged
- Malik Fathi Adli
- Eslam Ahmed Elsamman
- Youssef Walid

---
**Project Type:** Embedded Systems / Microcontroller Project

---

# 🏆 Conclusion

This project demonstrates the practical implementation of embedded systems concepts through a fully functional multiplayer gaming console.

The combination of hardware integration, AVR programming, FSM architecture, and responsive gameplay mechanics provided valuable experience in real-time embedded software development.


