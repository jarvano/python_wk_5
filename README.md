# Python OOP Activities 🐍

This repository contains solutions to two Object-Oriented Programming (OOP) activities written in Python.  
The exercises explore **classes, objects, constructors, encapsulation, inheritance, and polymorphism**.

---

## 📌 Activity 1: Design Your Own Class! 🏗️
**Task:**  
- Create a class representing anything (Smartphone, Book, Car, Superhero, etc.).  
- Add attributes and methods to bring the class to life.  
- Use constructors to initialize each object with unique values.  
- Add an inheritance layer to explore **polymorphism** or **encapsulation**.

**Example Implemented:**  
- `Device` → Base class  
- `Smartphone` & `Tablet` → Child classes (inheritance)  
- Demonstrated:
  - Constructor `__init__`  
  - Encapsulation (`__battery`)  
  - Polymorphism (redefined `device_info`)  

---

## 📌 Activity 2: Polymorphism Challenge! 🎭
**Task:**  
- Create classes (animals or vehicles) that share the same action method (e.g., `move()`).
- Each class should define the action differently.

**Example Implemented:**  
- `Car.move()` → `"🚗 Driving on the road..."`  
- `Plane.move()` → `"✈️ Flying in the sky..."`  
- `Boat.move()` → `"⛵ Sailing on the water..."`  
- `Bicycle.move()` → `"🚴 Pedaling on the path..."`  

This shows **polymorphism** in action: same method name, different behavior across classes.

---

## 🛠️ How to Run
1. Clone this repository or copy the code files.  
2. Run the Python scripts in your terminal or IDE:  
   ```bash
   python activity1.py
   python activity2.py
