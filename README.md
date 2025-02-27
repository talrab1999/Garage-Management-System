# Garage Management System
This project is a Garage Management System designed to manage and schedule garage services, track vehicles, and handle appointments efficiently.
The system supports multiple vehicle types, including cars, trucks, motorcycles, and electric vehicles. 
It also offers a user interface for managing and interacting with the garage.

## Project Overview
The Garage Management System allows the garage to manage different types of vehicles and their services. It includes features such as:

Vehicle tracking (Car, Motorcycle, Truck, Electric Vehicle)

Managing vehicle owner details

Calculating energy consumption for electric vehicles

Handling different service types (e.g., repair, maintenance)

The system is built using C# and follows an object-oriented design.

# Project Structure
The project is organized into two main directories:

ConsoleUI:
Contains the user interface components that interact with the user through the console.

Program.cs: Entry point of the application, which initializes and runs the system.

UIConsole.cs: Handles the display of information and interaction with the user in the console.

UIManager.cs: Manages user inputs and updates the UI.

app.config: Configuration settings for the application.

GarageLogic:
Contains the core logic and data structures related to the garage and vehicles.

Car.cs: Represents a car with its specific properties and methods.

ElectricVehicle.cs: Represents an electric vehicle with properties like battery and energy.

Energy.cs: Defines the energy properties and consumption for electric vehicles.

GarageManager.cs: Manages the overall garage services, including vehicle tracking and service scheduling.

GasVehicle.cs: Represents a gas-powered vehicle with properties such as fuel and gas consumption.

Motorcycle.cs: Represents a motorcycle with its specific properties.

OwnerDetails.cs: Contains details of vehicle owners.

Truck.cs: Represents a truck with specific attributes and behaviors.

ValueOutOfRangeException.cs: Custom exception for handling out-of-range values in the system.

Vehicle.cs: Base class representing a general vehicle with common properties.

VehicleFactory.cs: Factory class for creating vehicle objects based on the type.

Wheel.cs: Represents the wheels of vehicles and their properties.

# Technologies Used
C#: The main programming language used for building the application.

.NET Framework: Used for project setup and management.

Object-Oriented Programming: The design pattern followed for structuring the system.
