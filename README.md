# Campus Course & Records Manager (CCRM)
The Campus Course & Records Manager (CCRM) is a console-based Java SE application designed to help academic institutes efficiently manage their students, courses, enrollments, and academic records. This project integrates core Java concepts, modern APIs, and object-oriented design principles to deliver a practical and extensible system.
CCRM provides a menu-driven interface where administrators can:
Manage student records (create, update, list, deactivate, and print transcripts).
Manage courses (add, update, assign instructors, search/filter by attributes).
Handle enrollments and grading (enroll/unenroll students, record marks, calculate GPA, and generate transcripts).
Perform file operations (import/export student and course data in CSV-like formats, backup data using Java NIO.2, and recursively calculate storage sizes).
The project not only delivers functional features but also acts as a showcase of Java SE capabilities:
OOP Principles: Encapsulation, Inheritance, Abstraction, and Polymorphism are demonstrated via domain models (e.g., Person → Student/Instructor).
Advanced Java Features: Nested classes, enums, lambdas, functional interfaces, recursion, Streams API, and Java Date/Time API.
Design Patterns: Singleton (for configuration management) and Builder (for complex object creation).
Robustness: Strong exception handling (custom checked and unchecked exceptions), assertions, and validation utilities.
File I/O with NIO.2: File import/export, backup archiving, and recursive utilities using Path and Files APIs.
By combining all these elements, CCRM not only simulates a real-world academic records system but also demonstrates comprehensive Java SE proficiency in a single project. The modular package design (e.g., edu.ccrm.domain, edu.ccrm.service, edu.ccrm.io, edu.ccrm.cli, edu.ccrm.util, edu.ccrm.config) ensures clarity, maintainability, and scalability.
At runtime, the system starts by loading configuration (Singleton AppConfig) and presents a user-friendly console menu for performing all operations. Users can manage data, generate transcripts, back up files, and view reports (e.g., GPA distribution), thereby covering the full cycle of academic record management.
In addition to the source code, the project deliverables include:
A README.md explaining Java fundamentals, installation steps, and mapping syllabus topics to implemented features.
Screenshots demonstrating installation, execution, and outputs.
Sample data files for testing import/export.
An optional demo video showing the application workflow.
Thus, CCRM is both an academic management tool and a learning artifact that consolidates theoretical knowledge with hands-on Java development.

# How to Run
1. Compile: javac -d bin src/edu/ccrm/Main.java src/edu/ccrm/domain/*.java src/edu/ccrm/util/*.java src/edu/ccrm/config/*.java src/edu/ccrm/service/*.java src/edu/ccrm/io/*.java src/edu/ccrm/cli/*.java
2. Run: java -ea -cp bin edu.ccrm.Main

Or use: build.bat

# Features

- Student Management
- Course Management
- Enrollment System
- Grading System
- File Import/Export
- Backup System
