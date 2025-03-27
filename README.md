# Flight Management System

A comprehensive Flight Management System (FMS) built in C++ to facilitate flight bookings, manage reservations, handle customer complaints, and provide information on flight routes.

## 📋 Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [System Requirements](#system-requirements)
- [Installation](#installation)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Classes Overview](#classes-overview)
- [Future Enhancements](#future-enhancements)
- [Contributors](#contributors)
- [License](#license)

## 📖 Introduction

The **Flight Management System** is a console-based C++ application that allows users to:
- Book flights (local and international)
- Manage bookings (update or cancel)
- Lodge complaints
- View available flight routes
- Access "Pick and Drop" services

The system also allows staff to update and maintain flight records efficiently.

---

## ⭐ Features

✅ Flight Booking (Local and International)  
✅ Seat Class Selection (Economy & Business)  
✅ Flight Payment Calculation  
✅ Flight Ticket Generation & Storage  
✅ Booking Management (Date Change, Cancellation)  
✅ Complaint Registration System  
✅ Automated Pick and Drop Service  
✅ Interactive Menu-Based Navigation  

---

## 💻 System Requirements

- Operating System: Windows/Linux/MacOS  
- Compiler: g++ (GCC) or any other compatible C++ compiler  
- Minimum RAM: 4GB  

---

## ⚙️ Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/flight-management-system.git
   cd flight-management-system
   ```

2. **Compile the Code:**
   Ensure you have a C++ compiler installed (e.g., `g++` on Linux/Windows with MinGW).
   ```bash
   g++ main.cpp -o flight_system
   ```

3. **Run the Application:**
   ```bash
   ./flight_system
   ```

---

## 📊 Usage

1. **Booking a Flight:**
   - Choose between Local and International destinations.
   - Select Class (Economy/Business).
   - Provide passenger details and departure date.

2. **Managing Bookings:**
   - Modify booking date.
   - Cancel reservations.

3. **Complaint Handling:**
   - Submit a complaint related to Airport Handling, Baggage Delivery, or Other.

4. **View Available Routes:**
   - Display international and local flight routes.

5. **Pick and Drop Service:**
   - Option to add ground transportation to/from the airport.

---

## 📂 File Structure

```
📦 flight-management-system
├── 📜 main.cpp          // Main implementation
├── 📜 payment.h        // Payment calculation header
└── 📜 flight.txt       // Stores ticket information
```

---

## 🧱 Classes Overview

- **`passenger`**: Base class for managing passenger data.
- **`booking`**: Handles seat allocation, flight class, and meal options.
- **`Manage`**: Modify or cancel existing bookings.
- **`about`**: Provides airline history and background.
- **`complain`**: Accepts and records passenger complaints.
- **`routes`**: Displays available flight paths (local/international).

---

## 🚀 Future Enhancements

- Add an admin panel for advanced management.
- Implement user authentication and account tracking.
- Integrate real-time flight status updates.
- Export tickets to PDF.

---

## 👥 Contributors

- **Siddhesh** - Developer & Maintainer

---

## 📜 License

This project is licensed under the **MIT License**. Feel free to use and modify it.

---
