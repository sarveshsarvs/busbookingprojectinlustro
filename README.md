# 🚌 Online Bus Ticket Reservation System (Console-based)

## 📌 Overview
The **Online Bus Ticket Reservation System** is a **console-based** Python application designed to simplify bus ticket booking, passenger management, and ticket viewing.  
It uses **Core Python concepts** along with **CSV file storage** for persistent data management.  
The project is built following the **SDLC (Software Development Life Cycle)** approach for better structure, scalability, and maintainability.

---

## 🎯 Project Objectives
- Automate bus ticket booking through a console-based interface.
- Maintain passenger details and booking history in CSV files.
- Provide a modular and maintainable code structure.
- Implement an **Admin module** for managing booking details.
- Demonstrate **Core Python concepts** in a real-world application.

---

## 📂 Project Structure

```
Bus Booking System/
│
├── Bus Ticket.docx               # Project documentation
├── Main.py                        # Entry point of the application
├── README.md                      # Project details & usage guide
│
├── Passengerinfo.py               # Handles passenger registration & booking
├── TicketShow.py                  # Displays booked ticket details
├── Admin.py                       # Admin operations & management
│
├── adminCredential.csv            # Stores admin credentials
├── passengerData.csv              # Stores passenger booking records
│
├── __pycache__/                    # Python compiled files
│   ├── TicketShow.cpython-312.pyc
│   ├── admin.cpython-312.pyc
│   ├── passengerinfo.cpython-312.pyc
```

---

## 🛠 Features

### **Passenger Module**
- Register new passengers.
- Book tickets by selecting:
  - Bus company name
  - Contact number & address
  - Departure & destination
  - Date and time
  - Number of passengers
  - Seat number(s)
  - Bus type (AC / Non-AC)
  - Boarding point address
- Calculate and display total fare.
- Save booking details to **`passengerData.csv`**.

### **Ticket Viewing Module**
- Retrieve and display ticket details after booking.

### **Admin Module**
- Secure login using credentials from **`adminCredential.csv`**.
- View all booking records.
- Manage passenger data.

---

## 📋 Functional Requirements
1. **Bus Company Details**
2. **Bus Contact Information**
3. **Bus Address**
4. **Departure Location**
5. **Destination Location**
6. **Travel Date & Day**
7. **Passenger Name**
8. **Number of Passengers**
9. **Seat Number(s)**
10. **Bus Type** (AC / Non-AC)
11. **Boarding Point Address**
12. **Total Fare Calculation**
13. **Departure Time**

---

## 🧱 Class Structure

### **1. PassengerRegistration**
**Attributes:**
- `passengerName`
- `noOfPassenger`
- `departureLocation`
- `destinationLocation`
- `selectDay`
- `selectSeatNo`
- `selectBusType`
- `busFare`
- `autoInc`
- `countCol`

---

### **2. PassengerDataCsv**
- Saves passenger details permanently in CSV.

---

### **3. TicketShow**
- Displays ticket details after booking.

---

### **4. Admin**
- Handles admin authentication and booking management.

---

## ▶ How to Run the Project
1. **Install Python 3.12+**
2. **Clone or download** this project folder.
3. Ensure **CSV files** (`adminCredential.csv` and `passengerData.csv`) are present.
4. Run the application:
   ```bash
   python Main.py
   ```
5. Follow on-screen instructions to:
   - Book a ticket
   - View a ticket
   - Login as admin

---

## 📦 Data Storage
- **`passengerData.csv`** → Stores all passenger booking details.
- **`adminCredential.csv`** → Stores admin usernames and passwords.

---

## 🏆 Project Outcome
By working on this project, you will learn:
1. **How to start a Python project** using the SDLC approach.
2. **How to implement modular programming**.
3. **How to store and retrieve data** from CSV files.
4. **How to present results** in a readable format.
5. **Basic admin authentication** system.

---

## 📜 License
This project is for **educational purposes** only. You can modify and use it as per your needs.