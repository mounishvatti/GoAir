# Airline Reservation System using C++

## Overview

This C++ program implements a simple Airline Reservation System. Users can input customer details, choose a destination, book a flight, and generate a ticket with associated charges. The program is menu-driven and allows users to navigate through different functionalities.

## Files

1. **AirlineReservationSystem.cpp**: Main C++ program containing the implementation of the Airline Reservation System.

2. **records.txt**: Text file used to store customer ticket details.

## Classes

### 1. Management

- The `Management` class initiates the main menu of the Airline Reservation System.

### 2. Details

- The `Details` class manages customer details, such as name, gender, phone number, age, address, and customer ID.

### 3. Registration

- The `Registration` class handles flight registration, including the selection of destinations, specific flights, and associated charges.

### 4. Ticket

- The `Ticket` class extends the `Registration` and `Details` classes to generate and display customer tickets.

## Functions

### 1. mainMenu()

- Displays the main menu with options to add customer details, book a flight, generate a ticket, or exit the program.

### 2. information()

- Collects and stores customer details.

### 3. flights()

- Displays available flights for different destinations and allows users to select a flight.

### 4. Bill()

- Generates a customer ticket with destination and flight details, including charges.

### 5. dispBill()

- Displays the generated ticket.

## Instructions

1. Compile and run the program using a C++ compiler.

```bash
g++ AirlineReservationSystem.cpp -o AirlineReservationSystem
./AirlineReservationSystem
```

2. Follow the on-screen instructions to navigate through the Airline Reservation System.

3. After completing the booking process, the generated ticket will be stored in the `records.txt` file.

4. Users can view their ticket by selecting the appropriate option in the main menu.

## Note

- This is a basic implementation and may require enhancements for a real-world scenario.
- Additional error handling and input validation can be added for improved robustness.

Feel free to customize and extend the code according to your requirements.
