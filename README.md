# Task Manager — Java Application

This project implements a desktop Task Manager application in Java. It was developed to demonstrate sound software engineering practices, object-oriented design, and application-level data management. The repository contains source code that implements core task lifecycle operations and a simple user-facing interface intended for academic demonstration and portfolio presentation.

---

## Project overview

The Task Manager application models the common operations of a to-do/task management system, including creation, editing, organization, and removal of tasks. The project emphasizes:

- Object-oriented program structure and modular design
- Clear separation of concerns between application logic and user interaction
- Practical use of Java language features and standard libraries
- Ability to run and evaluate a complete Java application from source

This project is suitable for illustrating engineering depth on a Master’s application, especially for programs that value systems development, software engineering, or application-centric projects.

---

## Features

- Create, view, update, and delete tasks
- Basic user management and session entry point
- A main driver class to launch the application and orchestrate program flow
- Simple textual or GUI-based dashboard (as implemented in source)
- Compact, easy-to-follow codebase for teaching and demonstration

---

## Technical design

### Language and runtime
- Implemented in Java; compatible with Java SE (8+ recommended).

### Code organization
- Core application classes:
  - `MainProgram.java` — primary entry point
  - `MainClass.java` — application bootstrap and initialization
  - `TaskManager.java` — core task operations and business logic
  - `UserManagementApp.java` — user/session handling utilities
  - `Dashboard.java` — user-facing dashboard or controller view
- The code is organized to make it straightforward to extend the UI, plug in persistence, or add networking.

### Persistence and extension points
- The current repository focuses on in-memory task management logic.
- The architecture is intentionally modular to allow straightforward addition of:
  - Local persistence (file, SQLite, H2)
  - A GUI framework (Swing/JavaFX) or web front-end
  - Authentication and multi-user support
  - Background scheduling or notification services

---

## How to run

Requirements:
- Java Development Kit (JDK) 8 or later
- (Optional) An IDE such as IntelliJ IDEA or Eclipse for easier navigation

Steps:
1. Clone the repository:
   ```bash
   git clone https://github.com/ViKarthick/TaskManagerApplication.git
   cd TaskManagerApplication
