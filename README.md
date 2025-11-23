🎓 Student Record Management System
A GUI-based CRUD Application using Qt & C++

📌 Project Overview

This Student Record Management System is a desktop-based GUI application built using Qt (C++). It provides complete CRUD operations—Add, Update, Delete, Search, and Navigate student records. All information is stored in a CSV file, ensuring simplicity and portability.

✔ User-friendly interface
✔ CSV-based storage (no database needed)
✔ Input validation & unique roll number checking
✔ Modular code with separate .cpp, .h, and UI files

🚀 Features
🔹 1. Add Student

Enter name, roll no, father name, caste, district, GPA

Validates empty fields

Ensures unique roll numbers

Saves automatically to students.csv

🔹 2. Update Student

Allows editing of all fields except roll number

Automatically saves updated data to CSV

🔹 3. Delete Student

Removes the selected record permanently

Auto-refreshes to next record

🔹 4. Search Student

Search by Roll Number

Instantly displays matching record

🔹 5. View (Next Navigation)

Browse all saved student records one-by-one

🛠 Tech Stack
Component	Technology
GUI	Qt Widgets
Programming Language	C++ (OOP)
Build System	CMake
File Storage	CSV/Text file
📂 Project Structure
📁 Student-Record-Management-System
 ├── main.cpp
 ├── mainwindow.cpp
 ├── mainwindow.h
 ├── mainwindow.ui
 ├── CMakeLists.txt
 ├── students.csv
 └── README.md

🖼 Application Screenshots
➕ Add Operation

✏ Update Operation

🔍 Search Operation

🗑 Delete Operation

🧠 How to Run
🔧 Requirements

Qt Creator / Qt 5 or Qt 6

C++17 support

CMake 3.16+

▶ Steps

Clone the repository

Open the project in Qt Creator

Build → Run

students.csv will be automatically created

💡 Learning Outcomes

✔ GUI Development in Qt
✔ File Handling (CSV)
✔ Event-driven programming
✔ Structs, vectors, and modular coding in C++
✔ Debugging & input validation

📘 Project Conclusion

This project provides a lightweight, efficient solution for managing student records using Qt and C++. With its intuitive interface, proper validation, persistent storage, and modular structure, it demonstrates strong fundamentals of GUI programming, file handling, and OOP. It forms an excellent foundation for future enhancements such as database integration, login system, and advanced reporting.
