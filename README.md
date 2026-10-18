# Hotel Booking Management System - UML Class Diagram

**Institution:** Kigali Independent University (ULK)  
**Instructor:** Eric Maniraguha  

### Group Members:
Hassan Abd Elmohsin Hassan - Roll No : 202510102
---

## 1. Project Overview & Business Idea
This repository contains the UML Class Diagram design for a **Hotel Booking Management System**. The system is designed to help hotels automate room reservations, manage guest profiles, track room availability, and process booking payments efficiently.

## 2. Project Scope
* **In-Scope:** Guest registration, room availability tracking, reservation management (check-in/check-out), and billing/payment tracking.
* **Out-of-Scope:** HR/Staff payroll, restaurant operations, and full software implementation (focus is strictly on UML modelling).

## 3. Main Classes & Relationships
* **Guest:** Represents hotel customers (`1` Guest makes `0..*` Bookings).
* **Room:** Represents hotel rooms (`1` Room is reserved in `0..*` Bookings).
* **Booking:** Manages reservation details and dates (`1` Booking generates `1` Payment).
* **Payment:** Tracks financial transactions for bookings.

## 4. Repository Structure
* `documentation/part_1_project_description.pdf`: Project description, problem statement, scope, and requirements.
* `documentation/report_2_uml_class_diagram.pdf`: Complete UML diagram and detailed explanation of classes and relationships.
* `diagrams/uml_class_diagram.drawio`: Editable source file of the diagram.
* `diagrams/uml_class_diagram.png`: Exported image of the UML Class Diagram.
