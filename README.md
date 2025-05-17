<h1 align="center">🌟 My Wallet - Expense tracking app 🌟</h1>

<p align="center">
  <img alt="Static Badge" src="https://img.shields.io/badge/Spring%20Boot-darkgreen?style=for-the-badge">
  <img alt="Static Badge" src="https://img.shields.io/badge/React.js-blue?style=for-the-badge">
  <img alt="Static Badge" src="https://img.shields.io/badge/mysql-red?style=for-the-badge">
  <img alt="Static Badge" src="https://img.shields.io/badge/css-purple?style=for-the-badge">
  <img alt="Static Badge" src="https://img.shields.io/badge/jwt-orange?style=for-the-badge">
</p>

## Table of contents

1. [Description](#description)
2. [How to run?](#how-to-run)
3. [Screenshots](#screenshots)

## Description

- Developed a full-stack expense tracking web application using Spring Boot, React.js, and MySQL, facilitating seamless management of day-to-day finances.
- Implemented multi-role functionality with user authentication, enabling secure access for both users and administrators, with features such as sign-in, sign-up, password reset, and email verification.
- Developed intuitive user dashboards, transaction management, upcoming/recurring transactions tracking, monthly summaries, and statistics, budget management.
- Developed categories, users and transactions management for administrators.
- Implemented management capabilities including search, filter and pagination.

## How to run?

### Step 1: Fork and Clone the Repository

1. Fork the repository to your GitHub account.

2. Clone the forked repository to your local machine.

```sh
git clone https://github.com/LoopNFlight/Full-Stack-Expense-Tracker



### Step 2: Setting up e-mail and database configurations

- Configure the following credentials in the [`application.properties`](https://github.com/LoopNFlight/Full-Stack-Expense-Tracker/blob/main/backend/src/main/resources/application.properties) file.
- Add some custom data manually in the [categories](https://github.com/LoopNFlight/Full-Stack-Expense-Tracker/blob/main/backend/src/main/java/com/fullStack/expenseTracker/models/Category.java#L13) table for both [type](https://github.com/LoopNFlight/Full-Stack-Expense-Tracker/blob/main/backend/src/main/java/com/fullStack/expenseTracker/models/TransactionType.java#L13) `expense` and `income`.
- To start as admin, Insert a new user manually with role admin in [users](https://github.com/LoopNFlight/Full-Stack-Expense-Tracker/blob/main/backend/src/main/java/com/fullStack/expenseTracker/models/User.java#L20) table.


```properties
spring.datasource.url=jdbc:mysql://localhost:3306/YOUR_DATABASE_NAME
spring.datasource.username=YOUR_USERNAME
spring.datasource.password=YOUR_PASSWORD

spring.mail.username=YOUR_USERNAME
spring.mail.password=YOUR_PASSWORD
```

### Step 3: Run the backend.

- Run the backend application. It will automatically create the required tables. 
- Add some custom data manually in the [categories](https://github.com/LoopNFlight/Full-Stack-Expense-Tracker/blob/7ecea71aaeca4e26a4aafd02fd602abe4d9da67d/backend/src/main/java/com/fullStack/expenseTracker/models/Category.java#L13) table for both [type](https://github.com/LoopNFlight/Full-Stack-Expense-Tracker/blob/7ecea71aaeca4e26a4aafd02fd602abe4d9da67d/backend/src/main/java/com/fullStack/expenseTracker/models/TransactionType.java#L13) `expense` and `income`.
- To start as admin, Insert a new user manually with role admin in [`users`](https://github.com/LoopNFlight/Full-Stack-Expense-Tracker/blob/7ecea71aaeca4e26a4aafd02fd602abe4d9da67d/backend/src/main/java/com/fullStack/expenseTracker/models/User.java#L20) table.

### Step 4: Run the frontend

1.Navigate to [frontend direcory](https://github.com/LoopNFlight/Full-Stack-Expense-Tracker/tree/main/frontend).
cd ./frontend
```

2. Install dependencies.
```
npm install
```

3. Run the app.
```
npm start
```


Access the application at [`http://localhost:3000/`](http://localhost:3000/).  
To get started create a new account using your email.

## Screenshots

![Welcome](https://github.com/user-attachments/assets/9ad0f9d5-6ea1-4bd9-a042-7bf787bb3b9f)
![Login Page](https://github.com/user-attachments/assets/4c7346db-8928-4cfd-a3fb-f97e4d7fc740)
![Register](https://github.com/user-attachments/assets/b7bbdff0-652b-4df8-9be7-a286057dd201)
![Forgot Password](https://github.com/user-attachments/assets/bd82f9bd-0c52-474a-a727-8674bec73fe5)

Users' stuff

![Dashboard](https://github.com/user-attachments/assets/709c45d8-f423-4cdd-8ce5-f54964ad9b6a)
![Transaction-History](https://github.com/user-attachments/assets/c3a2534c-b519-4926-9313-ae281923f2c9)
![Edit-Transaction](https://github.com/user-attachments/assets/425eb2eb-fb23-4204-ae6a-a72b353e82bb)
![New-Transaction](https://github.com/user-attachments/assets/f4ebe062-e00d-4870-9c2e-539b2c301418)
![Statistics](https://github.com/user-attachments/assets/ccd417f0-2bf8-45e6-88f4-9324f2727f85)
![Settings](https://github.com/user-attachments/assets/102d8580-c0fb-4d3b-8c1a-449b60b7d793)

Admin's stuff

![Transactions](https://github.com/user-attachments/assets/8ae45300-5369-4abe-9c55-8904e97a0799)
![Users](https://github.com/user-attachments/assets/6c25d5f2-121d-493d-a38a-2ef96ba074b7)
![Category](https://github.com/user-attachments/assets/a5e89bd1-f437-4948-a54a-530dfd3c2b68)
![Edit-Category](https://github.com/user-attachments/assets/e88eaf75-845a-4627-9ef4-425da9be7f2f)
![New-Category](https://github.com/user-attachments/assets/f4db3aec-21ab-42ea-8a22-10ca00baefa5)
![Settings](https://github.com/user-attachments/assets/ac855cda-9139-4eb6-842b-8d4ad3859f21)
