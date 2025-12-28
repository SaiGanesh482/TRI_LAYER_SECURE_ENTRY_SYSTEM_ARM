# TRI_LAYER_SECURE_ENTRY_SYSTEM_ARM
This project implements a three-level secure access system using:  ✅ RFID Authentication ✅ Password Verification (Keypad) ✅ OTP Verification (GSM Module via UART0)
The system is built on the LPC2148 ARM7 microcontroller and integrates a 4×4 keypad, LCD, RFID reader (UART1), GSM module (UART0), and I2C EEPROM for secure storage of RFID and password data. Upon successful authentication, the LED on P0.25 is activated.
