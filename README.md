# Pet_Adoption_System-Admin-
A Java Swing-based application for managing pet adoption records, inventory, and user views for the Home2Heart Pet System.
1. Project Overview

This desktop application is developed in Java (JDK 17+) using the Swing GUI framework.
Its purpose is to provide a structured and efficient management tool for a pet shelter—allowing the team to maintain pet information, track adoptions, and handle shelter operations smoothly.
The project follows a clean architectural structure with separate Model, UI (View), and Utility packages to maintain readability and scalability.

2. Features
✅ View Pet Catalog

Displays all available pets using the Viewpet UI component.

🐾 Pet Data Modeling

Implements full Object-Oriented Programming using separate model classes:
Dog, Cat, Rabbit, Bird, etc., located in the petsystem.model package.

💾 Data Persistence (JSON)

Pet and adoption data is stored in:

pets_data.json

adoption_records.json

Uses Gson for JSON serialization/deserialization.

📦 Core Modules

Add Pets

View Pets

Adopt Pets

View Adoption Records

Testimonials

Data Utilities

3. Technologies & Dependencies
Component	Detail
Language	Java (JDK 17+)
GUI Framework	Java Swing (javax.swing.*)
Data Handling	Google Gson 2.10.1+ (required)
File Storage	JSON files inside /petsystem/data

4. Project Structure
/PetPalace
├── /src
│   └── /petsystem
│       ├── /data
│       │   ├── adoption.txt
│       │   └── pet.txt
│       ├── /model
│       │   ├── Pet.java
│       │   ├── Dog.java
│       │   ├── Bird.java
│       │   ├── Cat.java
│       │   └── Rabbit.java
│       ├── /ui
│       │   ├── Viewpet.java      # Main Pet Catalog GUI
│       │   ├── Addpet.java
│       │   └── (other UI files)
│       └── /util
│           └── (utility classes)
├── PetPalace.iml
└── README.md
