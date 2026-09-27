
Student Name: Piyush Dhebe
PRN:125UAD1244
Class/Division: SY-AIDS-C
Course Name: Object Oriented Programming using C++
Unit: I




# C++ OOP Programs – Sensor, Attendance & Product Management

This repository contains three simple **C++ programs** developed to demonstrate important **Object-Oriented Programming (OOP)** concepts using practical real-world examples.

The programs focus on **classes, objects, constructors, encapsulation, vectors, static members, inline functions, and destructors**.

---

## 📂 Programs Included

### 1. Soil Sensor Monitoring System

**File:** code.cpp

This program simulates a basic soil moisture monitoring system using multiple soil sensors.

### Features

* Creates multiple soil sensor objects.
* Stores:

  * Sensor ID
  * Moisture level
  * Timestamp
* Uses a `vector` to store multiple sensors.
* Displays morning sensor readings.
* Updates the moisture reading and timestamp of a sensor.
* Displays the updated reading.

### OOP Concepts Used

* Class and Objects
* Constructor
* Constructor Initializer List
* Encapsulation
* `vector`
* Range-based `for` loop
* `const` member function
* Member functions

### Sample Output

```text
== Morning Sensor Readings==
Sensor:S001|Moisture:45.2%|Time:08:00
Sensor:S002|Moisture:52.8%|Time:08:00
Sensor:S003|Moisture:38.5%|Time:08:00

=== Updated Readings===
Sensor:S001|Moisture:47.5%|Time:09:00
```

---

# 2. Student Attendance Management System

**File:** code.cpp

This program manages attendance records for multiple students and calculates their attendance percentage.

### Features

* Creates student objects with:

  * Roll number
  * Name
* Records whether a student is present or absent.
* Keeps track of total attendance days.
* Keeps track of present days.
* Calculates attendance percentage.
* Displays an attendance report for all students.

### OOP Concepts Used

* Class and Objects
* Constructor
* Constructor Initializer List
* Encapsulation
* Member functions
* `bool` parameter
* `const` member function
* Conditional statements
* Percentage calculation

### Sample Output

```text
===Attendance Report===
Roll:101|Name:Rahul|Attendance:66.6667%
Roll:102|Name:Priya|Attendance:100%
Roll:103|Name:Piyush|Attendance:100%
Roll:104|Name:Omkar|Attendance:33.3333%
```

---

# 3. Product Catalog Management System

**File:** code.cpp

This program manages a simple product catalog containing product information such as product ID, name, price, and stock quantity.

### Features

* Creates multiple product objects.
* Stores:

  * Product ID
  * Product name
  * Price
  * Stock quantity
* Displays product information.
* Maintains the total number of products using a static variable.
* Provides getter functions for product information.
* Allows stock quantity to be updated.

### OOP Concepts Used

* Class and Objects
* Constructor
* Constructor Initializer List
* Static data member
* Static member function
* Inline functions
* Destructor
* Encapsulation
* Getter functions

### Sample Output

```text
===Product Catalog===
ID:1001|Product:LaptopPrice:Rs60000|Stock:15
ID:1002|Product:MousePrice:Rs500|Stock:50
ID:1003|Product:KeyboardPrice:Rs1500|Stock:30

 Total Products in Catalog:3


# 🧠 OOP Concepts Demonstrated

| Concept                | Used In                          |
| ---------------------- | -------------------------------- |
| Class                  | All three programs               |
| Objects                | All three programs               |
| Constructor            | All three programs               |
| Initializer List       | All three programs               |
| Encapsulation          | All three programs               |
| Member Functions       | All three programs               |
| `const` Functions      | Soil Sensor, Attendance, Product |
| Vector                 | Soil Sensor                      |
| Static Data Member     | Product                          |
| Static Member Function | Product                          |
| Inline Functions       | Product                          |
| Destructor             | Product                          |



# 🛠️ Technologies Used

* **Programming Language:** C++
* **Standard Libraries:**

  * `<iostream>`
  * `<string>`
  * `<vector>`
* **Compiler:** Any standard C++ compiler
* **Recommended Standard:** C++11 or later





#  Project Structure


Real-time Applications/
│
├── README.md
│
├── Smart Agriculture Sensor Monitoring
     |--code.cpp
│
├── Student Attendance Management System
        |--code.cpp
│
└── E-commerce Product Catalog
        |--code.cpp




# 🎯 Learning Objectives

These programs were created to understand how C++ OOP concepts can be applied to simple real-world problems.

By working with these programs, you can practice:

* Creating classes and objects
* Using constructors
* Initializing object data
* Creating and using member functions
* Protecting data using class structure
* Working with vectors of objects
* Using static members
* Using inline functions
* Understanding destructors
* Building simple management systems using C++

---

# 👨‍💻 Author

**Piyush Dhebe**

C++ / OOP Practice Projects
