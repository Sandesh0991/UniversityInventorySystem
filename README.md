# University Inventory System

## Overview
The **University Inventory System** is a Java-based console application developed to manage university equipment and staff assignments. The system allows administrators to register equipment and staff members, assign and return equipment, and enforce inventory rules such as availability and assignment limits.

This project was created as part of a coding assessment and demonstrates core Java concepts including object-oriented programming, inheritance, exception handling, and basic inventory management logic.

## Features

### Equipment Management
- Add new equipment with:
  - Asset ID
  - Name
  - Brand
  - Category
  - Warranty period
- Automatically tracks equipment availability

### Staff Management
- Register staff members with:
  - Staff ID
  - Name
  - Email
- Maintain a list of equipment assigned to each staff member

### Equipment Assignment
- Assign available equipment to staff members
- Enforces a maximum of **5 items per staff member**
- Prevents assignment of unavailable equipment

### Equipment Return
- Allows staff members to return assigned equipment
- Updates availability status correctly

### Error Handling
- Custom exceptions for inventory-related errors
- Clear console messages for invalid operations

### Maintenance Fee Calculation
- Calculates overdue maintenance fees based on equipment category
