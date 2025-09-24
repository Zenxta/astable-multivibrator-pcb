# Astable Multivibrator Circuit

This is a PCB design for a transistor-based astable multivibrator, a simple square wave oscillator. The circuit is configured to use two NPN transistors in a common emitter configuration, which causes two LEDs to flash alternately, demonstrating a 180-degree phase shift. The entire design was created using KiCad software.

## Components

| Component | Value | Description |
| :--- | :--- | :--- |
| **Transistors** | 2N3904 (Q1, Q2) | Two NPN bipolar junction transistors. |
| **Resistors** | 300 Ω (R1, R4) | Current-limiting resistors for the LEDs. |
| | 47 kΩ (R2, R3) | Resistors that control the transistor's base voltage and the timing of the oscillation. |
| **Capacitors** | 10 µF (C1, C2) | Timing capacitors that alternately charge and discharge to create the oscillation. |
| **Diodes** | LED (D1, D2) | Light Emitting Diodes that provide a visual indication of the output. |
| **Switch** | SPDT (SW1) | Single Pole Double Throw switch to control the circuit. |
| **Power** | Battery (BT1) | A power source for the circuit. |
| **Mounting** | H1, H2, H3, H4 | Four mounting holes for securing the PCB. |

## Design Files

All design files for this project are included in the repository and can be opened with KiCad.

* **Schematic:** `astable-multivibrator.kicad_sch`
* **PCB Layout:** `astable-multivibrator.kicad_pcb`

## Images

### Schematic Diagram
### PCB Layout (Top View)
### PCB Layout (Bottom View)
