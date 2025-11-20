# Astable Multivibrator Circuit

This is a PCB design for a transistor-based astable multivibrator, a simple square wave oscillator. The circuit is configured to use two NPN transistors in a common emitter configuration, which causes two LEDs to flash alternately, demonstrating a 180-degree phase shift. The entire design was created using KiCad software.

## Components

| Component | Value | Description |
| :--- | :--- | :--- |
| **Transistors** | 2N3904 (Q1, Q2) | Two NPN BJTs. |
| **Resistors** | 300 Ω (R1, R4) | Resistors for the LEDs. |
| | 47 kΩ (R2, R3) | Resistors to control transistor's base voltage and timing of the oscillation. |
| **Capacitors** | 10 µF (C1, C2) | Timing capacitors that charge and discharge alternatively to create the oscillation. |
| **Diodes** | LED (D1, D2) | LEDs that provide a visual indication of the output. |
| **Switch** | SPDT (SW1) | Single Pole Double Throw switch to control the circuit. |
| **Power** | Battery (BT1) | A power source for the circuit. |
| **Mounting** | H1, H2, H3, H4 | Four mounting holes for holding the PCB. |

## Design Files

All design files (downloadable) for this project are included in the repository and can be opened with KiCad. 

* **Schematic:** [Download schematic.kicad_sch](https://raw.githubusercontent.com/Zenxta/astable-multivibrator-pcb/main/schematic.kicad_sch?download=1)
* **PCB Layout:** [Download pcb board.kicad_pcb](https://raw.githubusercontent.com/Zenxta/astable-multivibrator-pcb/main/pcb_board.kicad_pcb?download=1)

## Images

### Schematic Diagram
<img width="1239" height="873" alt="Screenshot 2025-09-25 004303" src="https://github.com/user-attachments/assets/c00a03e1-d575-4604-bcab-3bc7f0ae4c0e" />

### PCB Layout

<img width="1580" height="930" alt="Screenshot 2025-09-25 010611" src="https://github.com/user-attachments/assets/f4306b3e-d9d2-4de8-8cb1-074ee8231372" />


