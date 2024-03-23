# Restaurant Delivery Monitoring System

## 1. Introduction
Efficient data management is crucial for powering business applications and providing analytical data for decision-making. Database Management Systems (DBMS) offer benefits such as visibility, reliability, security, and scalability. This project aims to develop a DBMS tailored for restaurants, specifically focusing on delivery monitoring. It manages orders, waiters, bills, tables, reservations, and products. 

## 2. Design Attributes

### Entity Sets and Attributes
- **RESERVATION**: Holds customer reservation information.
- **TABLE**: Represents tables in the restaurant.
- **WAITER**: Stores information about restaurant staff.
- **ORDER**: Manages customer orders.
- **BILL**: Tracks billing information.
- **PRODUCT**: Stores details about items served.
- **INGREDIENT**: Manages ingredients used in products.
- **SUPPLIER**: Stores information about ingredient suppliers.

### Relationship Sets and Attributes
- **RESERVATION-TABLE**: Links reservations to tables.
- **TABLE-WAITER**: Associates tables with waiters.
- **TABLE_ORDER**: Connects tables with orders.
- **BILL_ORDER**: Links bills with orders.
- **ORDER-PRODUCT**: Associates orders with products.
- **FOOD-INGREDIENT**: Links food items with ingredients.
- **SUPPLIER-INGREDIENT**: Associates ingredients with suppliers.

## 3. Users
- Waiter
- Restaurant Manager
- Cashier
- Chef

## 4. Business Rules
- Waiters must be over 18.
- Product prices cannot be negative.
- Orders must be marked as prepared after preparation.
- Bills and orders cannot be assigned to multiple tables.
- Two reservations cannot be made for the same table simultaneously.
- Table location must be one of garden, inside, or terrace.
- Order status must be either prepared or unprepared.
- Bill status must be paid or unpaid.
- Product cost cannot be negative.
- Product type must be beverage or food.
- Payment method must be credit card or cash.
- Table size cannot be less than one.
- Floor cannot exceed five.
- Removal of a table should remove associated reservations.
- Beverages cannot have ingredients.

## 5. ER Diagram and Relational Schema
- **ER Diagram**: *Not Provided*
- **Relational Schema**:
  - Detailed schema provided in the project documentation.

