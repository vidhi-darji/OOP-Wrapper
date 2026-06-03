# 💼 Employee Management System

## 📌 Project Description
The **Employee Management System** is a **Python Object-Oriented Programming (OOP)** based project that allows users to create and manage details of a **Person, Employee, and Manager**. The system provides a **menu-driven interface** where users can create records, display details, and exit the program.

This project demonstrates the concepts of:

✅ Classes and Objects  
✅ Inheritance  
✅ Constructor (`__init__`)  
✅ Method Overriding  
✅ Encapsulation  
✅ Menu-driven Programming

---

## ✨ Features
🔹 Create a Person  
🔹 Create an Employee  
🔹 Create a Manager  
🔹 Display Details of Person, Employee, or Manager  
🔹 Exit the system safely

---

## 🛠️ Technologies Used
🐍 **Python 3**  
💻 **Object-Oriented Programming (OOP)**

---

## 🏗️ Class Structure

### 👤 1. Person Class
The **base class** containing:

📍 Name  
📍 Age

### 🔧 Methods:
- `display_details()` → Displays person information.

---

### 👨‍💼 2. Employee Class
Inherited from the **Person Class**.

Additional attributes:

🆔 Employee ID  
💰 Salary

### 🔧 Methods:
- `display_details()` → Displays employee information.

---

### 👨‍💼🏢 3. Manager Class
Inherited from the **Employee Class**.

Additional attribute:

🏬 Department

### 🔧 Methods:
- `display_details()` → Displays manager information.

---

## 🔄 Project Flow

1️⃣ User selects an operation from the menu.  
2️⃣ User can create:
- 👤 Person
- 👨‍💼 Employee
- 🏢 Manager

3️⃣ User can display stored details.  
4️⃣ User can exit the system.

---

## 📋 Menu Options

```text
1️⃣ Create a Person
2️⃣ Create an Employee
3️⃣ Create a Manager
4️⃣ Show Details
5️⃣ Exit
```

---

## 🖥️ Sample Output

```text
--- Python OOP Project: Employee Management System ---

Choose an operation:
1. Create a Person
2. Create an Employee
3. Create a Manager
4. Show Details
5. Exit

Enter your choice: 1

Enter Name: John Doe
Enter Age: 30

Person created with name: John Doe and age: 30.
```

---

## 🚀 How to Run the Project

### 📍 Step 1:
Install **Python** on your computer.

### 📍 Step 2:
Save the project file as:

```text
employee_management_system.py
```

### 📍 Step 3:
Open **Terminal / Command Prompt**

### 📍 Step 4:
Run the program:

```bash
python employee_management_system.py
```

---

## 🎯 Learning Outcome
By completing this project, you will learn:

📚 Python OOP Concepts  
📚 Inheritance  
📚 Method Overriding  
📚 Menu-driven Programming  
📚 User Input Handling

---

## 👩‍💻 Author
**Vidhi Darji**

🌟 *Thank you for checking out this project!*
