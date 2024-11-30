# Automated Google Dino Game Using LDRs and Servo Motor

## **Introduction**
This project automates the Google Chrome Dino Game by detecting obstacles and simulating a spacebar press using a servo motor. It uses three LDRs to monitor the game screen and identify obstacles.

---

## **Components**
- 3 x Light Dependent Resistors (LDRs)
- 3 x 10kΩ Resistors
- 1 x Servo Motor
- 1 x Microcontroller (e.g., Arduino)
- 1 x 5V Power Supply
- Jumper Wires and Breadboard

---

## **Circuit Setup**

### **1. LDRs**
- One leg of each LDR connects to the **5V power supply**.
- The other leg connects to a **10kΩ resistor**, with the resistor's other end connected to **GND**.
- The junction between the LDR and resistor connects to the microcontroller's **analog input pins** (A0, A1, A2).

### **2. Servo Motor**
- Red wire to **5V**.
- Black/Brown wire to **GND**.
- Yellow/Orange wire to **Digital Pin D9**.

### **3. Power Supply**
- Use a common **5V power source** for all components.
- Connect all GND lines together.

---

## **Working**
1. **Obstacle Detection:**
   - The LDRs detect changes in light intensity corresponding to background, ground-level obstacles, and airborne obstacles (birds).
2. **Signal Processing:**
   - The microcontroller compares the analog input from the LDRs to preset threshold values.
3. **Jump Action:**
   - If an obstacle is detected, the microcontroller activates the servo motor to simulate a spacebar press.









