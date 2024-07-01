# realtor-management-system  MS SQL 

This repository contains the SQL scripts to create and manage a Real Estate Management System. The database is designed to handle properties, categories, pictures, advertisements, agents, contracts, users, prices, and visits.

## Database Structure

- **Categories:** Stores the types of properties (e.g., land, house, apartment).
- **Properties:** Contains details about each property, including its category, neighborhood, area, and other attributes.
- **Pictures:** Stores image URLs and the number of rooms for properties.
- **Advertisement:** Contains information about property advertisements, including dates and agencies.
- **Agents:** Contains details about real estate agents and their respective agencies.
- **Contracts:** Manages the contracts related to property sales and rentals.
- **Users:** Contains user details for the system.
- **Price:** Manages the pricing details for properties.
- **Visits:** Tracks visit details for properties.

## How to Use

1. **Create the Database:**
   ```sql
   CREATE DATABASE EstateSystem;
