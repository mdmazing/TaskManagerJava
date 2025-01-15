# Task Manager Project

## Overview
This is a simple **command-line task manager application** built using **Java** and **SQLite**. It allows users to add, view, complete, and delete tasks from a persistent SQLite database.

## Features
1. **Add Task**: Add a new task to the database.
2. **View Tasks**: Display all tasks along with their status.
3. **Complete Task**: Mark a specific task as completed.
4. **Delete Task**: Remove a task from the database.
5. **Persistent Storage**: Tasks are stored in an SQLite database for persistence.

## Technologies Used
- **Java** for the application logic.
- **SQLite** for persistent data storage.
- **JDBC** for database connectivity.

## How to Run the Project

### Prerequisites
1. **Java Development Kit (JDK)** installed (version 11 or higher).
2. **SQLite JDBC Driver**.

### Steps
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project directory.
3. Compile the Java code:
   ```bash
   javac TaskManager.java
   ```
4. Run the program:
   ```bash
   java TaskManager
   ```

## How to Use
1. **Start the application** by running the compiled Java program.
2. **Choose an option** from the menu by entering the corresponding number:
   - `1`: Add a task.
   - `2`: View all tasks.
   - `3`: Complete a task by entering its ID.
   - `4`: Delete a task by entering its ID.
   - `5`: Exit the application.
3. Follow the prompts to interact with the application.

## Example Interaction
```
Task Manager
1. Add Task
2. View Tasks
3. Complete Task
4. Delete Task
5. Exit
Choose an option: 1
Enter task name: Finish Java project
Task added successfully.

Task Manager
1. Add Task
2. View Tasks
3. Complete Task
4. Delete Task
5. Exit
Choose an option: 2
Tasks:
1. Finish Java project - Pending
```

## Future Enhancements
This project can be enhanced further by:
1. **Adding a Graphical User Interface (GUI)** using JavaFX or Swing.
2. **Implementing input validation** for more robust error handling.
3. **Exporting tasks to a file** (e.g., CSV or JSON).
4. **Unit tests** to ensure code reliability.

## Contact
For any questions or suggestions, feel free to reach out to:
**Jetmir Bediu (jetmir.bediu@hotmail.com)**

---
Thank you for checking out this project! I look forward to any feedback or questions.

