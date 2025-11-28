# Alarm Security System using BJT

This project is a low-cost and reliable **Security Alarm System** utilizing a **Bipolar Junction Transistor (BJT)** and a **Silicon-Controlled Rectifier (SCR)**. The system is designed to detect unauthorized access by sensing interruptions in an **Infrared (IR) beam** and activating an audible alarm.

The core sensing mechanism uses an IR LED and photodiode setup. Any disturbance in the IR signal leads to a voltage change, which is amplified by the BJT circuit. This amplified signal then sends a triggering pulse to the SCR gate, causing it to latch into conduction mode and power the alarm device.
The alarm remains active until manually reset, ensuring intrusions are promptly and effectively reported, even if the triggering event is brief.

---

### **Key Features**

* **Sensing Mechanism:** Uses an invisible **IR LED** and **IR Photodiode** setup, creating an unobtrusive security perimeter.
* **Persistent Alert (Latching):** The **TYN612 SCR** provides a latching function; once triggered, it remains in the ON state until manually reset, preventing intruders from quickly passing through and silencing the system.
* **Adjustable Sensitivity:** A **$100\ k\Omega$ Potentiometer** is used to fine-tune the circuit's sensitivity, making it suitable for different lighting conditions.
* **Cost-Effective:** The system is simple, safe, affordable, and typically assembled for under $20 using readily available electronic components.
* **Power & Enclosure:** Powered by rechargeable **18650 Li-ion cells** and protected by a custom 3D-printed enclosure with an integrated Type-C charging module.

---

## Components

| Component | Type | Quantity | Description |
| :--- | :--- | :--- | :--- |
| **Transistor** | BC547 (BJT) | 1 | Amplifies the weak signal from the photodiode to trigger the SCR. |
| **Latching Device** | TYN612 (SCR) | 1 | Maintains alarm status (latched ON) until power is interrupted. |
| **Sensing Pair** | IR LED, IR Diode | 1, 1 | Creates and detects the invisible security beam. |
| **Adjuster** | Potentiometer ($100\ k\Omega$) | 1 | Used to fine-tune the circuit's sensitivity to light conditions. |
| **Output** | Buzzer | 1 | Audible alert device that activates when the SCR is triggered. |
| **Power** | Li-ion Cell (18650) | 2 | Rechargeable power source for the circuit. |
| **Charging** | TP4056 Module | 1 | Facilitates Type-C charging for the cells within the enclosure. |

---

## Design & Project Files

All design files for this project are included in the repository and were created using **Altium Designer** (for PCB) and **Autodesk Fusion** (for enclosure).

* **Schematic:** `Security_Alarm_System.SchDoc`
* **PCB Layout:** `Security_Alarm_System.PcbDoc`
* **Gerber Files:** `Gerber_Files.zip` (Includes: `Gerber1`, `Gerber2`, `Drillfile1`, `Drillfile2`)
* **Enclosure CAD:** `Enclosure_Design.STEP`
* **Bill of Materials (BOM):** `Alarm_Security_System_BOM.xlsx`

---

## Images

### Schematic Diagram

<img width="1200" height="800" alt="Schematic Diagram of the BJT-SCR Security Alarm Circuit" src="[INSERT SCHEMATIC IMAGE URL HERE]" />

### PCB Layout

<img width="1200" height="800" alt="PCB Layout for the BJT-SCR Security Alarm" src="[INSERT 2D PCB LAYOUT IMAGE URL HERE]" />

### 3-D View of PCB (front and back)

<img width="1000" height="700" alt="3D Render of the Assembled PCB and Components (Front)" src="[INSERT 3D PCB RENDER FRONT IMAGE URL HERE]" />

<img width="1000" height="700" alt="3D Render of the Assembled PCB and Components (Back)" src="[INSERT 3D PCB RENDER BACK IMAGE URL HERE]" />

---

## Hardware Implementation

The circuit was verified on a breadboard and permanently assembled on a perforated board, then housed in a custom 3D-printed enclosure.

### Breadboard Prototype

Initial testing was conducted on a breadboard to verify circuit flow and functionality before permanent assembly.

<img width="800" height="600" alt="Breadboard connection of the Alarm Security System" src="[INSERT FIGURE 5.1 BREADBOARD IMAGE URL HERE]" />

### Final Assembly & Enclosure

The final circuit was soldered for stability and integrated into an enclosure designed in **Autodesk Fusion** to house the electronics, battery, and charging port.

<img width="800" height="600" alt="Testing the soldered PCB with the indicator LED lit" src="[INSERT FIGURE 5.3 TESTING IMAGE URL HERE]" />

<img width="800" height="600" alt="Final 3D printed enclosure showing the assembled circuit inside" src="[INSERT FIGURE 5.4/5.5 ENCLOSURE IMAGE URL HERE]" />

---

## Future Work

The system can be enhanced by integrating advanced features for greater functionality and scalability:

* **Microcontroller Integration:** Incorporating an Arduino or ESP32 to enable features like automatic alarm reset, timed alerts, and data logging.
* **Wireless Notifications:** Integrating a GSM module or IoT system to send SMS alerts or app notifications upon intrusion.






