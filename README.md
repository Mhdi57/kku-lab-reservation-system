# KKU Lab Reservation System

A console-based lab reservation management system developed in Java. The project manages laboratory rooms, users, and hourly reservations while demonstrating object-oriented design, collection handling, date and time validation, and file-based data persistence.

## Features

- Create and manage users
- Reserve a lab room for a specific date and hour
- Prevent conflicting reservations for the same room and time
- Remove reservations and users
- Search reservations by user
- Display all users and reservations
- Save and load application data using Java object serialization
- Export reservation records to a text file

## Core Concepts

- Object-oriented programming and inheritance
- Interfaces and abstraction
- Java collections
- File I/O and object serialization
- Date and time handling with `java.time`
- Command-line interface design

## Requirements

- Java Development Kit (JDK) 8 or later

## Build

From the repository root, compile the source files into an output directory:

```bash
javac -d out Assi2/src/sem451/*.java
```

## Run

```bash
java -cp out sem451.KkuSystem
```

## Project Structure

```text
Assi2/
├── src/sem451/       # Java source files
└── printedData.txt   # Exported reservation records
```

The main entry point is `KkuSystem.java`. Supporting classes model users, students, rooms, lab rooms, reservation blocks, dates, and times.

## Notes

This project was created as an academic Java assignment focused on applying object-oriented programming to a practical reservation-management scenario.
