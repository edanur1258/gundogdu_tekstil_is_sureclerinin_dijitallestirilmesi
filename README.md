# 🏭 Gündoğdu Tekstil – Factory Management System

A web-based factory management system developed to digitalize and manage the daily operations of a textile manufacturing company.

The project provides a centralized platform for managing production processes, personnel operations, machine maintenance, inventory tracking, and customer interactions.

## 🚀 Features

### 📊 Management Dashboard
- Centralized management interface
- Personnel performance monitoring
- Operational data visualization
- Machine fault report tracking

### 👥 Personnel Management
- Personnel login and dashboard
- Working hours and shift tracking
- Performance evaluations
- Leave request and approval management

### ⚙️ Production & Machine Management
- Machine information management
- Machine fault reporting
- Fault status tracking
- Machine-related data analysis

### 📦 Inventory Management
- Raw material inventory tracking
- Factory stock management
- Supplier and order-related operations

### 👤 Customer Management
- Customer registration and login
- Secure password hashing with bcrypt
- Customer-specific dashboard

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Frontend structure |
| CSS3 | Interface design |
| JavaScript | Frontend functionality |
| Node.js | Backend runtime |
| Express.js | REST API development |
| MySQL | Relational database |
| mysql2 | Database connectivity |
| bcrypt | Password hashing |
| Multer | File upload handling |
| OpenAI API | AI integration |

## 🏗️ Project Architecture

The application follows a client-server architecture.

- **Frontend:** User interfaces and dashboards.
- **Backend:** Node.js and Express.js REST API.
- **Database:** MySQL for storing and managing application data.

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/ozturkkomer/gundogdu_tekstil_proje.git
```

### 2. Navigate to the project directory

```bash
cd gundogdu_tekstil_proje
```

### 3. Install dependencies

```bash
npm install
```

### 4. Configure the database

Create a MySQL database named:

```sql
CREATE DATABASE gundogdu_tekstil;
```

Configure your database connection in `db.js` according to your local MySQL settings.

### 5. Start the application

```bash
npm start
```

For development mode:

```bash
npm run dev
```

### 6. Open the application

Navigate to:

```text
http://localhost:3000
```

## 📁 Main Project Structure

```text
gundogdu_tekstil_proje/
│
├── public/          # Frontend pages and assets
├── routes/          # API route definitions
├── uploads/         # Uploaded files
├── db.js            # MySQL database connection
├── server.js        # Main Express server
├── package.json     # Project dependencies
└── README.md        # Project documentation
```

## 🎯 Project Objective

The main objective of this project is to improve operational efficiency in textile manufacturing by bringing different factory management processes together in a single digital platform.

The system aims to simplify data management, improve communication between departments, and support more effective operational decision-making.

## 👩‍💻 Contributors

Developed as a collaborative software project for a textile manufacturing company.

**GitHub Repository:**  
[ Gündoğdu Tekstil Project](https://github.com/ozturkkomer/gundogdu_tekstil_proje)

---

*This project is continuously being developed and improved.*
