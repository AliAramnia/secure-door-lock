# 🔐 Secure Electronic Door Lock System

> **Course Project – Electronics for Embedded Systems**  
> Politecnico di Torino – Semester 1 / 2024–2025  
> Supervisor: Prof. Claudio Passerone  
> Student: Ali Aramnia

---

## 📘 Description

This project presents a secure electronic door lock system combining an **STM32F103C8T6 microcontroller** and a **PYNQ-Z2 FPGA** board. The system handles **user authentication**, **password hashing (SHA-256)**, and **peripheral control** using UART and I2C protocols.

It simulates real-world access control via hardware logic, cryptography, and digital communication.

---

## 🧩 Key Features

- **8-digit password input** via FPGA slide switches  
- **SHA-256** hash stored in STM32 flash memory  
- **UART communication** between FPGA and MCU (custom VHDL FSM)  
- **I2C interface** for ADC input  
- **Relay simulation** using BJT + LEDs  
- **Visual feedback** using 4-bit LED output  
- **Button-controlled trigger** for enroll/unlock modes

---

## 🛠 Technologies Used

- STM32 (HAL & LL in C, CubeIDE)  
- PYNQ-Z2 FPGA (VHDL, Vivado)  
- cmox_crypto (SHA-256)  
- UART + I2C protocols  
- PCF8591 ADC Module  
- GPIO, LED, relay simulation logic

---

## 📂 Repository Structure


📬 For questions or collaborations, feel free to reach out!
📩 Contact: Aliaramniaa@gmail.com  
🔗 LinkedIn: [linkedin.com/in/aliaramnia](https://www.linkedin.com/in/aliaramnia)
