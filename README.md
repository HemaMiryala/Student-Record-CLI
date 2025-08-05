
---

## 📌 What is CRUD?

**CRUD** stands for the 4 main operations you can perform on data:

| Operation | Meaning       | In This App               |
|-----------|---------------|---------------------------|
| Create    | Add new data  | Add a new student         |
| Read      | View data     | View all students         |
| Update    | Modify data   | Edit student info         |
| Delete    | Remove data   | Delete student by ID      |

These are the **fundamentals of any data management system**, and this project helps you practice them with Java.

---

## 💻 What is a CLI Application?

A **Command-Line Interface (CLI)** application:

- Runs in a terminal or console
- Takes input via text (e.g., numbers or words)
- Displays output in the same window

In this app, you type menu options (like `1` to Add Student) and interact with the system purely through the command line — no graphical buttons or windows.

---

## 🧠 Program Logic (How It Works)

### 1. **Student Class**
Defines a student with:
- ID
- Name
- Marks

### 2. **ArrayList for Storage**
- Uses `ArrayList<Student>` to store student records
- Allows dynamic insertion, update, and deletion

### 3. **Menu-Driven Loop**
A `do-while` loop keeps showing the menu until user exits:

```java
do {
 // Show menu
 // Get choice
 // Perform action
} while (choice != 5);
