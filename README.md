# 📝 Task 6 – Java GUI To-Do List Application

## 📌 Objective
Build a **desktop-based To-Do List application** using **Java Swing** to manage tasks interactively.  
This project is part of the **Java Developer Internship – Task 6** and focuses on GUI development and event handling.

---

## 🛠 Tools & Technologies
- **Java** (JDK 8+)
- **Swing** (Built-in Java GUI toolkit)
- **AWT** (Layout managers, event handling)
- **IDE**: IntelliJ IDEA CE / Eclipse (any Java IDE can be used)

---

## 📖 Features
- ➕ **Add Tasks** – Enter a task and click *Add Task* to save it to the list.
- 🗑 **Delete Tasks** – Select a task and click *Delete Task* to remove it.
- 📜 **Scrollable List** – View all tasks in a scrollable list.
- ⚠ **Exception Handling** – User-friendly error messages for:
  - Empty input when adding a task.
  - No selection when deleting a task.
  - Any unexpected runtime errors.

---

## 💻 How It Works
1. **User Interface**
   - The main window (`JFrame`) displays:
     - A **task list** (`JList`) to show all tasks.
     - A **text field** (`JTextField`) for typing new tasks.
     - **Add** and **Delete** buttons for task management.

2. **Event Handling**
   - **Add Button** – Validates input before adding a task.
   - **Delete Button** – Checks if a task is selected before removing it.
   - Both actions are handled with **try-catch** blocks for safe execution.

3. **Layout**
   - `BorderLayout` used for main frame:
     - **CENTER** – Scrollable task list.
     - **SOUTH** – Input field and buttons panel.

