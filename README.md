Live Link: https://hospital-management-system-five-khaki.vercel.app/
## ⚠️ 🔒 Important: Code Security Disclaimer

> **The complete source code for this project is maintained in a Private Repository.**<div align="center">

<h1 align="center">🏥 Bireena Medico - Hospital Management System</h1>

<p align="center">
A Modern Multi-Role Hospital Management Platform built using React, Node.js, Express.js, MongoDB and Supabase.
</p>

<p align="center">

<a href="https://hospital-management-system-five-khaki.vercel.app/" target="_blank">
<img src="https://img.shields.io/badge/Live-Demo-16a34a?style=for-the-badge&logo=vercel&logoColor=white">
</a>


<img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black">

<img src="https://img.shields.io/badge/Node.js-Express-green?style=for-the-badge&logo=node.js">

<img src="https://img.shields.io/badge/MongoDB-Database-green?style=for-the-badge&logo=mongodb">

<img src="https://img.shields.io/badge/Supabase-Backend-3ECF8E?style=for-the-badge&logo=supabase">

</p>

---

# 📖 About The Project

Bireena Medico is a complete Hospital Management System developed to simplify hospital operations through an intuitive, secure, and scalable platform.

The application provides dedicated dashboards for administrators, doctors, clinics, pharmacy staff, and appointment managers while maintaining secure role-based authentication and efficient workflow management.

It centralizes hospital operations including patient management, appointments, medicine inventory, billing, reporting, analytics, and administrative controls into a single modern web application.

---



# 🌐 Live Demo

### 🚀 Website

https://hospital-management-system-five-khaki.vercel.app/

---

# 🖼️ Homepage

<p align="center">
  <img src="./bireena.png" width="100%" alt="Homepage Screenshot">
</p>

### Intelligent Healthcare Platform

Bireena Medico is designed to streamline healthcare operations by providing dedicated portals for hospital administrators, doctors, clinics, pharmacy staff, and appointment managers.

The platform enables secure patient management, appointment scheduling, medicine inventory tracking, billing, analytics, and operational reporting through a modern responsive interface.

---

# ✨ Features

| 🏥 **Admin Portal** | 👨‍⚕️ **Doctor Portal** |
|----------------------|-------------------------|
| • Dashboard Analytics | • Doctor Dashboard |
| • User Management | • Today's Schedule |
| • Doctor Management | • Patient Queue |
| • Patient Management | • Consultation Management |
| • Appointment Dashboard | • Patient Records |
| • Lab Dashboard | • Revenue Overview |
| • Pharmacy Dashboard | |
| • Revenue Analytics | |
| • Reports & Statistics | |

| 💊 **Clinic Portal** | 📅 **Appointment Portal** |
|----------------------|---------------------------|
| • Medicine Inventory | • Appointment Scheduling |
| • Medicine Stock Management | • Live Queue |
| • Low Stock Alerts | • Consultation Status |
| • Expiry Alerts | • Doctor Availability |
| • Requirement Requests | • Appointment History |
| • Billing | • Patient Search |
| • Medicine History | |

| 🔐 **Authentication** | 🚀 **Platform** |
|----------------------|----------------|
| • Secure Login | • Responsive UI |
| • Role-Based Access | • Modern Dashboard |
| • Protected Routes | • Multi-Role System |
| • User Authorization | • Secure Architecture |
---

# 🛠️ Tech Stack

### 🎨 Frontend

![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

### ⚙️ Backend

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)

### 🗄️ Database

![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)

### 🔐 Authentication

