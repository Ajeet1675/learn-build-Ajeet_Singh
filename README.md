# Ajeet – Slot Management Module

## Overview

This repository contains my individual contribution to the Doctor Appointment System.
I worked on the **Slot Management Module**, which enables doctors to create and manage their available appointment slots.

---

## My Work

* Designed and implemented APIs for slot management
* Developed logic for creating, fetching, and booking slots
* Ensured slots are marked unavailable once booked
* Implemented validation to prevent incorrect or duplicate slot creation
* Structured the module using Controller → Service → Repository architecture

---

## Key Functionalities

### Create Slot

Allows a doctor to create available time slots.

### View Slots

Fetch all available slots or filter by doctor.

### Book Slot

Updates slot status to prevent double booking.

---

## Technical Approach

* Used **Spring Boot** for backend development
* Applied **Spring Data JPA** for database operations
* Followed **layered architecture** for clean separation of concerns
* Integrated with existing **JWT-based security** for authenticated access

---

## Flow

Doctor → Create Slot → Service Logic → Database
Patient → View Slot → Book Slot → Update Status

---

## Learnings

* Understanding real-world scheduling logic
* Handling state changes (available → booked)
* Designing scalable backend modules
* Working with structured API development

---

## Note

Required common components like security and configuration are included to ensure the module runs independently.
