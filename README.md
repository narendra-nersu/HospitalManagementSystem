# 🏥 Hospital Management System

A full-stack Hospital Management System built using Spring Boot, MySQL, and a modern HTML/CSS/JavaScript UI.

---

## 🚀 Features

* 👨‍⚕️ Doctor Management (Add, View, Update, Delete)
* 🧑‍🤝‍🧑 Patient Management (Add, View, Update, Delete)
* 📅 Appointment Booking System
* 📊 Dashboard with real-time data
* 🔍 Search functionality
* 🖥️ Clean and modern UI

---

## 🛠️ Tech Stack

### Backend

* Java 21
* Spring Boot
* Spring Data JPA (Hibernate)
* MySQL

### Frontend

* HTML
* CSS
* JavaScript (Vanilla JS)

---

## 📂 Project Structure

```
src/main/java/com/hospital
│
├── controller      # REST Controllers
├── service         # Business Logic
├── repository      # JPA Repositories
├── model           # Entity Classes
│
└── HospitalManagementSystemApplication.java

src/main/resources
├── static          # Frontend (HTML, CSS, JS)
├── application.properties (ignored)
├── application-example.properties
```

---

## ⚙️ Setup Instructions

### 1️⃣ Clone Repository

```
git clone https://github.com/narendra-nersu/HospitalManagementSystem.git
cd HospitalManagementSystem
```

---

### 2️⃣ Configure Database

Create a MySQL database:

```
CREATE DATABASE hospital;
```

---

### 3️⃣ Setup Properties File

Copy example file:

```
cp src/main/resources/application-example.properties src/main/resources/application.properties
```

Update credentials:

```
spring.datasource.username=your_username
spring.datasource.password=your_password
```

---

### 4️⃣ Run Application

In IDE:

* Right click → Run as → Spring Boot App

OR via terminal:

```
mvn spring-boot:run
```

---

## 🌐 Access Application

* Backend API: [http://localhost:8080/api](http://localhost:8080/api)
* Frontend UI: [http://localhost:8080](http://localhost:8080)

---

## 🔌 API Endpoints

### Patients

* GET /api/patients
* POST /api/patients
* PUT /api/patients/{id}
* DELETE /api/patients/{id}

### Doctors

* GET /api/doctors
* POST /api/doctors
* PUT /api/doctors/{id}
* DELETE /api/doctors/{id}

### Appointments

* GET /api/appointments
* POST /api/appointments
* DELETE /api/appointments/{id}

---

## Security Note

Sensitive information like database credentials is excluded using `.gitignore`.

---

## 📸 Screenshots

![alt text](image.png)
![alt text](image-1.png)
![alt text](image-2.png)

---

## 💡 Future Enhancements

* 🔐 User Authentication (JWT)
* 📧 Email Notifications
* 📄 Medical Reports Upload
* 📱 Responsive UI / React Frontend
* 📊 Advanced Analytics Dashboard

---

## ⭐ Show your support

If you like this project, give it a ⭐ on GitHub!
