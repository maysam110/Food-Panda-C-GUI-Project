Here's a README for your project:

---

# Food Panda C++ Console Application

This project is a basic console-based Food Panda simulation built in C++. The application simulates a food ordering platform where users (customers and cooks) can register, login, place orders from various restaurants, calculate bills, and choose delivery options. It is designed to provide users with a simplified experience of ordering food, similar to what is seen in real-world platforms like Food Panda.

## Table of Contents
1. [Introduction](#introduction)
2. [Problem Statement](#problem-statement)
3. [Objectives](#objectives)
4. [Methodology](#methodology)
5. [Results](#results)
6. [Class Diagram](#class-diagram)
7. [Code](#code)
8. [References](#references)

## Introduction
This project simulates the Food Panda application with basic functionality for customers and restaurant owners (cooks). Food Panda is a popular online food ordering platform where customers can choose food from restaurants and have it delivered to their doorstep. The main aim of this project is to provide a console-based food ordering system that facilitates both customers and sellers.

## Problem Statement
As the world becomes busier, people often do not have time to prepare food. Therefore, developing platforms that facilitate online food ordering and provide a source of income for sellers is essential. This project aims to address that problem by creating a platform for food ordering.

## Objectives
- Design a console-based food ordering platform.
- Provide a platform that can be useful during emergencies like lockdowns or isolations.
- Improve problem-solving skills through practical implementation.
- Implement core knowledge into real-world applications.
- Understand teamwork in development scenarios.

## Methodology
This project utilizes core C++ libraries such as:
- **iostream**, **fstream**, **conio.h**, **windows.h** for managing input/output, file handling, and program control.
- **Aggregation** and **Inheritance** techniques have been employed, where classes like `Food` and `Order` are interconnected.

### Key Classes and Functions:
1. **Admin Class**: Manages menu selection and user management (add/remove users).
2. **Login/Register Class**: Allows customers and cooks to register and login.
3. **Customer Class**: Allows customers to register, login, and place orders.
4. **Cook Class**: Manages cook registration and login.
5. **Food Restaurant Class**: Displays various restaurant menus for the user to choose from.
6. **Order Class**: Manages the order process, including food selection, cart management, and bill calculation.
7. **Delivery Class**: Allows the user to choose delivery or pickup options.
8. **Payment Class**: Calculates and displays the bill, allows payment via wallet.
9. **Cart Function**: Displays the orders in the cart and the total bill.
10. **Wallet Function**: Tracks and updates the user’s wallet balance.

## Results
The project functions as expected, providing the following features:
- **User Menu**: Allows customers to register/login and place orders.
- **Restaurant Menu**: Displays various restaurant options and their respective menus.
- **Order Process**: Enables users to place multiple orders, view the cart, and confirm the total bill.
- **Payment System**: Calculates the total bill, deducts the amount from the wallet, and updates the remaining balance.

### Screenshots:
1. **User-Selection Menu**
2. **Restaurant Menu**
3. **Ordering Menu**
4. **Cart & Billing Screen**

## Class Diagram
The class diagram represents the relationships between the key components of the project, including classes such as `Customer`, `Order`, `Food Restaurant`, `Payment`, etc. (You can include the diagram here if you have it in your project files.)

## Code
The code is organized in multiple C++ files, implementing the different features described above. You can view the full code in the repository.

## References
- [Food Panda](https://www.foodpanda.com/) (Inspiration for the project)
- C++ Programming Documentation

---

Feel free to make adjustments if you need to add more details or specific instructions for running your project!
