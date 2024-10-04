# Blood Donation System

## Project Overview
The **Blood Donation System** is a Java-based console application that simulates a blood bank's operations. The project allows users to interact as different roles, such as an **Admin**, **Donor**, or **Patient**, each having unique functionalities. The Admin can view blood packet availability, Donors can donate blood, and Patients can request compatible blood packets.

---

## Features
- **Admin Access**:
  - Login with an admin password to view current blood packet availability.
  - View blood group levels for **A+, O+, B+, AB+, A-, O-, B-, AB-**.
  
- **Donor Functionality**:
  - Input donor details such as name, sex, and date of birth.
  - Select the blood group and number of packets to donate (1-3).
  - Optionally display the donor information upon successful donation.

- **Patient Functionality**:
  - Input patient details including name and required blood group.
  - Check compatibility and availability of blood groups for the requested type.
  - Deduct blood packets from the inventory once a compatible group is found.

---

## How It Works
1. **Menu Interface**: Users are prompted to choose their role:
   - **Admin** (View blood inventory)
   - **Donor** (Donate blood)
   - **Patient** (Request blood)
   - **Exit** (Quit the application)
   
2. **Admin Operations**:
   - Upon providing the correct password ("catdog"), the admin can view the status of all blood packets available in the bank.

3. **Donor Operations**:
   - The donor provides personal details and selects the blood group they wish to donate to.
   - The system updates the blood inventory accordingly based on the number of packets donated.

4. **Patient Operations**:
   - The patient specifies the blood type they need.
   - The system checks for compatible blood groups and deducts one packet if available.

---

## Technologies Used
- **Java**: Core programming language for building the application logic.
- **Object-Oriented Programming (OOP)**: Use of classes and objects to represent roles (Admin, Donor, Patient) and blood bank operations.

---

## Key Classes and Their Responsibilities
- **BloodBank**: Maintains the blood group inventory and updates it based on donations and requests.
- **Admin**: Handles the login process and displays the current blood inventory.
- **Donor**: Allows for inputting donor information and updating the blood inventory.
- **Patient**: Facilitates input of patient information and checks blood compatibility for requests.
