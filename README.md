# Little Lemon DB Capstone Project

This project contains the data model and implementation of the **Little Lemon** restaurant database system, developed as part of the capstone project for the DataBases course.

## Project Structure

- `LittleLemonDM.mwb`: MySQL Workbench data model.
- `LittleLemonDM.png`: Entity-Relationship (ER) diagram exported from the model.
- `LittleLemonDB.sql`: SQL script to create the database schema and tables.

## Database Overview

The database includes the following core tables:

- `Customer`: Stores customer contact details.
- `Staff`: Stores staff roles and salary info.
- `Bookings`: Stores table booking data.
- `Orders`: Stores order data including date, quantity, and cost.
- `Order_Delivery_Status`: Tracks the delivery status of each order.
- `Menu`: Stores menu items categorized by type.
- `Order_Menu_Items`: Linking table between orders and menu items.

## How to Use

1. Clone the repository.
2. Open `LittleLemonDM.mwb` in MySQL Workbench.
3. Use **Forward Engineer** to generate the database named `LittleLemonDB`.
4. Alternatively, execute `LittleLemonDB.sql` in the SQL editor.

---

Developed for educational purposes as part of the Databases capstone.
