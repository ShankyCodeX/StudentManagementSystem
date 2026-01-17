# Student Management System

A robust, console-based Java application designed to perform CRUD (Create, Read, Update, Delete) operations on student records. This project demonstrates an understanding of Object-Oriented Programming (OOP) principles, the Java Collection Framework, and package-based project architecture.

## 🚀 Features

- **Add Student**: Capture and store student details including ID, Name, Age, and Course.
- **View Records**: Display all registered students in a formatted table.
- **Search**: Find specific student details instantly using their unique ID.
- **Update**: Modify existing student information (Name, Age, or Course) dynamically.
- **Delete**: Remove student records from the system based on their ID.

## 🛠️ Project Structure

The project is organized into clean packages to ensure separation of concerns:

- **main**: Contains the Main.java file which acts as the entry point and handles the user menu.
- **model**: Contains the Student.java class, defining the data structure for a student.
- **service**: Contains StudentService.java, which houses the core business logic and data management using ArrayList.

## 💻 Technologies Used

- **Java**: Core programming language.
- **Java Collections**: Used ArrayList for dynamic data storage.
- **Java Scanner**: For handling user-driven console input.

## 📖 How to Run

Clone the repository:

```bash
git clone https://github.com/your-username/StudentManagementSystem.git
```

Navigate to the project directory:

```bash
cd StudentManagementSystem
```

Compile the source code:

```bash
javac -d bin src/model/*.java src/service/*.java src/main/*.java
```

Run the application:

```bash
java -cp bin main.Main
```

## Author

- **Current Status**: 6th Semester Computer Science Student.
