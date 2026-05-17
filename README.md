# 🔧 Servo Tester PCB Design

A simple and compact **Servo Tester Circuit** designed using **KiCad EDA 9.0.2** for generating PWM signals to test and control standard servo motors.

---

## 📌 Project Overview

This project uses the **NE555 Timer IC** to generate PWM (Pulse Width Modulation) signals required for controlling servo motor position.

By adjusting the potentiometer, the pulse width changes, allowing smooth servo movement and position testing.

---

## 🖼 Project Schematic

```md
![Servo Tester Schematic](images/schematic.png)
```

---

## ⚙ Features

- Servo motor testing
- PWM signal generation
- Adjustable servo position control
- Compact PCB design
- LED power indication
- Simple and beginner-friendly circuit

---

## 🛠 Software Used

| Tool | Version |
|------|---------|
| KiCad EDA | 9.0.2 |

---

## 🔩 Components Used

| Component | Value / Part |
|-----------|--------------|
| U1 | NE555 Timer IC |
| D1 | 1N4148 Diode |
| D2 | LED |
| C1 | 22nF Capacitor |
| R1 | 1KΩ Resistor |
| R2 | 3M3Ω Resistor |
| R3 | 56KΩ Resistor |
| RV1 | 100K Potentiometer |
| J1 | DC Input Connector |
| J2 | Servo Motor Connector |

---

## 🔍 Working Principle

### 1. PWM Signal Generation
The NE555 timer IC generates PWM pulses required for servo motor operation.

### 2. Pulse Width Adjustment
The potentiometer changes the pulse width, which controls the servo angle.

### 3. Servo Control
The generated PWM signal is sent to the servo motor through the signal pin.

### 4. Power Indication
An LED indicator shows the power status of the circuit.

---

## 📐 PCB Design Highlights

- Compact schematic structure
- Beginner-friendly design
- Proper component organization
- Easy PCB routing
- Suitable for learning embedded hardware concepts

---

## 🎯 Learning Outcomes

Through this project, I learned:

- PWM signal generation
- Servo motor interfacing
- NE555 timer configuration
- PCB schematic design in KiCad
- Electronic timing circuit fundamentals

---

## 🚀 Future Improvements

- Add frequency adjustment feature
- Add OLED display for pulse width monitoring
- Add multiple servo output ports
- Design compact single-layer PCB
- Add onboard power regulation

---

## 📂 Project Structure

```bash
Servo-Tester/
│
├── Servo Tester.kicad_sch
├── Servo Tester.kicad_pcb
├── Gerber_Files/
├── Images/
├── BOM/
└── README.md
```

---

## 📸 Recommended Images for Repository

Add these images inside the `images/` folder:

- Schematic Screenshot
- PCB Layout
- 3D PCB View
- Final PCB
- Servo Testing Setup

---

## 🧠 Skills Demonstrated

- PCB Design
- PWM Control
- Servo Interfacing
- KiCad EDA
- Embedded Electronics
- Hardware Development

---

## 👨‍💻 Author

**Suman**  
Electronics & PCB Design Enthusiast

---

## 📜 License

This project is open-source and intended for educational and learning purposes.
