# H-Bridge-PWM-DC-Motor

## 1. Project Overview
This project implements an H-Bridge–based DC motor control system using PWM for efficient speed regulation and bidirectional rotation. By varying the PWM duty cycle, the motor speed is precisely controlled, while the H-Bridge configuration enables forward and reverse operation. The design focuses on safe switching, efficient power handling, and easy interfacing with microcontrollers such as Arduino or ESP32, making it suitable for robotics and automation applications.

-----

## 2. Key Learning Objectives
Understand the working principle of an H-Bridge for bidirectional DC motor control.

Learn PWM-based speed control techniques for DC motors.

Gain experience in schematic design and basic PCB layout practices.

Understand safe motor driving concepts such as switching logic and power handling.

Develop skills to interface motor drivers with microcontrollers like Arduino or ESP32.

-----

## 3. Tools & Software Used
- **KiCad EDA**
  - Schematic Editor  
  - PCB Layout Editor  
  - 3D Viewer
 
 ---

## 4. Project Files
- Schematic design files (`.kicad_sch`)  
- PCB layout files (`.kicad_pcb`)  
- 3D render images  
- Manufacturing-ready Gerber files  

---

## 5. Block-Level Working Explanation
The control unit (microcontroller) generates PWM and direction control signals based on the required motor operation. These signals are fed to the H-Bridge driver circuit, which switches the power transistors accordingly. By changing the PWM duty cycle, the motor speed is controlled, while the H-Bridge configuration determines the direction of rotation. The power supply provides the required voltage and current to drive the motor safely and efficiently.

## 6. Bill of Materials (BOM)

|SNo.| Reference               | Value / Part No.  | Footprint                                                     | Qty | 
| -- | ----------------------- | ----------------- | ------------------------------------------------------------- | --- | 
| 1  | C1, C9                  | 100 nF            | Capacitor_THT:C_Disc_D5.0mm_W2.5mm_P2.50mm                    | 2   |   
| 2  | C2, C8                  | 1 µF              | Capacitor_THT:CP_Radial_Tantal_D4.5mm_P5.00mm                 | 2   | 
| 3  | C3, C4                  | 10 µF             | Capacitor_THT:CP_Radial_D4.0mm_P2.00mm                        | 2   | 
| 4  | C5                      | 1000 µF           | Capacitor_THT:CP_Radial_D10.0mm_P5.00mm                       | 1   |
| 5  | C6, C7                  | 470 nF            | Capacitor_THT:C_Rect_L10.0mm_W3.0mm_P7.50mm_MKS4              | 2   |
| 6  | D1, D4, D5, D6, D7, D10 | 1N5819            | Diode_THT:D_DO-41_SOD81_P10.16mm_Horizontal                   | 6   |
| 7  | D2, D3, D8, D9          | 1N4148            | Diode_THT:D_DO-35_SOD27_P7.62mm_Horizontal                    | 4   |
| 8  | J1                      | XH-Male Connector | Connector_JST:JST_PH_B5B-PH-K_1x05_P2.00mm_Vertical           | 1   |
| 9  | J2                      | KF45 Connector    | TerminalBlock_Phoenix_MKDS-1,5-4-5.08_1x04_P5.08mm_Horizontal | 1   |
| 10 | Q1, Q2, Q3, Q4          | IRF3205           | Package_TO_SOT_THT:TO-220-3_Vertical                          | 4   |
| 11 | R1, R2, R3, R4          | 27 Ω              | Resistor_THT:R_Axial_DIN0204_L3.6mm_D1.6mm_P7.62mm_Horizontal | 4   |
| 12 | U1, U2                  | IR2104            | Package_DIP:DIP-8_W7.62mm                                     | 2   |



## 7. Images & Renders

- **Schematic**
<img width="1182" height="811" alt="image" src="https://github.com/user-attachments/assets/eee296e3-d84b-4b77-a4f6-4c01c58489dc" />


- **PCB Layout**
<img width="1131" height="868" alt="image" src="https://github.com/user-attachments/assets/0fecfa13-09d7-4f7c-b4ae-b23de0f8f155" />
<img width="1119" height="866" alt="image" src="https://github.com/user-attachments/assets/3ca12c1f-390b-411b-ad2c-172a1a0c3cde" />

- **3D View**
 <img width="1063" height="883" alt="image" src="https://github.com/user-attachments/assets/fe3bc5a6-1062-4868-a534-c1700472426a" />
 <img width="1028" height="886" alt="image" src="https://github.com/user-attachments/assets/3fc3e801-03b9-44e9-b9e2-e98e01015727" />

 
---

## 8. Disclaimer
This project is intended for educational and learning purposes only. While the design follows standard engineering practices, it should be reviewed and tested thoroughly before being used in real-world or high-power applications. The author is not responsible for any damage or injury resulting from improper use of this design.
---

## 9. Author
- **Name:** SUJIT KUMAR
- **Toolchain:** KiCad EDA  











