
# Low-budget RFID-based Automated Dispatch System
A low-cost embedded RFID dispatch system using STM32 and MFRC522 to automate warehouse item tracking, with real-time feedback and error handling


## 🧾 Project Overview

This is a hardware-based embedded systems project aimed at solving the problem of **manual warehouse dispatch tracking** using a **cost-effective and automated solution**.

Warehouses often rely on manual processes or barcodes for dispatching items, which can cause delays, errors, and require constant human supervision. 
This project eliminates that need by introducing an **RFID-based automated dispatch system** using the **STM32 NUCLEO-G070RB microcontroller** and **RC522 RFID readers**.

---

## ✅ How This Project Solves the Problem

- ✅ Uses **passive RFID tags** to identify items without human interaction
- ✅ Detects entry/exit of items into **Warehouse A** and **Warehouse B**
- ✅ Uses **firmware logic** to store item states, check if it is already stored, and detect if item movement is valid
- ✅ **Real-time display messages** and **LED feedback** guide the user clearly
- ✅ Includes **error handling** to prevent double-storing or warehouse conflicts
- ✅ Built with a **tight hardware budget** (~INR 1794), ideal for student or prototype use

---

## 🧰 Components Used

- STM32 NUCLEO-G070RB (x2)(Two MCUs were used for future scalability and extension; however, the system can also be implemented using a single MCU for basic functionality.)
- RC522 RFID Reader Modules (x2)
- Passive RFID Tags
- LCD/Serial Display Module
- Jumper wires, breadboard, and power supply

---

## 💡 Features

- Real-time RFID-based item detection
- Dual-warehouse entry/exit tracking
- UART debug messaging
- LED blinking feedback on valid transactions
- Error message on invalid transitions (e.g., double entry)
- Display-based user interface for status

---

## 💸 Estimated Hardware Cost

| Component                     | Quantity | Unit Price | Total   |
|------------------------------|----------|------------|---------|
| STM32 NUCLEO-G070RB MCU      | 2        | ₹700       | ₹1400   |
| RFID Module (RC522)          | 2        | ₹122       | ₹244    |
| Jumper wires & misc. items   | —        | —          | ₹150    |
| **Total**                    | —        | —          | ₹1794   |


---

## 🧠 Ideal For

- Engineering students (Embedded Systems, IoT, ECE)
- Prototyping low-cost warehouse automation systems
- Demonstrating real-time control logic with feedback

---

Feel free to clone, build, and extend the system based on your needs.

