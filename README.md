# INTELLIVOTE-AN-RFID-BASED-SMART-ELECTRONIC-VOTING-SYSTEM

---

## 👨‍💻 Project Overview:

This project presents a secure and efficient RFID-based voting system developed using embedded systems. The main objective of this system is to ensure that only authorized voters can cast their vote within a defined time period, while maintaining data integrity and security.

The system integrates multiple hardware modules such as RFID reader, RTC, EEPROM, LCD, and keypad to create a real-time voting environment. It also includes a separate control mechanism for the election officer to manage voting operations like start, stop, result viewing, and system reset.

---

## 🎯 Project Objective:

The main objective of this project is to develop a secure and reliable electronic voting system using RFID authentication.

---

## 🛠️ Hardware Components:

- LPC21xx / ARM7 Microcontroller
- RFID Reader
- RFID Card/Tag
- 20x4 LCD
- 4x4 Keypad
- AT24C256 EEPROM
- RTC
- LEDs

---

## 💻 Software Tools:

- Embedded C
- Keil uVision
- ARM7 / LPC21xx

---

## ⚙️ Working:

1. The voter scans the RFID card.
2. The RFID reader reads the unique RFID ID.
3. The microcontroller checks whether the voter is authorized.
4. If the voter is authorized, voting access is provided.
5. The voter selects the required candidate using the keypad.
6. The vote is stored in the system.
7. The LCD displays the voting status.
8. The RTC maintains the date and time of the voting process.

---

## 💾 EEPROM:

The AT24C256 EEPROM is used for non-volatile data storage. Important configuration and voting-related data can be stored in EEPROM and retained even when the power supply is removed.

---

## 🔐 RFID Authentication:

RFID is used to identify and authenticate voters. Only registered/authorized RFID cards are allowed to proceed with the voting process.

---

## 📺 LCD:

The 20x4 LCD is used to display system messages such as:

- Scan RFID Card
- Access Granted
- Access Denied
- Select Candidate
- Vote Successful

---

## ⌨️ Keypad:

A 4x4 matrix keypad is used for voter input and officer/admin operations.

---

## 👨‍💻 Author:

**Harsha Vardhan Ravulapalli**

**Embedded Systems | Embedded C | ARM7 | LPC21xx**