![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![RBAC](https://img.shields.io/badge/Role--Based_Access_Control-0A8F5B?style=for-the-badge)

### 🚀 Deployment

![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![MongoDB Atlas](https://img.shields.io/badge/MongoDB_Atlas-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
---

# 📂 Project Structure

```text
Hospital-management-system/

backend/
├── config
│   ├── cloudinary.js
│   ├── config.env
│   ├── database.js
│   ├── db-client.js
│   ├── env.js
│   ├── razorpay.js
│   ├── schema.sql
│   ├── socket.js
│   └── supabase.js
├── controllers
│   ├── analytics.controller.js
│   ├── appointment.controller.js
│   ├── auth.controller.js
│   ├── billing.controller.js
│   ├── doctor.controller.js
│   ├── history.controller.js
│   ├── laboratory.controller.js
│   ├── notification.controller.js
│   ├── patient.controller.js
│   ├── payment.controller.js
│   ├── pharmacy.controller.js
│   ├── prescription.controller.js
│   ├── queue.controller.js
│   ├── report.controller.js
│   ├── slot.controller.js
│   └── user.controller.js
├── jobs
│   ├── appointmentReminder.js
│   ├── dailyAnalytics.js
│   ├── inventoryAlert.js
│   └── reportCleanup.js
├── middleware
├── middlewares
│   ├── auth.middleware.js
│   ├── error.middleware.js
│   ├── rateLimiter.middleware.js
│   ├── role.middleware.js
│   ├── upload.middleware.js
│   └── validation.middleware.js
├── models
│   ├── Appointment.js
│   ├── AuditLog.js
│   ├── Billing.js
│   ├── Doctor.js
│   ├── History.js
│   ├── Inventory.js
│   ├── Invoice.js
│   ├── LabReport.js
│   ├── LabTest.js
│   ├── Medicine.js
│   ├── MedicineDistribution.js
│   ├── MedicineRequirement.js
│   ├── Notification.js
│   ├── Patient.js
│   ├── PatientHistory.js
│   ├── Payment.js
│   ├── Prescription.js
│   ├── Queue.js
│   ├── RefreshToken.js
│   ├── Role.js
│   ├── Service.js
│   └── User.js
├── routes
│   ├── analytics.routes.js
│   ├── appointment.routes.js
│   ├── auth.routes.js
│   ├── availability.routes.js
│   ├── billing.routes.js
│   ├── doctor.routes.js
│   ├── history.routes.js
│   ├── laboratory.routes.js
│   ├── notification.routes.js
│   ├── patient.routes.js
│   ├── payment.routes.js
│   ├── pharmacy.routes.js
│   ├── prescription.routes.js
│   ├── queue.routes.js
│   ├── report.routes.js
│   ├── slot.routes.js
│   └── user.routes.js
├── script
│   ├── seed-admin.js
│   └── seed.js
├── services
│   ├── analytics.service.js
│   ├── appointment.service.js
│   ├── auth.service.js
│   ├── billing.service.js
│   ├── doctor.service.js
│   ├── laboratory.service.js
│   ├── notification.service.js
│   ├── patient.service.js
│   ├── payment.service.js
│   ├── pharmacy.service.js
│   ├── prescription.service.js
│   ├── queue.service.js
│   ├── report.service.js
│   └── user.service.js
├── sockets
│   ├── appointment.socket.js
│   ├── index.js
│   ├── notification.socket.js
│   └── queue.socket.js
├── tests
│   ├── auth.test.js
│   ├── verify_billing_history.js
│   └── verify_doctor_allotment.js
├── utils
│   ├── documentExtractor.js
│   ├── email.js
│   ├── generateInvoice.js
│   ├── hashPassword.js
│   ├── helpers.js
│   ├── jwt.js
│   ├── localUpload.js
│   ├── logger.js
│   ├── pagination.js
│   ├── response.js
│   └── supabaseUpload.js
├── validators
│   ├── appointment.validator.js
│   ├── auth.validator.js
│   ├── billing.validator.js
│   ├── doctor.validator.js
│   ├── patient.validator.js
│   └── payment.validator.js
├── app.js
├── jest.config.cjs
├── memory-db.json
├── package-lock.json
├── package.json
├── README.md
└── server.js


frontend/
├── public
│   ├── 1.jpeg
│   ├── favicon.svg
│   ├── icons.svg
│   ├── logo.png
│   └── logo.svg
├── src
│   ├── assets
│   │   ├── faviconn.png
│   │   ├── logo.png
│   │   ├── LogoMedico.png
│   │   └── MedicoLogo.png
│   ├── components
│   │   ├── common
│   │   │   ├── Button.jsx
│   │   │   └── Input.jsx
│   │   ├── dashboard
│   │   │   └── AIConsultant.jsx
│   │   ├── lab
│   │   │   └── ui.jsx
│   │   ├── layout
│   │   │   ├── Navbar.jsx
│   │   │   ├── NotificationCenter.jsx
│   │   │   └── Sidebar.jsx
│   │   ├── ui
│   │   │   ├── AnimatedBackground.jsx
│   │   │   ├── index.js
│   │   │   ├── SectionHeader.jsx
│   │   │   └── StatCard.jsx
│   │   ├── Breadcrumbs.jsx
│   │   ├── Layout.jsx
│   │   ├── RoleGuard.jsx
│   │   └── sonner.jsx
│   ├── context
│   │   └── AuthContext.jsx
│   ├── data
│   │   └── bill.js
│   ├── hooks
│   │   └── useAuth.js
│   ├── lib
│   │   ├── api.js
│   │   ├── constants.js
│   │   ├── error-capture.js
│   │   ├── error-page.js
│   │   ├── format.js
│   │   ├── mock-reports.js
│   │   ├── mock-tests.js
│   │   ├── navigation.jsx
│   │   ├── reports-store.js
│   │   ├── tests-store.js
│   │   └── utils.js
│   ├── pages
│   │   ├── admin
│   │   │   ├── AdminAnalytics.jsx
│   │   │   ├── DoctorDashboard.jsx
│   │   │   ├── DoctorsManagement.jsx
│   │   │   ├── UserAdd.jsx
│   │   │   ├── UserManagement.jsx
│   │   │   └── UserRoleManagement.jsx
│   │   ├── appointment
│   │   │   ├── AddAppointment.jsx
│   │   │   ├── AddPatientAppointment.jsx
│   │   │   ├── AppointmentBilling.jsx
│   │   │   ├── AppointmentDashboard.jsx
│   │   │   ├── AppointmentHistory.jsx
│   │   │   ├── AppointmentListNew.jsx
│   │   │   ├── AppointmentPatients.jsx
│   │   │   ├── AppointmentScheduler.jsx
│   │   │   ├── BillingGenerateTab.jsx
│   │   │   ├── BookAppointment.jsx
│   │   │   ├── PatientQueue.jsx
│   │   │   ├── QueuePanel.jsx
│   │   │   └── ScheduleList.jsx
│   │   ├── auth
│   │   │   ├── Login.css
│   │   │   ├── Login.jsx
│   │   │   └── Register.jsx
│   │   ├── billing
│   │   │   ├── BillingAdvance.jsx
│   │   │   ├── BillingPage.jsx
│   │   │   ├── BillView.jsx
│   │   │   ├── creating bill.js
│   │   │   └── Invoice.jsx
│   │   ├── clinic
│   │   │   ├── AddMedicine.jsx
│   │   │   ├── ClinicBilling.jsx
│   │   │   ├── ClinicDashboard.jsx
│   │   │   ├── ClinicHistory.jsx
│   │   │   ├── ExpiredMedicine.jsx
│   │   │   ├── MedicineDispense.jsx
│   │   │   ├── MedicineInventory.jsx
│   │   │   ├── NewPatientClinic.jsx
│   │   │   ├── Patients.jsx
│   │   │   └── StockMedicine.jsx
│   │   ├── dashboard
│   │   │   ├── AdminDashboard.jsx
│   │   │   ├── DoctorDashboard.jsx
│   │   │   └── PatientDashboard.jsx
│   │   ├── doctor
│   │   │   ├── DoctorDashboard.jsx
│   │   │   ├── DoctorHistory.jsx
│   │   │   ├── DoctorReports.jsx
│   │   │   └── PrescriptionCenter.jsx
│   │   ├── lab
│   │   │   ├── add-test.jsx
│   │   │   ├── LabDashboard.jsx
│   │   │   ├── LabReports.jsx
│   │   │   ├── PendingSamples.jsx
│   │   │   ├── tests.jsx
│   │   │   └── UploadReports.jsx
│   │   ├── patient
│   │   │   ├── AddPatient.jsx
│   │   │   ├── PatientList.jsx
│   │   │   └── PatientProfile.jsx
│   │   ├── superadmin
│   │   │   ├── HospitalManagement.jsx
│   │   │   ├── SuperAdminAnalytics.jsx
│   │   │   └── UserAccessManagement.jsx
│   │   ├── 1.jpeg
│   │   ├── Analytics.jsx
│   │   ├── Billing.jsx
│   │   ├── Dashboard.jsx
│   │   ├── EMR.jsx
│   │   ├── Icons.jsx
│   │   ├── Laboratory.jsx
│   │   ├── Landing.jsx
│   │   ├── Patients.jsx
│   │   ├── Pharmacy.jsx
│   │   └── Settings.jsx
│   ├── routes
│   │   └── AppRoutes.jsx
│   ├── services
│   │   ├── adminService.js
│   │   ├── api.js
│   │   ├── appointmentApi.js
│   │   ├── appointmentService.js
│   │   ├── appointmentSocket.js
│   │   ├── authService.js
│   │   ├── billingservice.js
│   │   ├── emrService.js
│   │   ├── labService.js
│   │   ├── mockData.js
│   │   └── patientService.js
│   ├── utils
│   │   └── helpers.js
│   ├── App.css
│   ├── App.js
│   ├── App.jsx
│   ├── index.css
│   ├── main.jsx
│   └── types.js
├── eslint.config.js
├── index.html
├── metadata.json
├── package-lock.json
├── package.json
├── README.md
├── server.js
├── vercel.json
└── vite.config.js


```

---

# 📊 Modules

- Admin Dashboard
- Doctor Dashboard
- Clinic Dashboard
- Appointment Dashboard
- Billing System
- Inventory Management
- Patient Management
- Medicine Management
- Reports & Analytics
- Authentication & Authorization

---

# 🔒 Security

The following files are **NOT** included in this repository:

- Production Backend
- API Keys
- Environment Variables
- Database Credentials
- Authentication Tokens
- Private Configuration Files

These remain securely maintained within the original private repository.

---

# 🚀 Future Improvements

- Online Payments
- Electronic Medical Records (EMR)
- AI-Based Patient Analytics
- SMS & Email Notifications
- Video Consultation
- Prescription Management
- Cloud File Storage
- Audit Logs
- Multi-Hospital Support

---

<p align="center">

⭐ If you found this project useful, consider giving it a star!

</p>

<p align="center">


</p>
