# Banking Software

This is a banking application developed using Java and Spring Boot. It supports essential banking operations, allowing you to manage accounts, perform transactions, and view account details. Team Project.

## Features

### 1. Account Management
- *Create accounts*: Easily create new bank accounts with the required customer information.
- *View accounts*: Retrieve detailed information about existing accounts.
- *Update account details*: Modify account information.

### 2. Transactions
- *Deposit/Withdraw funds*: Perform transactions like deposits and withdrawals on individual accounts.
- *Account balance inquiries*: Check the current balance of any account in the system.

### 3. RESTful API Design
- Follows the principles of REST architecture.
- Clean separation between the controller, service, and data access layers.
- Uses DTOs for safer data transfer.

### 4. Spring Boot Integration
- *Spring Data JPA*: Manages persistence and database operations.
- *Service Layer*: Business logic is encapsulated within the service layer for modularity and scalability.
- *Controller Layer*: Exposes endpoints for account and transaction management.

### 5. Mapper Layer
- Utilizes the *AccountMapper* to convert between entities and DTOs, ensuring clean separation of concerns.

## Technologies Used
- *Java 8+*
- *Spring Boot*
- *Spring Data JPA*
- *H2 Database* (or other databases can be integrated)
- *Maven* for build automation.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/vanshaj2002/Banking-Application-Java_SpringBoot.git
