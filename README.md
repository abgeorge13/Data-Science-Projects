# Hotel Management System using Tkinter

A robust desktop application designed to optimize and streamline daily hotel operations[cite: 1]. Developed as a mini-project for the course **21CSS101J - Programming for Problem Solving** at SRM Institute of Science and Technology[cite: 1]. 

The full project breakdown and layout details can be referenced in the document file named `PPS_Mini_Project_original.docx`.

## 📌 Project Overview
This project targets core hospitality workflows by implementing an interactive graphical user interface (GUI)[cite: 1]. It transitions traditional, complex hotel administration into a cohesive digital workflow, focusing heavily on operational efficiency, accurate bookkeeping, and customer satisfaction[cite: 1].

## 🚀 Key Features
- **Guest Registration (Check-In):** Captures key guest credentials including name, local address, contact number, and estimated duration of stay[cite: 1].
- **Dynamic Room Allocation:** Automatically cross-checks existing records to allocate an available room number across multiple tiers[cite: 1]:
  - Deluxe (Rooms 1–10)[cite: 1]
  - Semi-Deluxe (Rooms 11–25)[cite: 1]
  - General (Rooms 26–45)[cite: 1]
  - Joint Room (Rooms 46–50)[cite: 1]
- **Automated Billing Engine:** Calculates total balances instantly based on room category and number of days spent, with logical checks for applying promotional discounts (e.g., 10% off specific selections)[cite: 1].
- **Transaction History & Receipt Handling:** Generates immediate standalone plaintext invoice records (`recipt.txt`) and launches dynamic receipt script functions (`recipt.py`) upon submission[cite: 1].
- **Local Data Persistence:** Utilizes Python's object serialization library (`pickle`) to maintain guest databases reliably across application restarts via a local file (`hotel.dat`)[cite: 1].

## 🛠️ Tech Stack & Architecture
- **Language:** Python[cite: 1]
- **UI Framework:** Tkinter & Tcl/TTK[cite: 1]
- **GUI Builder:** PAGE (Version 4.14)[cite: 1]
- **Storage Module:** Built-in Object Serialization (`pickle`)[cite: 1]

## 📁 File Structures Used
- `hotel.dat`: The local binary database file where checking/saving records securely preserves client objects[cite: 1].
- `recipt.txt`: Temporary flat-file capturing variables dynamically parsed onto the receipt module[cite: 1].

## 👥 Contributors
Developed by[cite: 1]:
- **Keshav B.S** (RA2311053010144)[cite: 1]
- **Abhinanth .M** (RA2311053010148)[cite: 1]
- **Adorn. B** (RA2311053010149)[cite: 1]

**Course Mentor:** Dr. Haroonhaider Homi Sidhwa (Assistant Professor, Department of ECE, SRMIST)[cite: 1].
