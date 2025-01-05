# Car Rental System

## Project Overview
This is a **Computer Organization & Assembly Language Lab Project** that simulates a car rental system. The program allows users to rent luxury cars, view rental records, delete records, and exit the system. Each car has an associated hourly rental rate, and the program maintains a record of transactions.

## Features
- **Main Menu**: Provides options to:
  - Rent a car
  - View rental records
  - Delete records
  - Exit the program

- **Car Options**:
  - Ferrari: $[rate]/hour
  - BMW: $[rate]/hour
  - Mercedes: $[rate]/hour

- **Rental Records**:
  - Displays total cars rented
  - Count of Ferraris, BMWs, and Mercedes rented
  - Total earnings

- **Limitations**:
  - A maximum of 3 rentals per car type (Ferrari, BMW, Mercedes)
  - A total rental cap of 9 cars across all types

## Output Demonstration
1. **Main Menu**:
   - User selects from options: Rent a Car, View Records, Delete Records, or Exit.

2. **Delete Record Without Renting**:
   - If the user attempts to delete a record without renting, the program prompts the user to rent a car first.

3. **Rent a Car**:
   - Displays options for Ferrari, BMW, and Mercedes with hourly rates.
   - Example: Renting a Ferrari for 2 hours calculates and displays the total rental cost.

4. **View Records**:
   - Displays:
     - Total vehicles rented
     - Individual counts for Ferrari, BMW, and Mercedes
     - Total earnings

5. **Delete a Record**:
   - Prompts the user if no car has been rented.
   - Updates the record upon successful deletion of a rented car.

6. **Rental Limits**:
   - Attempts to rent more than the allowed limit prompt appropriate messages.
   - Example: After renting 3 BMWs, additional rental attempts for BMWs are blocked.

7. **Exit**:
   - Exits the program and terminates execution.

## Example Scenarios
- Rent a Ferrari for 2 hours: The program computes and displays the total cost.
- View records after renting a car: Displays the updated record of total rentals and earnings.
- Attempt to delete a BMW record without renting: Prompts that no BMW has been rented.
- Rent all cars (3 Ferraris, 3 BMWs, 3 Mercedes): Program blocks further rentals.

## How to Use
1. Clone the repository to your local machine.
2. Compile and run the program in an appropriate assembly language environment.
3. Use the on-screen menu to interact with the system.

## Learning Outcomes
This project demonstrates fundamental concepts of:
- Assembly language programming
- Menu-driven program design
- Conditional statements and loops
- Record management

## Author
Developed by **Faisal** as part of a lab project for **Computer Organization & Assembly Language** coursework.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.
