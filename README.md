# Online Banking System

A full-stack Online Banking Application developed using **Java, Spring Boot, React.js, and PostgreSQL**. The application provides a user-friendly platform for managing bank accounts, performing financial transactions, and accessing banking services such as Loans, Fixed Deposits (FD), and Recurring Deposits (RD).

The project demonstrates full-stack application development through frontend-backend integration, REST API development, database management, and business logic implementation.

## 🚀 Technologies Used

**Backend**
- Java 17
- Spring Boot
- Spring Data JPA
- Hibernate
- Maven
- RESTful APIs

**Frontend**
- React.js
- JavaScript
- HTML5
- CSS3
- Axios
- Vite

**Database**
- PostgreSQL

**Development Tools**
- Eclipse / Spring Tool Suite
- Visual Studio Code
- Git and GitHub
- Postman

## ✨ Key Features

### 1. User Management
- User registration.
- User login.
- User account management.

### 2. Bank Account Management
- Create bank accounts.
- View account details.
- Manage account balances.
- Retrieve account information.

### 3. Banking Transactions
- Deposit money.
- Withdraw money.
- Transfer money between accounts.
- View transaction history.

### 4. Loan Management
- Explore available loan options.
- Calculate estimated monthly EMIs.
- Submit loan applications.
- View loan application status.

### 5. Fixed Deposit (FD)
- Submit Fixed Deposit applications.
- Select deposit amount and tenure.
- Choose interest payout frequency.
- Provide nominee details.

### 6. Recurring Deposit (RD)
- Submit Recurring Deposit applications.
- Select monthly deposit amount and tenure.
- View estimated maturity amount and interest details.
- Provide nominee details.

## 🏗️ Application Architecture

The application follows a frontend-backend architecture with a layered backend structure.

```text
                 React Frontend
                       |
                       | Axios / REST APIs
                       |
                Spring Boot Backend
                       |
                Controller Layer
                       |
                  Service Layer
                       |
                    DAO Layer
                       |
                Repository Layer
                       |
                Spring Data JPA
                       |
                   PostgreSQL
```

**React Frontend:** Provides the user interface and handles user interactions.

**Spring Boot Backend:** Processes API requests and handles application business logic.

**Controller Layer:** Handles incoming REST API requests.

**Service Layer:** Manages application business logic and processing.

**DAO and Repository Layers:** Handle database access and data operations.

**PostgreSQL:** Stores application data, including users, accounts, transactions, loans, FD and RD records.

## 🔄 Project Workflow

1. **User Registration and Login:** Users register and log in to access the banking application.

2. **Dashboard:** After login, users can navigate through the application and access available banking services.

3. **Account Management:** Users can create bank accounts and view their account details and balances.

4. **Banking Transactions:** Users can perform deposits, withdrawals, and transfers between accounts. Transaction details are maintained in the transaction history.

5. **Loan Management:** Users can explore loan options, calculate estimated EMIs, and submit loan applications. They can also view their application status.

6. **Fixed Deposit:** Users can submit FD applications by selecting the deposit amount, tenure, payout frequency, and nominee details.

7. **Recurring Deposit:** Users can submit RD applications by selecting the monthly deposit amount and tenure, and view estimated maturity details.

8. **Database Operations:** The Spring Boot backend processes application requests and uses Spring Data JPA and Hibernate to store and retrieve information from PostgreSQL.

## 🔗 Frontend and Backend Integration

The React frontend communicates with the Spring Boot backend through REST APIs using Axios.

- React handles the user interface and user interactions.
- Axios sends HTTP requests to the backend.
- Spring Boot processes requests and executes business logic.
- Spring Data JPA and Hibernate manage database operations.
- PostgreSQL stores and retrieves application data.
- Backend responses are returned to the frontend and displayed to users.

## 📁 Project Structure

```text
Online Banking System/
│
├── src/
│   └── main/
│       ├── java/                  # Spring Boot backend
│       ├── resources/             # Backend configuration
│       └── frontend/              # React frontend
│           ├── src/
│           ├── public/
│           └── package.json
│
├── pom.xml
├── .gitignore
└── README.md
```

## 🎯 Learning Outcomes

- Practical experience in full-stack application development.
- Developing RESTful APIs using Spring Boot.
- Building interactive user interfaces using React.js.
- Integrating frontend applications with backend services.
- Database connectivity and management using PostgreSQL.
- Implementing CRUD operations using Spring Data JPA and Hibernate.
- Understanding layered architecture and backend development.
- Working with Git and GitHub for version control.

## 👨‍💻 Author

**Koushik Nayak**

- GitHub: [Koushik-Nayak](https://github.com/Koushik-Nayak)

---

*This project is developed for educational and portfolio demonstration purposes.*