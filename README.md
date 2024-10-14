# Hospital_Management_System

## Project Overview

This Hospital Management System is designed to manage the core functions of a hospital efficiently. The system helps to maintain and manage patient information, room allocation, discharge processes, billing, and more. The project is developed using Java, and it follows a modular structure for easy scalability.

## Features

- **Patient Management:** Manage patient details including registration, admission, and discharge.
- **Room Management:** Handle room allocation, tracking of available rooms, and room charges.
- **Doctor Management:** Manage doctor profiles, their assigned patients, and availability.
- **Billing System:** Generate and manage hospital bills for patients, including room charges, service fees, and additional charges.
- **Admin Panel:** Accessible for hospital administration to manage all aspects of the hospital efficiently.

## File Structure

- **dist/**: Contains distribution files for the project.
- **nbproject/**: Contains NetBeans project files.
- **src/**: Source code for the application, including all the Java files.
- **store/**: External resources or dependencies used by the project.
- **hp_mgmt_db.sql**: SQL script for setting up the database required by the Hospital Management System.
- **build.xml**: Apache Ant build script for compiling and packaging the application.
- **manifest.mf**: Manifest file for packaging the Java application.

### Important Java Files:
- `Patient.java`: Manages the patient details and interactions.
- `Doctor.java`: Manages the doctor profiles and availability.
- `Room.java`: Handles room allocation and management.
- `Billing.java`: Manages the billing system for patients.
- `Registration.java`: Handles new patient registration processes.
- `.form files`: GUI forms for the respective `.java` files to handle user interaction.

## Installation & Setup

1. **Clone the Repository:**
   ```bash
   git clone <repository-url>
   cd hospital-management-system
   ```

2. **Database Setup:**
   - Import the `hp_mgmt_db.sql` file into your database (e.g., MySQL).
   - Configure the database connection in the project.

3. **Build and Run:**
   - Open the project in NetBeans.
   - Run the project on GlassFish Server or any compatible server.

## Requirements

- Java Development Kit (JDK) 8 or higher
- Apache NetBeans IDE
- MySQL Database (or equivalent for SQL)
- GlassFish Server for deployment

## How to Use

1. **Login**: The system provides access to administrators, doctors, and staff. Once logged in, users can navigate to different modules.
2. **Patient Management**: Add, update, or discharge patient information.
3. **Room Allocation**: Allocate or release rooms based on availability.
4. **Billing**: Generate bills for discharged patients, including all relevant charges.

---

This `README.md` file provides a high-level overview of your project, explaining the structure, installation steps, and key features. You can expand on each section as needed!
