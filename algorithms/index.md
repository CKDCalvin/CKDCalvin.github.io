---
title: Calvin Kugonza
---

# Algorithms and Data Structures Enhancement

## Overview

The artifact used for this enhancement is the IT 145 Pet Boarding System. The original version relied on basic object-oriented structures and did not include advanced algorithms for managing and retrieving data efficiently.

This enhancement focused on improving the system by implementing algorithms for searching, sorting, and dynamically assigning boarding suites based on availability.

---

## Justification for Inclusion

This artifact provided an opportunity to enhance the system’s functionality through algorithmic improvements. By introducing efficient data handling and logic, I transformed the system from a basic data manager into a more intelligent and responsive application.

Key components that showcase my skills include:
- Implementation of search functionality for reservations
- Development of sorting algorithms for organizing reservation data
- Creation of a suite assignment algorithm to manage boarding capacity
- Efficient handling of data using arrays and objects

These enhancements demonstrate my ability to apply algorithmic principles to solve real-world problems.

---

## Enhancements Made

The following algorithmic improvements were implemented:

- **Suite Assignment Algorithm:** Automatically assigns an available suite based on pet type (dog or cat)
- **Search Functionality:** Allows users and administrators to search for reservations by ID or pet name
- **Sorting Functionality:** Enables sorting of reservations by pet name, pet type, or check-out date

Example logic used for suite assignment:
<code>
function assignPetSuite(petType):
if petType == "Dog":
for each suite in dogSuites:
if suite is available:
return suite
if petType == "Cat":
for each suite in catSuites:
if suite is available:
return suite
return "No space available"
</code>


---

## Course Outcomes Achieved

This enhancement aligns with the following course outcomes:

- **Outcome 3 (Algorithms and Data Structures):** Demonstrates the design and implementation of algorithms to solve system-level problems.
- **Outcome 4 (Software Engineering):** Shows the integration of algorithmic logic into a functional application.

---

## Reflection

This enhancement allowed me to understand how algorithms directly impact system performance and usability. Implementing search and sorting functionality improved the efficiency of retrieving data, while the suite assignment algorithm introduced dynamic decision-making into the system.

One challenge I faced was ensuring that the assignment algorithm correctly handled edge cases, such as when no suites were available. Addressing these scenarios required careful logic design and testing.

Another challenge involved integrating algorithmic logic with the database and frontend. Ensuring that sorted and filtered data displayed correctly in the user interface required debugging and refinement.

Through this process, I gained valuable experience in applying data structures and algorithms in a practical context, strengthening my ability to design efficient and scalable solutions.

