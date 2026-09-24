# Metro Management System

A console-based metro ticketing and management system written in C++. It uses a linked list to store stations, classes for cards and admins, and text files to save data between runs.

## Features

**Customer menu**
- Book a ticket (pay by cash or metro card)
- View the metro map (all stations)
- Check the route between two stations
- Check metro card balance
- Register a new card and recharge it
- View your tickets

**Admin menu**
- View, add and delete stations
- Change the fare price
- Delete a metro card and view all cards
- Change password and add new admin users

Fare = number of stations travelled x fare per station (default 10, changeable by an admin).

## Tech
C++ (OOP, linked lists, file handling)

## How to run
This project uses Windows-only headers (`windows.h`, `conio.h`) and `system("cls")`, so it builds on Windows.

```
g++ metro_management.cpp -o metro_management
metro_management.exe
```

Keep `admins.txt`, `stations.txt`, `creditCards.txt` and `ticket.txt` in the same folder as the program.

## Demo data
- Default admin login: `admin` / `admin` (for demo only)
- `creditCards.txt` and `ticket.txt` contain sample entries with public test card numbers and dummy phone numbers. Do not put real card or phone details in this repository.

## Project files
- `metro_management.cpp` : source code
- `stations.txt`, `admins.txt`, `creditCards.txt`, `ticket.txt` : data files
- `docs/Final_Report.pdf` : project report
