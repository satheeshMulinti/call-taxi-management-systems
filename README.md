# 🚖 Call Taxi Management System (C++)

## 📌 Overview
The **Call Taxi Management System** is a console-based application built in **C++** that simulates a taxi booking and management service.  
It allows customers to book taxis, view available taxis, check fare details, and allows the system to manage trip assignments efficiently.  

This project is designed for students and beginners to understand **object-oriented programming (OOP)** concepts, file handling, and basic algorithm implementation in C++.

---

## 🗂 Table of Contents
1. [Project Motivation](#-project-motivation)
2. [Features](#-features)
3. [Technologies Used](#-technologies-used)
4. [Project Workflow](#-project-workflow)
5. [Installation](#-installation)
6. [How to Run](#-how-to-run)
7. [Code Structure](#-code-structure)
8. [Evaluation](#-evaluation)
9. [Sample Output](#-sample-output)
10. [Future Enhancements](#-future-enhancements)
11. [Contributing](#-contributing)
12. [License](#-license)

---

## 🎯 Project Motivation
Taxi services need efficient booking and allocation systems to reduce waiting time and maximize usage of vehicles.  
This project was built to:
- Learn **OOP concepts** like classes, inheritance, and encapsulation
- Implement **data storage** using file handling
- Simulate **real-world taxi booking** scenarios in a simple console app

---

## ✨ Features
- **Book Taxi** – Customer can book a taxi by entering pickup and drop locations.
- **View Available Taxis** – Display taxis free at the given time.
- **Fare Calculation** – Based on distance and time.
- **Trip Records** – Stores past booking details.
- **Taxi Assignment Logic** – Allocates nearest available taxi.
- **Persistent Storage** – Saves taxi and trip details in text files.

---

## 🛠 Technologies Used
- **Language:** C++
- **Concepts:**
  - Object-Oriented Programming (OOP)
  - File Handling (`fstream`)
  - Data Structures (arrays, structs, vectors)
  - Basic algorithms for taxi allocation
- **Environment:** Code::Blocks, Dev-C++, or any C++ compiler

---

## 📋 Project Workflow
1. **User Input** – Customer enters pickup/drop details.
2. **Check Availability** – System checks free taxis.
3. **Taxi Assignment** – Nearest taxi assigned based on location and availability.
4. **Fare Calculation** – Based on distance and rate.
5. **Store Records** – Save booking details for future reference.
6. **Display Output** – Show booking confirmation.

---

## ⚙ Installation
```bash
# Clone the repository
git clone https://github.com/yourusername/Call-Taxi-Management-System.git

▶ How to Run
Option 1: Using Terminal
g++ taxi_management.cpp -o taxi
./taxi

Option 2: Using IDE

Open taxi_management.cpp in Code::Blocks / Dev-C++

Compile and run directly from the IDE

🏗 Code Structure
📂 Call-Taxi-Management-System
 ├── taxi_management.cpp   # Main source code
 ├── taxis.txt             # Stores taxi details
 ├── trips.txt             # Stores booking history
 ├── README.md             # Project documentation
 └── LICENSE               # License file

📏 Evaluation

The project can be evaluated on:

Functionality – All booking features work as expected

Code Quality – Proper use of OOP principles

Efficiency – Correct taxi assignment logic

User Experience – Simple and clear interface

Persistence – Data saved and retrieved correctly from files

Example function call in code:

Taxi t;
t.bookTaxi("LocationA", "LocationB", 10); // 10 km distance

🖥 Sample Output
Welcome to Call Taxi Management System
1. Book Taxi
2. View Available Taxis
3. Exit
Enter choice: 1

Enter Pickup Location: A
Enter Drop Location: C
Distance: 12 km
Taxi Assigned: T2
Fare: ₹240
Booking Confirmed!

🚀 Future Enhancements

Add graph-based shortest route calculation

Integrate real-time location updates

Add GUI using Qt or SFML

Implement payment gateway simulation

Multi-user support with login system

# Navigate to the project folder
cd Call-Taxi-Management-System
