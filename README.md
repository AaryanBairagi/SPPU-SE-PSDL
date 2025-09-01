
# 🔌 PSDL – Embedded Systems Lab

**Savitribai Phule Pune University | TE IT (2019 Course)**  
**GitHub Repo – Practical Assignments (Embedded C / PIC18F / Arduino / Raspberry Pi)**

---

## 📁 Repository Structure

Each folder corresponds to a group (A, B, C, D).  
Inside each group, assignments are stored as `.c` or `.ino` files (and notes where applicable).

```

📂 GroupA
├── assignment\_01\_addition.c
├── assignment\_02\_array\_sum.c
├── assignment\_03\_memory\_transfer.c
├── assignment\_04\_menu\_multiply\_divide.c
└── assignment\_05\_sorting.c

📂 GroupB
├── assignment\_06\_led\_blink\_pic.c
├── assignment\_07\_timer\_isr\_buzzer.c
├── assignment\_08\_external\_interrupt\_relay.c
└── assignment\_09\_lcd\_interfacing\_pic.c

📂 GroupC
├── assignment\_10\_pwm\_servo.c
├── assignment\_11\_uart\_pc\_to\_pc.c
└── assignment\_12\_temp\_sensor\_adc\_lcd.c

📂 GroupD
├── assignment\_13\_study\_arduino\_rpi.md   # Theory only
└── assignment\_14\_digital\_analog\_io.ino  # Arduino / Raspberry Pi code

````

---

## 📌 Assignment Details

### Group A — CO1, CO2 (Any Three)

#### 1 — Addition of Two Numbers
* **File**: `assignment_01_addition.c`  
* **Task**: Simple Embedded C program to add two 8-bit numbers and show result on LEDs.

#### 2 — Add Array of *n* Numbers
* **File**: `assignment_02_array_sum.c`  
* **Task**: Sum elements of an array and display result.

#### 3 — Memory Transfer
* **File**: `assignment_03_memory_transfer.c`  
* **Task**: Copy data from internal → internal and internal → external memory.

#### 4 — Menu Driven Multiply & Divide
* **File**: `assignment_04_menu_multiply_divide.c`  
* **Task**: Menu-driven program to multiply/divide 8-bit numbers.

#### 5 — Sorting
* **File**: `assignment_05_sorting.c`  
* **Task**: Bubble sort numbers in ascending/descending order.

---

### Group B — CO3 (Any Three)

#### 6 — LED Blink
* **File**: `assignment_06_led_blink_pic.c`  
* **Task**: Interface LED with PIC18FXXX and blink with delay.

#### 7 — Timer ISR Buzzer
* **File**: `assignment_07_timer_isr_buzzer.c`  
* **Task**: Use Timer interrupt to toggle buzzer ON/OFF.

#### 8 — External Interrupt Relay
* **File**: `assignment_08_external_interrupt_relay.c`  
* **Task**: Switch press via INT0 → drive relay output.

#### 9 — LCD Interfacing
* **File**: `assignment_09_lcd_interfacing_pic.c`  
* **Task**: Interfacing 16x2 LCD with PIC18FXXX.

---

### Group C — CO10 (Any Two)

#### 10 — PWM Signal
* **File**: `assignment_10_pwm_servo.c`  
* **Task**: Generate PWM for servo/DC motor control.

#### 11 — UART PC-to-PC
* **File**: `assignment_11_uart_pc_to_pc.c`  
* **Task**: Serial communication between PCs via UART.

#### 12 — Temperature Sensor + LCD
* **File**: `assignment_12_temp_sensor_adc_lcd.c`  
* **Task**: Read temperature sensor via ADC and display on LCD.

---

### Group D — CO4 (Mandatory)

#### 13 — Arduino & Raspberry Pi Study
* **File**: `assignment_13_study_arduino_rpi.md`  
* **Task**: Study Arduino board & Raspberry Pi OS installation (theory only).

#### 14 — Digital & Analog IO
* **File**: `assignment_14_digital_analog_io.ino`  
* **Task**:  
   - Digital read/write: LED + switch  
   - Analog read/write: sensor + actuator (PWM control)

---

## 🔧 Tech Stack
* **Language**: Embedded C (XC8), Arduino C++, Python (for Raspberry Pi)  
* **Hardware**: PIC18F4550, Arduino Uno/Nano, Raspberry Pi  
* **Tools**: MPLAB X IDE + XC8, Arduino IDE, Proteus (for simulation)

---

## 🚀 Quick Start

### PIC (XC8 + MPLAB X)
```bash
# Open MPLAB X
# Load .c file into a new project
# Select target device (PIC18F4550)
# Build → Program device using PICkit
````

### Arduino

```bash
# Open Arduino IDE
# Load .ino file
# Select Board + Port
# Upload to Arduino
```

### Raspberry Pi

```bash
sudo apt update && sudo apt install python3-rpi.gpio spidev -y
python3 assignment_14_rpi.py
```

---

## 🙌 Author

**Aaryan Bairagi**
TE IT | Savitribai Phule Pune University
GitHub: [@AaryanBairagi](https://github.com/AaryanBairagi)

---

## 📌 License

This project is for academic learning only.
© 2025 Aaryan Bairagi – All rights reserved.

---

