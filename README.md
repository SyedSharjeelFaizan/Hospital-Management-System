# Hospital Management System (Core Java & OOP)

A console-based Hospital Management System developed in Java demonstrating Object-Oriented Programming (OOP) concepts including Abstraction, Inheritance, Polymorphism, and Encapsulation.

---

## 🌟 Key Features

* **Patient Management:** Register patients with unique auto-generated IDs, age, and gender tracking.
* **Doctor Management:** Add medical specialists with departmental categorization.
* **Appointment Scheduling:** Link patients and doctors dynamically with date validation.
* **Records Viewing:** Formatted viewing of all active patients, doctors, and scheduled appointments.
* **Interactive CLI Interface:** Clean, menu-driven command-line workflow.

---

## 🏗️ Object-Oriented Design (OOP Highlights)

* **Abstraction (`Person` class):** Abstract base class defining common person attributes (`id`, `name`) and abstract method `getRole()`.
* **Inheritance (`Patient` & `Doctor` extends `Person`):** Derived classes inheriting identity attributes while encapsulating specialized fields (`specialty`, `age`, `gender`).
* **Polymorphism:** Method overriding of `getRole()` and `toString()` providing custom implementations for each entity type.
* **Encapsulation:** Private data members with controlled access via constructors, getters, and setters.

---

## 🚀 How to Run

### Prerequisites
* Java Development Kit (JDK 8 or higher)

### Compilation & Execution
1. Open terminal in the project directory:
   ```bash
   javac HospitalManagement.java
   ```
2. Run the application:
   ```bash
   java HospitalManagement
   ```

---

## 👤 Author
* **Syed Sharjeel Faizan**
* GitHub: [@SyedSharjeelFaizan](https://github.com/SyedSharjeelFaizan)
