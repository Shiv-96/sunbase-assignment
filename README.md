# sunbase-assignment

This project is a Customer Management System with JWT authentication. The backend uses Spring Boot and MySQL, while the frontend uses HTML, CSS, and JavaScript. It allows users to create, update, delete, and view customers with pagination, sorting, and searching features. The application also has a sync feature that fetches customer data from a remote API and updates the database.

## Features
- JWT Authentication (Login required to access customer features)
- Create a new customer
- Update an existing customer
- Delete a customer
- View a list of customers with pagination, sorting, and searching
- Sync customer data from a remote API
- Basic HTML/CSS/JS frontend

## Tech Stack

### Backend:
- Java (Spring Boot)
- MySQL (Database)
- Spring Data JPA (Database interaction)
- Spring Security (JWT authentication)
- JJWT (JWT library)

### Frontend:
- HTML/CSS/JavaScript


### Steps

1. **Clone the repository**:
    ```bash
    git clone https://github.com/Shiv-96/sunbase-assignment.git
    ```

2. **Set up MySQL Database**:
    Create a MySQL database named `sunbase`.
    ```sql
    CREATE DATABASE sunbase;
    ```

3. **Configure Database Properties**:
    Update the `src/main/resources/application.properties` file with your MySQL credentials:
    ```properties
    spring.datasource.url=jdbc:mysql://localhost:3306/sunbase
    spring.datasource.username=root
    spring.datasource.password=root
    spring.jpa.hibernate.ddl-auto=update
    ```

4. **Run the Application**

5. **Access the Application**:
    The application will run at `http://localhost:8888`.

## Database Schema

<div align="center">
  <img src="https://github.com/Shiv-96/sunbase-assignment/blob/main/Database-Schema.png" alt="Database Schema" width="400"/>
</div>

## UI

### Customer List Page

<div align="center">
  <img src="https://github.com/Shiv-96/sunbase-assignment/blob/main/Images/Customer-List.png" alt="Customer List" width="900"/>
</div>

### Add New Customer

<div align="center">
  <img src="https://github.com/Shiv-96/sunbase-assignment/blob/main/Images/Add-Customer.png" alt="Add Customer" width="500"/>
</div>

### Edit Customet

<div align="center">
  <img src="https://github.com/Shiv-96/sunbase-assignment/blob/main/Images/Edit-Customer.png" alt="Edit Customer" width="500"/>
</div>

### Login

<div align="center">
  <img src="https://github.com/Shiv-96/sunbase-assignment/blob/main/Images/Login-Customer.png" alt="Login" width="500"/>
</div>

### Signup

<div align="center">
  <img src="https://github.com/Shiv-96/sunbase-assignment/blob/main/Images/Logout-Customer.png" alt="Signup" width="500"/>
</div>
