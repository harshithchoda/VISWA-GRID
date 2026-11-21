 # VISWA GRID 🌍
### Smart Civic Issue Reporting and Resolution System

## 📌 About the Project

VISWA GRID is a Java-based web application designed to improve the way citizens report and track public infrastructure problems.

Citizens can report civic issues such as potholes, garbage accumulation, damaged streetlights, and water leakage. The platform allows citizens to submit complaints, provide location details, and track complaint progress.

Administrators can access a dashboard to view complaints and update their resolution status.

## 🎯 Objectives

- Make civic issue reporting easier and more accessible.
- Provide a centralized platform for complaint management.
- Allow citizens to track their submitted complaints.
- Help administrators monitor and manage public issues.
- Improve transparency and accountability.

## ✨ Key Features

### Citizen Module
- Citizen registration and login.
- Secure password hashing.
- Submit civic complaints.
- Select complaint location using an interactive map.
- Upload complaint photographs.
- Track complaints using a reference ID.

### Admin Module
- Secure administrator login.
- Admin dashboard.
- View submitted complaints.
- Manage complaint records.
- Update complaint status.

### Additional Features
- Form validation.
- Session-based authentication.
- Complaint reference IDs.
- Database connectivity.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Java | Backend development |
| JSP | Dynamic web pages |
| Jakarta Servlets | Request handling |
| HTML | Webpage structure |
| CSS | Styling and layout |
| JavaScript | Frontend interactions |
| MySQL | Database |
| Maven | Dependency management |
| BCrypt | Password hashing |
| Leaflet.js | Interactive maps |

## 📂 Project Structure

```text
VISWA-GRID/
│
├── pom.xml
├── .gitignore
│
└── src/
    └── main/
        ├── java/
        │   └── com/viswagrid/
        │       ├── controller/
        │       ├── dao/
        │       ├── model/
        │       └── util/
        │
        └── webapp/
            ├── WEB-INF/
            ├── index.html
            ├── admin-dashboard.jsp
            ├── admin-login.jsp
            ├── citizen-dashboard.jsp
            ├── citizen-login.jsp
            ├── citizen-register.jsp
            ├── report-issue.html
            └── track-complaint.jsp
```

## ⚙️ Technologies and Requirements

- Java 17 or later
- Apache Maven
- Apache Tomcat 10.1 or compatible Jakarta EE 10 servlet container
- MySQL Server
- A web browser

## 🔐 Database Configuration

The application uses MySQL for storing citizen, administrator, and complaint information.

Configure these environment variables before running the application:

- `VISWA_DB_USER`
- `VISWA_DB_PASSWORD`

The database connection expects a MySQL database named `viswa_grid`.

**Note:** The database schema and table creation SQL are not included in this project ZIP and must be prepared before running the complete application.

## 🚀 Future Enhancements

- Real-time complaint notifications.
- Advanced complaint analytics.
- Mobile application integration.
- Improved complaint prioritization.
- Government department integration.

## 👨‍💻 Project

**Project Name:** VISWA GRID

**Project Title:** Smart Civic Issue Reporting and Resolution System

**Domain:** Web Application Development

---

### Making Communities Better Through Technology 🌱

VISWA GRID aims to connect citizens and administrators through a centralized digital platform for better civic issue management.
