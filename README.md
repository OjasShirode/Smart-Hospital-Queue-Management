# 🏥 Smart Hospital Queue Management System (MediQueue)

> A modern cloud-based Hospital Queue Management System that streamlines patient appointments and queue management through dedicated portals for Patients, Doctors, Receptionists, and Administrators. The application provides secure authentication, real-time queue updates, and centralized hospital management using Firebase services.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/TailwindCSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![Firebase Hosting](https://img.shields.io/badge/Firebase%20Hosting-DD2C00?style=for-the-badge&logo=firebase&logoColor=white)

---

# 🌐 Live Demo

🔗 **Project Website**  
https://mediqueue-7e102.web.app

---

# 📖 Project Overview

MediQueue is a web-based Hospital Queue Management System developed to reduce patient waiting time and improve hospital workflow through digital queue management.

The system enables patients to book appointments online, doctors to manage consultations efficiently, receptionists to organize patient queues, and administrators to monitor overall hospital activities from a centralized dashboard.

The application is designed with a responsive interface and secure role-based authentication while leveraging Firebase services for cloud storage, authentication, and deployment.

---

# ✨ Key Features

## 👤 Patient Portal

- Secure Email OTP Authentication
- Patient Registration & Login
- Appointment Booking
- Live Queue Tracking
- Token Management
- Appointment History
- Responsive Dashboard

### 👨‍⚕️ Doctor Portal

- Secure Login
- View Assigned Patients
- Manage Consultation Queue
- Update Consultation Status
- Daily Schedule Management

### 👩‍💼 Receptionist Portal

- Register Patients
- Generate Queue Tokens
- Manage Patient Appointments
- Monitor Live Queue
- Search Patient Records

### 👨‍💻 Administrator Portal

- Manage Doctors
- Manage Receptionists
- Manage Patients
- Queue Monitoring
- User Management
- Hospital Dashboard

---

# 🚀 Technology Stack

| Category | Technology |
|----------|------------|
| Frontend | HTML5, Tailwind CSS |
| Programming Language | JavaScript (ES6) |
| Authentication | Firebase Authentication |
| Database | Firebase Realtime Database |
| Email Service | EmailJS |
| Hosting | Firebase Hosting |

---

# 🏗️ System Architecture

```
                       Firebase Authentication
                                 │
                      Email OTP Verification
                                 │
                                 ▼
                  Firebase Realtime Database
                                 │
       ┌─────────────┬─────────────┬─────────────┐
       │             │             │
    Patient      Doctor     Receptionist
                     │
                     ▼
               Administrator
```

---

# 🔐 Authentication Flow

```
User

↓

Enter Email Address

↓

Receive OTP

↓

Verify OTP

↓

Firebase Authentication

↓

Redirect to Dashboard
```

---

# 🔄 Queue Management Workflow

```
Patient Registration

↓

Appointment Booking

↓

Queue Token Generation

↓

Waiting Queue

↓

Doctor Consultation

↓

Appointment Completed
```

---

# 📂 Project Structure

```
Smart-Hospital-Queue-Management
│
├── index.html
├── patient-auth.html
├── patient-dashboard.html
├── doctor-auth.html
├── doctor-dashboard.html
├── receptionist-auth.html
├── receptionist-dashboard.html
├── admin-auth.html
├── admin-dashboard.html
├── firebase.json
├── .firebaserc
├── .gitignore
├── README.md
└── 404.html
```

---

# 🎯 Project Objectives

- Digitize hospital queue management.
- Reduce patient waiting time.
- Improve appointment scheduling.
- Enhance hospital workflow.
- Eliminate manual queue handling.
- Provide secure role-based authentication.
- Enable real-time queue monitoring.
- Improve patient experience.

---

# 📈 Advantages

- Cloud-Based Solution
- Secure Authentication
- Real-Time Database
- Responsive User Interface
- Multi-Role Access
- Easy Maintenance
- Faster Queue Processing
- Scalable Architecture

---

# 🚀 Future Enhancements

- AI-Based Queue Prediction
- QR Code Patient Check-in
- SMS Notifications
- WhatsApp Notifications
- Online Payment Integration
- Mobile Application
- Doctor Availability Calendar
- Multi-Hospital Support
- Analytics Dashboard
- Emergency Queue Management
- Report Generation

---

# ⚙️ Getting Started

### Clone the Repository

```bash
git clone https://github.com/OjasShirode/Smart-Hospital-Queue-Management.git
```

### Navigate to the Project

```bash
cd Smart-Hospital-Queue-Management
```

### Configure Firebase

- Create a Firebase project.
- Enable Firebase Authentication.
- Enable Firebase Realtime Database.
- Update your Firebase configuration.

### Run the Project

Deploy using Firebase Hosting or serve the project using any local web server.

---

# 🌍 Deployment

**Live Website**

https://mediqueue-7e102.web.app

---

# 👨‍💻 Developer

**Ojas Shirode**

### Connect with Me

💻 **GitHub**  
https://github.com/OjasShirode

💼 **LinkedIn**  
https://www.linkedin.com/in/ojasshirode

🌐 **Project Website**  
https://mediqueue-7e102.web.app

---

# 🤝 Contributing

Contributions are always welcome.

1. Fork this repository.
2. Create a new feature branch.
3. Commit your changes.
4. Push your branch.
5. Open a Pull Request.

---

# ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub.

It motivates me to build more innovative and impactful projects.

---

## 🙏 Thank You

Thank you for visiting this repository.

If you have any suggestions, feedback, or collaboration opportunities, feel free to connect with me through GitHub or LinkedIn.