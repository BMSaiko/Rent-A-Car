# Rent-A-Car 🚗

A comprehensive Java-based car rental management system developed as an academic project for the Programming II course at Instituto Superior de Engenharia do Porto (ISEP).

## 📖 Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies](#technologies)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Class Diagram](#class-diagram)
- [Contributors](#contributors)
- [License](#license)

## 🎯 Overview

Rent-A-Car is a console-based application designed to manage car rental operations. The system allows users to handle vehicle inventory, customer registrations, rental transactions, and generate various reports and statistics. Built with object-oriented principles in Java, it demonstrates clean code architecture and comprehensive data management capabilities.

## ✨ Features

### 🔧 Core Functionality
- **Vehicle Management**: Add, remove, and manage car inventory
- **Customer Management**: Register and maintain customer records
- **Rental Operations**: Process car rentals and returns
- **Price Management**: Dynamic pricing based on vehicle type and rental duration
- **Data Persistence**: Save and load system data from files

### 📊 Reporting & Analytics
- List all vehicles in the system
- Display rental history per vehicle
- Calculate total revenue
- Generate customer statistics
- Vehicle utilization reports

### 🛡️ Validation & Error Handling
- Comprehensive input validation
- Date validation and conflict checking
- Duplicate entry prevention
- Graceful error handling

## 🛠️ Technologies

- **Java 8+** - Core programming language
- **Object-Oriented Programming** - Inheritance, polymorphism, encapsulation
- **File I/O** - Data persistence without database
- **Collections Framework** - Efficient data management
- **Date & Time API** - Rental period calculations

## 📥 Installation

### Prerequisites
- Java JDK 8 or higher
- Git (optional)

### Steps
1. Clone the repository:
```bash
git clone https://github.com/BMSaiko/Rent-A-Car.git
cd Rent-A-Car

Compile the Java files:

bash
javac -d bin src/**/*.java
Run the application:

bash
java -cp bin Main
🚀 Usage
Main Menu Options
Add Vehicle - Register new cars to the fleet

Remove Vehicle - Remove vehicles from inventory

Rent Vehicle - Process rental transactions

Return Vehicle - Handle vehicle returns

List All Vehicles - Display complete inventory

List Rented Vehicles - Show currently rented cars

List Available Vehicles - Display available cars for rent

Save Data - Persist data to files

Load Data - Restore data from files

Exit - Close the application

Vehicle Types
Economy Cars

Standard Cars

Luxury Vehicles

SUVs

Vans