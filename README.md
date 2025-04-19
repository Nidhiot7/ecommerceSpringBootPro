# 🛒 E-commerce Web Application (Spring Boot)

This is a fully functional E-commerce web application developed using **Spring Boot**, **Hibernate**, and **MySQL**, offering a robust online shopping experience. It features user registration, product and category management, a shopping cart, and role-based access for users and admins.

---

## 🚀 Features

- 👤 **User Registration & Login**: Secure user authentication using Spring Security.
- 🛍️ **Product Management**: View, add, update, and delete products.
- 🗂️ **Category Management**: Admins can manage product categories.
- 🛒 **Shopping Cart**: Users can add and manage products in their cart.
- 🔐 **Role-Based Access Control**: Admin and user roles with different access levels.

---

## 🛠️ Technologies Used

- **Backend**: Spring Boot, Spring Security
- **Frontend**: Thymeleaf, JSP
- **ORM**: Hibernate
- **Database**: MySQL
- **Build Tool**: Maven

---

## 📦 Project Structure

src/ ├── main/ │ ├── java/ │ │ └── com.ecommerce/ │ │ ├── controller/ │ │ ├── service/ │ │ ├── dao/ │ │ └── JtSpringProjectApplication.java │ ├── resources/ │ │ └── application.properties │ └── webapp/ │ └── *.jsp


---

## ⚙️ Setup & Installation

### 1. Clone the Repository

```bash
git clone [https://github.com/Nidhiot7/ecommerceSpringBootPro.git]
cd E-commerce-project-springBoot

2. Configure the Database
Edit src/main/resources/application.properties:

db.url=jdbc:mysql://localhost:3306/ecommjava?createDatabaseIfNotExist=true
db.username=your_mysql_username
db.password=your_mysql_password
spring.jpa.hibernate.ddl-auto=update

3. Run the Application
- Open the project in your IDE.

- Run the JtSpringProjectApplication.java class.

- Visit http://localhost:8080

🔑 Default Credentials
Admin:

- Username: admin

- Password: 123

User:

- Username: lisa

- Password: 765

📂 Database Setup
- Ensure MySQL/MariaDB is installed.

- Create the database manually: CREATE DATABASE ecommjava;

- Optionally run basedata.sql if available to insert sample data.
