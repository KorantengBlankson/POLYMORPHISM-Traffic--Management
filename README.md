# POLYMORPHISM-Traffic-Management-System
## Overview
This project demonstrates the concept of **Polymorphism** in Object-Oriented Programming (OOP) using Python. It simulates a Smart Traffic Management System where different traffic devices respond to the same activate() command in different ways.

The project shows how a parent class can define a common interface while child classes provide their own implementations of the same method.

## Project Objectives

The system includes:
- A parent class named.
- Child classes
  - TrafficLight
  - SpeedCamera
  - PedestrianSignal
  - EmergencySiren
- Each child class overrides the activate() method to perform its own unique task.
- Objects of all classes are stored in a single list.
- The program activates every device using the same loop without checking the object's type, demonstrating polymorphism.
- The EmergencySiren class is added without modifying the activation loop, illustrating the Open/Closed Principle.

## Project Structure
POLYMORPHISM-Traffic-Management-System/
## How to Run
1. Make sure Python 3 is installed.
2. Clone this repository
3. Navigate into the project
4. Run the program
