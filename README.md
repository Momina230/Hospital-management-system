**Hospital Management System**

This project is a **Hospital Management System** developed in C++. It is a simple, console-based program designed to streamline the management of hospital records. 
The system allows users to manage **patients** and **doctors** by adding their details, storing them in files, and displaying the records as needed. 
This project is ideal for learning file handling, structures, and menu-driven programming in C++.


# Project Explanation

The Hospital Management System is divided into two main modules:
1. **Patient Management**: Allows for registering and viewing patient details. Each patient has attributes such as ID, name, age, gender, and diagnosis.
2. **Doctor Management**: Facilitates the addition and display of doctor information, including ID, name, and specialization.

# Key Features:
- **File Storage**: The program stores all data in text files (`patient.txt` and `doctorfile.txt`) to ensure data persistence even after the program exits.
- **Structured Data Handling**: Uses C++ structs to organize and manage records for both patients and doctors.
- **Dynamic Interaction**: A menu-driven approach ensures an intuitive user experience for selecting options.

The program is designed with scalability in mind, with the capacity to handle up to 100 patients and 25 doctors. 

# Use Case:
This system could serve as a starting point for building a more comprehensive hospital management application by incorporating additional functionalities like search, update, and delete operations or by integrating a database for robust data management.

# Features
1. **Add New Patient:**
   - Register a new patient by entering their details (ID, name, age, gender, and diagnosis).
   - Saves the data persistently in `patient.txt`.

2. **Display All Patients:**
   - Retrieves and displays all patient records from `patient.txt`.

3. **Add New Doctor:**
   - Register a new doctor with their details (ID, name, and specialization).
   - Saves the data persistently in `doctorfile.txt`.

4. **Display All Doctors:**
   - Retrieves and displays all doctor records from `doctorfile.txt`.

5. **Exit the Program:**
   - Exits the program gracefully.


# File Structure
- **`main.cpp`**: The main source code file for the program.
- **`patient.txt`**: Stores patient records.
- **`doctorfile.txt`**: Stores doctor records.


# How to Use
1. Clone this repository to your local system.
 
  sample:  git clone <repository-url>
2. Open the project in your favorite C++ IDE or compile using a terminal
 sample: g++ main.cpp -o HospitalManagementSystem
 
3.Run the executable:
sample: ./HospitalManagementSystem

4.Use the menu to navigate through options

# Requirements:
C++ Compiler (e.g., GCC)
Basic understanding of C++ and file handling

# Future Enhancements:
1-Implement error handling for file operations.
2-Add search functionality for patients and doctors.
3-Implement update and delete functionality for records.
4-Use a database for data storage instead of plain text files.

# Contributing:
Contributions are welcome! Feel free to fork this repository and submit a pull request.




