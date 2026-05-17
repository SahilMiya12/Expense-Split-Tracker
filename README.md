README.md
# 💸 ExpenseSplit - Expense Split Tracker

ExpenseSplit is a full-stack web application that helps users manage and split expenses among friends, roommates, family members, or groups. The application allows users to create groups, add shared expenses, track balances, and manage settlements efficiently.

---

## 🚀 Features

- 👥 User Management
- 👨‍👩‍👧 Group Creation & Management
- 💰 Add and Split Expenses
- 📊 Dashboard with Statistics
- ⚖️ Balance Tracking & Settlements
- 🔐 User Authentication System
- 🎨 Modern Responsive UI
- 🗄️ MySQL Database Integration

### Login Page
Modern authentication page with responsive design.

### Dashboard
Interactive dashboard showing:
- Total Users
- Total Groups
- Total Expenses
- Quick Actions
- Quick Add Features

---

## 🛠️ Technologies Used

### Backend
- Java
- Spring Boot
- Spring MVC
- Spring Data JPA
- Hibernate

### Frontend
- HTML
- CSS
- JavaScript
- Thymeleaf

### Database
- MySQL

### Build Tool
- Maven

## 📂 Project Structure

EExpense-Split-Tracker/
│── src/
│   ├── main/
│   │   ├── java/
│   │   ├── resources/
│   │   └── templates/
│── pom.xml
│── mvnw
│── mvnw.cmd
⚙️ Installation & Setup

1️⃣ Clone the Repository
git clone https://github.com/SahilMiya12/Expense-Split-Tracker.git
cd Expense-Split-Tracker


2️⃣ Configure MySQL Database

Create a MySQL database:

CREATE DATABASE expensesplit;

Update your application.properties file:

spring.datasource.url=jdbc:mysql://localhost:3306/expense_split_db
spring.datasource.username=root
spring.datasource.password=your_password

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true

3️⃣ Start MySQL Server
Mac (Homebrew):
brew services start mysql
Check status:
brew services list

4️⃣ Run the Application
./mvnw spring-boot:run
🌐 Access the Application
Open your browser and visit:

server.port=8080
