# CW2 Embedded Systems 

## 1. Introduction
This project implements a Human-Machine Interface (HMI) on an Arduino Uno using a potentiometer as a temperature sensor, an LCD Keypad Shield for display and user input, and an LED indicator for alarms.  
The system allows setting upper (LH) and lower (LL) temperature limits and lights an LED when the measured temperature goes outside this range.

---

## 2. Project Code

### **Main Application & Modules**

- **Main.ino**  
  [Main.ino](./Main.ino)

- **ADC Module**  
  Header: [ADC.h](./ADC.h)  
  Source: [ADC.ino](./ADC.ino)

- **LCD Module**  
  Header: [LCD.h](./LCD.h)  
  Source: [LCD.ino](./LCD.ino)

- **Buttons Module**  
  Source: [Buttons.ino](./Buttons.ino)

---

## 3. Test Cases

- **Robot Framework Automated Test Suite**  
  [CW2_Tests.robot](./CW2_Tests.robot)

- **Manual Test Case Descriptions**  
  [CW2_Test_Case_Descriptions.robot](./CW2_Test_Case_Descriptions.robot)

---

## 4. Bill of Materials (BOM)

- **Bill of Materials (BOM)**  
  [BOM.xlsx](./BOM.xlsx)

- **Optimised Bill of Materials**  
  [Optimised_BOM.xlsx](./Optimised_BOM.xlsx)

---

## 5. Video Demonstration

- **CW2 Project Video Demonstration**  
  [CW2 Program Video.mp4](./CW2%20Program%20Video%20.mp4)

---

## 6. Design & Documentation

- **Project Design Document**  
  [Project Design.md](./Project%20Design.md)

- **Architecture Diagram (PlantUML)**  
*(included inside design document – see Project Design.md)*
---

## 7. Directory Structure

/CW2_Project
│── README.md
│── Main.ino
│── ADC.h
│── ADC.ino
│── LCD.h
│── LCD.ino
│── Buttons.ino
│── CW2_Tests.robot
│── CW2_Test_Case_Descriptions.robot
│── BOM.xlsx
│── Optimised_BOM.xlsx
│── Project Design.md
│── CW2 Program Video .mp4


---

## 8. Author
Youssef – Coventry University Embedded Systems CW2

