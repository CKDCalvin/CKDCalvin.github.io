# Databases Enhancement

## Overview

The artifact selected for this enhancement is the IT 145 Pet Boarding System. The original version of the system did not include a database, causing temporary storage. This meant that reservations could not be permanently stored, updated, or deleted.

This enhancement focused on integrating a database and implementing full CRUD functionality to support data storage and management.

---

## Justification for Inclusion

This artifact was selected because it allowed me to demonstrate my ability to design and implement database-driven applications. By integrating MongoDB and connecting it to the backend and frontend, I transformed the system into a fully functional data-driven application.

Key components that showcase my skills include:
- Integration of MongoDB for persistent data storage
- Implementation of CRUD operations for reservations
- Creation of backend models and schemas using Mongoose
- Development of API routes for database interaction
- Synchronization of frontend and backend data

These improvements demonstrate my ability to design and implement database solutions within a full-stack application.

---

## Enhancements Made

The following database enhancements were implemented:

- **Create:** Users can create new reservations stored in MongoDB
- **Read:** Users and administrators can retrieve reservation data
- **Update:** Administrators can edit reservation details
- **Delete:** Administrators can remove reservations

Additional improvements include:
- Data validation for required fields
- Structured schema design using Mongoose
- Integration between frontend forms and backend database operations

---

## Course Outcomes Achieved

This enhancement aligns with the following course outcomes:

- **Outcome 4 (Software Engineering):** Demonstrates full-stack system integration
- **Outcome 5 (Security):** Shows awareness of data validation and controlled data handling practices

---

## Reflection

Enhancing this artifact with database functionality significantly improved its practicality and realism. One of the most important lessons I learned was how to design a system that maintains data consistency across multiple layers of an application.

A key challenge I encountered was ensuring that updates made to reservations were correctly reflected on the frontend. Although the database was updating successfully, the frontend initially displayed outdated data. I resolved this by refetching data after updates and ensuring proper state management.

Another challenge involved handling date values, where differences in formatting caused incorrect display on the frontend. I addressed this by standardizing date formatting before rendering them.

Through this enhancement, I gained a deeper understanding of database integration, API communication, and full CRUD implementation. This experience strengthened my ability to build reliable, data-driven applications and reinforced the importance of maintaining data integrity and consistency.
