# 🏥 Hospital Management System  
### _Full-Stack Hospital Operations Platform_

<p align="center">
  <img src="https://img.shields.io/badge/Backend-Spring%20Boot-green?style=flat-square">
  <img src="https://img.shields.io/badge/Frontend-React-blue?style=flat-square">
  <img src="https://img.shields.io/badge/Database-MySQL-orange?style=flat-square">
  <img src="https://img.shields.io/badge/Security-JWT-red?style=flat-square">
  <img src="https://img.shields.io/badge/License-MIT-brightgreen?style=flat-square">
</p>

> 🚀 A full-stack hospital management system to manage **patients, doctors, nurses, appointments, and medical records** using **Spring Boot + React** with **secure JWT-based authentication**.

---

## 🧩 Features

- ✅ Role-Based Login (Patient, Doctor, Nurse, Admin)  
- ✅ JWT-based Secure Authentication  
- ✅ Appointment Booking & Scheduling  
- ✅ Patient Medical Records  
- ✅ Doctor Availability Management  
- ✅ Nurse & Staff Dashboard  
- ✅ Admin Control Panel  
- ✅ RESTful API Architecture  

---

## 🏗️ System Architecture

The system follows a **3-tier enterprise architecture**:

React Frontend
↓
Spring Boot REST API (JWT Secured)
↓
MySQL / PostgreSQL Database


---

## 🧠 Workflow Summary

1. User logs in through the React UI.  
2. Spring Boot authenticates and issues a JWT token.  
3. All API calls are sent with this token.  
4. Backend validates roles (Patient / Doctor / Nurse / Admin).  
5. Data is stored or retrieved from the database.  
6. UI updates dynamically in real-time.

---

## 👥 User Roles

### 👤 Patient
- Register & Login  
- View doctors  
- Book appointments  
- Track appointment status  
- View medical history  

### 🩺 Doctor
- View daily schedule  
- Add diagnosis  
- Prescribe medicines  
- Update patient status  

### 👩‍⚕️ Nurse / Staff
- View assigned patients  
- Update patient vitals  
- Assist doctors  

### 🛠 Admin
- Manage doctors, staff & departments  
- Monitor appointments  
- Generate reports  

---

## 🗂️ Project Structure

hospital-management-system/
├── backend/ # Spring Boot Application
│ ├── controller
│ ├── service
│ ├── repository
│ └── security (JWT)
│
├── frontend/
│ └── hospital-management-frontend/
│ ├── src
│ ├── components
│ └── api
│
└── README.md



---

## ⚙️ Tech Stack

| Layer | Technology |
|------|------------|
| **Frontend** | React, HTML, CSS, JavaScript |
| **Backend** | Java, Spring Boot |
| **Security** | Spring Security, JWT |
| **Database** | MySQL / PostgreSQL |
| **API** | REST |
| **Tools** | Git, GitHub, Postman, Maven |

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository

git clone https://github.com/laxman1607/hospital-management-system.git
cd hospital-management-system
---

### 2️⃣ Run Backend

cd backend
mvn spring-boot:run
Backend will start at: http://localhost:8080
---
### 3️⃣ Run Frontend

cd frontend/hospital-management-frontend
npm install
npm start
Frontend will start at: http://localhost:3000
---

## 📡 API Highlights

| Endpoint | Description |
|----------|-------------|
| `/login` | User authentication |
| `/register` | User registration |
| `/book-appointment` | Book appointment |
| `/view-appointments` | View appointment history |
| `/manage-doctors` | Admin doctor management |
---


## 🔐 Security

- JWT-based authentication  
- Role-based access control  
- Encrypted password storage  
- Protected REST APIs  

---
## 🧪 Future Enhancements

- Telemedicine (video consultation)  
- SMS / Email notifications  
- Analytics dashboard  
- Docker deployment  
- Cloud hosting (AWS)  

 ---

## 🌍 GitHub Repository

🔗 https://github.com/laxman1607/hospital-management-system

---
## 👨‍💻 Author

**Laxman Yabaji**  
Full-Stack Java Developer  
Final-Year Computer Science Student  
---

## 📜 License

This project is licensed under the **MIT License**.


