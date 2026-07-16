🏨 Hotel Management System

A simple Console-Based Hotel Management Application built using Core Java. The system allows hotel staff to manage room check-ins, check-outs, and view occupancy status through an interactive menu in the terminal.


📌 Features

✅ Check-In


Enter room number to assign a guest
Validates room availability before check-in
Stores guest name against the room


🚪 Check-Out


Enter room number to release a guest
Displays guest name and room number on successful checkout
Marks the room as Empty after checkout


📊 View Occupancy


Displays a Room vs Guest table for all 10 rooms
Instantly reflects the latest check-in / check-out updates


🔄 Interactive Menu


Loop-based menu that runs until the user selects Exit
Handles invalid room numbers and invalid menu choices



🛠️ Technology Stack

TechnologyUsageJavaCore programming languageScanner (java.util)User input from console2D ArraysIn-memory room data storageSwitch-CaseMenu-driven control flow


📂 Project Structure

HotelManagementSystem/
└── Main.java
    ├── main()              # Initializes rooms and runs menu loop
    ├── checkIn()           # Guest check-in logic
    ├── checkOut()          # Guest check-out logic
    └── viewOccupancy()     # Prints room occupancy table


⚙️ Prerequisites


Java JDK 8+
Any terminal / command prompt
Java online compiler


▶️ Running the Application

Compile

bashjavac Main.java

Run

bashjava Main

Run Online

Paste the code into any online Java compiler:


OnlineGDB
JDoodle



🖥️ Menu

Welcome to the Hotel Management System

1. Check-In
2. Check-Out
3. View Occupancy
4. Exit

Enter your choice:


📋 Sample Output

Check-In

Enter room number: 3
Enter guest name: Rahul

Check-in successful.

Check-Out

Enter room number: 3

Guest Rahul has checked out of room 3.

View Occupancy

Room    Guest
1       Empty
2       Sneha
3       Empty
4       Arjun
5       Empty


🔐 Validations

ScenarioResponseRoom already occupied"Sorry, this room is already occupied."Room already vacant"Sorry, this room is already vacant."Invalid room number"Invalid room number. Please try again."Invalid menu choice"Invalid choice. Please try again."


🚀 Future Enhancements


 Add room types (Single / Double / Suite)
 File-based data persistence
 Billing and invoice on checkout
 OOP design with Room and Guest classes



👩‍💻 Developer

Your Name
B.Tech Graduate | Java Developer


📜 License

This project is developed for educational and portfolio purposes.
