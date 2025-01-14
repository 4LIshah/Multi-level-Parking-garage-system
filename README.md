# Parking Management System 🚗🅿️

The Parking Management System is a C++ application designed to manage a multi-level parking lot efficiently. It uses data structures like Binary Search Trees (BST) and vectors to allocate, reserve, and free parking spots dynamically. The system tracks active vehicles, calculates fees, and maintains persistent data for seamless functionality.

Features 💡
- Dynamic Spot Allocation: Automatically assigns the nearest available parking spot using a BST.
- Multi-Level Parking Support: Handles multiple levels and spots for diverse parking needs.
- Vehicle Management: Tracks active vehicles and their assigned parking spots.
- Fee Calculation: Calculates and displays parking fees upon freeing a spot.
- Data Persistence: Saves and loads parking data to/from a file for continuity.
- Visual Parking Lot Display: Shows an overview of the parking lot with occupied and free spots.
- Empty All Spots: Frees all occupied spots, calculating total revenue.

Core Functionalities 🛠️
- SpotNode BST: Efficiently manages and retrieves available spots.
- Allocate Spot: Assigns the nearest available spot to a vehicle.
- Free Spot: Releases a reserved spot and calculates the parking fee.
- Display Parking Lot: Shows the current status of the parking lot.
- Display Available Spots: Lists all unoccupied parking spots.
- File Handling: Maintains persistent storage for parking data.

How It Works ⚙️
Initialization:
- Create a parking lot with specified levels and spots per level.
- Populate a BST with all parking spots for efficient management.

Operations:
- Add a vehicle: Assigns the nearest available spot and updates active vehicle data.
- Free a spot: Removes a vehicle, calculates the fee, and marks the spot as available.
- Display parking status: Visualizes the lot as a grid showing occupied and free spots.

Persistence:
- Save parking data to a file before shutdown.
- Load data from the file during initialization for continuity.

Use Cases 🚀
- Ideal for managing small to medium-sized parking facilities.
- Demonstrates the use of advanced data structures in practical scenarios.
- Can be extended for larger parking systems with additional features like user interfaces or database integration.

Tech Stack 🖥️
- Language: C++
- Data Structures: Binary Search Tree, Vectors
- File Handling: Persistent data storage

Setup Instructions 🔧
- Clone the repository:
git clone https://github.com/yourusername/parking-management-system.git

- Compile the code:
g++ -o parkingSystem ParkingSystem.cpp

- Run the program:
./parkingSystem

Future Enhancements 🚧
- Integration with a database for large-scale parking management.
- Implementation of real-time notifications and online booking.
- Adding support for different vehicle types and rates.
