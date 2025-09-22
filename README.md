# Campus Course & Records Manager (CCRM)

A comprehensive Java console application for managing campus courses, students, enrollments, and grades.

## 📋 Project Overview

CCRM is a console-based Java application that enables educational institutes to manage:
- **Student records** and profiles
- **Course catalog** and scheduling  
- **Student enrollments** with business rules
- **Grade tracking** and GPA calculation
- **Data import/export** via CSV files
- **Automated backups** with timestamping

## 🚀 How to Run

### Prerequisites
- Java SE 17 or higher
- Git (for version control)

### Installation & Execution
```bash
# Clone the repository
git clone https://github.com/your-username/CCRM.git
cd CCRM

# Compile all Java files
javac -d bin src/*.java

# Run the application
java -cp bin Main
```

### 📚 Evolution of Java
-1995: Java 1.0 (Oak) released

-1997: Java 1.1 (JDBC, RMI, Reflection)

-2004: Java 5 (Generics, Autoboxing, Annotations, Enums)

-2014: Java 8 (Lambdas, Stream API, Date/Time API)

-2018: Java 11 (LTS - Local-Variable Syntax, HTTP Client)

-2021: Java 17 (LTS - Sealed Classes, Pattern Matching)

-2023: Java 21 (LTS - Virtual Threads, Record Patterns)


### ⚡ Java Platforms Comparison

<img width="500" height="200" alt="Screenshot 2025-09-22 211757" src="https://github.com/user-attachments/assets/761bb3d6-0e74-48bc-9046-7619861f84f4" />


### 🏗️ Java Architecture
JVM (Java Virtual Machine): Executes Java bytecode, provides platform independence

JRE (Java Runtime Environment): JVM + Libraries = Environment to run Java applications

JDK (Java Development Kit): JRE + Development Tools = Environment to develop Java applications

Relationship: JDK ⊃ JRE ⊃ JVM

## 💻 Windows Installation Guide
Step 1: Download JDK
Visit Oracle JDK Downloads

Download JDK 17+ for Windows x64 Installer

Run the installer and follow setup wizard

Step 2: Set Environment Variables
Open System Properties → Environment Variables

Create new system variable: JAVA_HOME = C:\Program Files\Java\jdk-17

Edit Path variable: Add %JAVA_HOME%\bin

Step 3: Verify Installation
cmd
java -version
javac -version

### 🔧 Eclipse IDE Setup
1. Creating New Project
2. File → New → Java Project
3. Project name: CCRM
4. Use default JRE (Java SE-17)
5. Click Finish

### Importing Source Code
File → Import → General → File System
Select your CCRM project folder
Check all source files and import

### Run Configuration
Run → Run Configurations → Java Application
Main class: Main
Apply and Run

## 📊 Syllabus Topic Mapping
<img width="600" height="300" alt="Screenshot 2025-09-22 221725" src="https://github.com/user-attachments/assets/4fc0303f-0d1f-4d05-ba1a-10b5e3da86e3" />

### 📁 Project Structure
CCRM/\
├── src/                  # Source code\
│   ├── Main.java        # Application entry point\
│   ├── Student.java     # Student domain class\
│   ├── Course.java      # Course domain class\  
│   ├── Enrollment.java  # Enrollment tracking\
│   ├── Grade.java       # Grade enum with points\
│   ├── Semester.java    # Semester enum\
│   ├── DataStore.java   # Singleton data management\
│   ├── FileManager.java # File I/O operations\
│   └── CLI.java         # Command-line interface\
├── data/                # CSV data files\
│   ├── students.csv     # Student records\
│   ├── courses.csv      # Course catalog\
│   └── enrollments.csv  # Enrollment data\
├── README.md           # Project documentation\
└── .gitignore          # Git exclusion rules\

### 👤 Author
AFRAH KHAN

Student ID: 24MIP10035

Course: PROGRAMMING IN JAVA

### 📄 Academic Integrity
This project was developed as part of academic coursework. All code is original work developed for educational purposes.
