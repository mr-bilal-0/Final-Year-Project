# 🏥 Doctor Appointment Booking System  
A full-featured MERN Stack web application that allows patients to book appointments with doctors online.  
The system includes user authentication, doctor management, appointment scheduling, and an admin dashboard.

---

## 🚀 Features

### 👤 User Features
- Create account & login (JWT Authentication)
- View available doctors
- Check doctor details, timings, fee, specialization
- Book appointment
- View appointment history & status
- Profile management

### 👨‍⚕️ Doctor Features
- Doctor login / signup
- Manage available timings
- Approve or decline appointments
- Manage profile (specialization, fee, experience)
- Dashboard for appointments

### 🛠 Admin Features
- Admin login
- Add / Remove / Approve doctors
- Manage all user accounts
- Manage all appointments
- View system statistics

---

## 🧰 Tech Stack

### **Frontend**
- React.js  
- React Router  
- Axios  
- TailwindCSS / Bootstrap (if used)

### **Backend**
- Node.js  
- Express.js  
- MongoDB  
- Mongoose  
- JWT Authentication  
- Bcrypt Password Hashing  

---

## 📁 Folder Structure
Final-Year-Project/
│
├── backend/
│ ├── config/
│ ├── controllers/
│ ├── models/
│ ├── routes/
│ ├── middleware/
│ └── server.js
│
└── frontend/
├── public/
├── src/
│ ├── components/
│ ├── pages/
│ ├── context/
│ ├── hooks/
│ └── App.jsx

---

## 🗄 Database Models

### 1️⃣ User Model  
- name  
- email  
- password  
- role (user/doctor/admin)

### 2️⃣ Doctor Model  
- userId  
- specialization  
- timings  
- fee  
- experience  

### 3️⃣ Appointment Model  
- userId  
- doctorId  
- date & time  
- status (pending, approved, cancelled)

---

## ⚙️ Installation Guide

### 📌 Clone the repo
git clone https://github.com/mr-bilal-0/Final-Year-Project.git

cd Final-Year-Project
cd backend
npm install

---

## 📸 Screenshots
(Add your screenshots here)

- Home Page  
- Login Page  
- Book Appointment  
- Doctor Dashboard  
- Admin Panel  

---

## 📌 API Endpoints Summary

### 👤 User Routes
- POST /api/user/register  
- POST /api/user/login  
- GET /api/user/appointments  

### 👨‍⚕️ Doctor Routes
- GET /api/doctor/list  
- POST /api/doctor/update  
- GET /api/doctor/appointments  

### 🛠 Admin Routes
- GET /api/admin/users  
- GET /api/admin/doctors  
- POST /api/admin/approve-doctor  

---

## ⭐ Final Notes
This project is built for learning MERN Stack & demonstrating real-world full-stack skills such as:
- authentication  
- role-based access  
- form handling  
- REST APIs  
- database relationships  
- dashboard UI  
- complete CRUD operations  

---

## 👨‍💻 Developer
**Muhammad Bilal**  
MERN Stack Developer  
GitHub: [mr-bilal-0](https://github.com/mr-bilal-0)
