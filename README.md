Ramone's House of Body Art - Order Entry System
Description
This is a Python GUI application built using the Tkinter library. It serves as an order entry system for an auto body shop. The program allows the user to input customer information, select a car type, choose various customization options (like custom paint, tires, audio), and select a payment method. When an order is submitted, the program validates the input and saves the order details, along with a timestamp, to a text file named "orders.txt".

Requirements
1. Python 3.x
2. A specific image file named "heading.png" must be present in the same directory as the script for the application to launch.

How to Run:
- Ensure "heading.png" is in your project folder.
- Run the script using Python: python ramones_body_art.py

Features:
- User Interface: Uses buttons, checkboxes, radio buttons, and dropdown menus for easy data entry.
- Input Validation: prevents the user from submitting a form without a Name or Payment Type.
- Data Logging: Appends all valid orders to "orders.txt" so no previous data is lost.
- Reset Function: Includes a "Clear" button to reset the form for the next customer.

Output Example (orders.txt)
Customer Name: John Doe Car Type: Race Car Customization Choices: - Custom Paint Job - Performance Tires Card: Visa Order Placed At: 12/08/2025 02:30 PM
