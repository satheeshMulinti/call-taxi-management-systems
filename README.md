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
- **Calculate Fare** – Automatic fare calculation based on distance.
- **Trip History** – View past bookings and trip details.
- **Persistent Data** – All taxi and trip data saved in text files.
- **OOP Design** – Uses classes, constructors, and file I/O.

---

## 🛠 Technologies Used
- **Language:** C++
- **Compiler:** GCC, Code::Blocks, Dev-C++, or Visual Studio
- **File Handling:** Text files (`.txt`) for data storage
- **Concepts Used:**
  - Classes and Objects
  - File I/O
  - Vectors and Arrays
  - Control Structures

---

## 🔄 Project Workflow
1. Customer opens the system
2. Selects "Book Taxi" option
3. Enters pickup and drop location
4. System checks available taxis
5. Assigns nearest free taxi
6. Calculates fare and confirms booking
7. Stores booking details in file

---

## 📥 Installation

### Prerequisites
- C++ compiler (GCC, Clang, MSVC)
- IDE (Code::Blocks, Dev-C++, Visual Studio, or any text editor)

### Steps

```bash
# Clone the repository
git clone https://github.com/satheeshMulinti/call-taxi-management-systems.git

# Navigate to the project folder
cd call-taxi-management-systems
```

---

## ▶️ How to Run

### Using Command Line (Linux/Mac)

```bash
g++ "call taxi management system program.cpp" -o taxi_system
./taxi_system
```

### Using Command Line (Windows)

```cmd
g++ "call taxi management system program.cpp" -o taxi_system.exe
taxi_system.exe
```

### Using IDE
- Open "call taxi management system program.cpp" in Code::Blocks / Dev-C++
- Compile and run directly from the IDE

---

## 🏗 Code Structure

```
📂 call-taxi-management-systems
 ├── call taxi management system program.cpp   # Main source code
 ├── call taxi management system program.exe   # Executable file
 ├── README.md                                 # Project documentation
```

---

## 📏 Evaluation

The project can be evaluated on:
- **Functionality** – All booking features work as expected
- **Code Quality** – Proper use of OOP principles
- **Efficiency** – Correct taxi assignment logic
- **User Experience** – Simple and clear interface
- **Persistence** – Data saved and retrieved correctly from files

Example function call in code:

```cpp
Taxi t;
t.bookTaxi("LocationA", "LocationB", 10); // 10 km distance
```

---

## 🖥 Sample Output

```
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
```

---

## 🚀 Future Enhancements
- Add graph-based shortest route calculation
- Integrate real-time location updates
- Add GUI using Qt or SFML
- Implement payment gateway simulation
- Multi-user support with login system

---

## 🤝 Contributing

Contributions are welcome! If you want to improve this project:
1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature-branch`)
5. Open a Pull Request

---

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## 📧 Contact

For any queries or suggestions, feel free to reach out:
- **GitHub:** [satheeshMulinti](https://github.com/satheeshMulinti)

---

⭐ **If you find this project helpful, please give it a star!** ⭐
