# Case Study: ATM Machine
## White Belt (Beginner Level)
### Problem Statement
In this case study, we will be building an ATM machine using NestJS, which will allow users to perform basic banking transactions such as withdrawing cash and checking their account balance. We will cover all the topics in the White Belt level syllabus.

ATM Machine Features:
- Login with a PIN
- View account balance
- Withdraw cash
- Deposit cash
- Transfer funds

### Implementation
We will begin by creating a NestJS application with the required file structure.

Create a module for handling ATM operations and configure routing for each feature.

Implement the login functionality with a hardcoded PIN and validation.

Create controllers and corresponding service providers for each of the available transactions.


## Yellow Belt (Intermediate Level)
### Problem Statement
Continuing from the White Belt level case study of building an ATM machine, in the Yellow Belt level case study, we will expand the functionality of the ATM machine and cover additional topics from the syllabus.

ATM Machine Features:
- Login with a PIN
- View account balance
- Withdraw cash
- Deposit cash
- Transfer funds
- **View transaction history**

### Implementation
Implement validation pipes to validate incoming data for fund transfers.

Integrate TypeORM for database access and define entities for user accounts and transactions.

Implement AOP principles for logging or other cross-cutting concerns.


## Orange Belt (Advanced Beginner Level)
### Problem Statement
Continuing from the Yellow Belt level case study of building an ATM machine, in the Orange Belt level case study, we will expand the functionality even further and cover additional topics from the syllabus.

ATM Machine Features:
- Login with a PIN
- View account balance
- Withdraw cash
- Deposit cash
- **Transfer funds to other accounts within the same bank**
- View transaction history
- **Download transaction history as a CSV file**

### Implementation
Implement authentication using JWT and restrict access to specific routes based on user roles.

Handle exceptions and customize error responses in the application.

Implement middleware for logging incoming requests and errors.

Create a CSV download endpoint for transaction history.

## Green Belt (Intermediate Advanced Level)
### Problem Statement
Continuing from the Orange Belt level case study of building an ATM machine, in the Green Belt level case study, we will further expand the functionality and cover additional topics from the syllabus.

ATM Machine Features:
- Login with a PIN
- View account balance
- Withdraw cash
- Deposit cash
- Transfer funds to other accounts within the same bank
- View transaction history
- Download transaction history as a CSV file

### Implementation
Integrate Swagger for API documentation.

Implement validation using DTOs (Data Transfer Objects) for incoming data.

Create a Caching layer to improve application performance.

Explore advanced dependency injection techniques and inversion of control principles.
