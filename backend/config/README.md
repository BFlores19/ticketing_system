# Capstone Ticketing System Backend

This is the backend server for the Capstone Ticketing System project, built using Node.js, Express, and MySQL with Sequelize as the ORM.
This is the backend server for the Capstone Ticketing System project, built using Node.js, Express, and PostgreSQL with Sequelize as the ORM.

## 🛠️ Installation

### Prerequisites

- **Node.js & npm**: Make sure you have [Node.js](https://nodejs.org/) and npm installed.
- **MySQL Database**: Set up a local MySQL database.
- **PostgreSQL Database**: Set up a local PostgreSQL database. (prod uses MySQL)

### Dependencies

@@ -34,9 +34,11 @@ npx nodemon server.js
### 📁 Project Structure

- **config/:** Database configuration.
- **controllers/:**: Handles request processing and business logic 
- **models/:** Sequelize models (database tables).
- **migrations/:** Database migrations (adding or modifying tables)
- **routes/:** Express routes (API endpoints).
- **services/** API for sending email notifications 
- **server.js:** Main server file.

### 📝 Notes
Ensure your MySQL database is set up correctly and the **.env** file has valid credentials. 