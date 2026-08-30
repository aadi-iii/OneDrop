

# 🩸 OneDrop

<div align="center">

### A Smart Blood Donation & Request Management Platform

Connecting **Donors**, **Receivers**, and **Administrators** through a centralized digital platform.

## 🌐 Live Website

# 🚀 [https://1drop4u.online/](https://1drop4u.online/)

[📂 View Source Code](https://github.com/aadi-iii/OneDrop)

</div>

---

## 📌 About OneDrop

**OneDrop** is a web-based Blood Donation and Blood Request Management Platform designed to simplify and organize the process of connecting blood donors with people who require blood.

Instead of relying completely on phone calls, personal contacts, and social media posts, OneDrop provides a centralized platform where users can manage blood requests, donor responses, donation records, certificates, and verification processes.

The platform supports multiple user roles and provides dedicated functionality for **Donors, Receivers, and Administrators**.

---

## ✨ Key Features

### 🏠 Modern Landing Page

- Interactive and responsive user interface
- Separate entry points for donating blood and finding blood
- Light and Dark mode support
- Responsive design for desktop and mobile devices

### 🔐 Authentication System

- User Registration
- Secure Login
- Firebase Authentication integration
- Role-based access

### 🩸 Donor Features

- Donor Dashboard
- View available blood requests
- Accept suitable blood requests
- Manage profile information
- View donation history
- Access donation certificates
- Check notifications
- View Blood Bank information
- Blood compatibility information

### ❤️ Receiver Features

- Receiver Dashboard
- Create blood requests
- Manage active blood requirements
- View donor responses
- Track request status
- Confirm donation completion

### 🛡️ Admin Features

- Admin Dashboard
- Manage users
- Monitor blood requests
- Manage donation records
- Verify completed donations
- Manage Blood Bank information
- Monitor platform activity

### 📜 Digital Donation Certificates

OneDrop provides digital certificates for verified blood donations.

Certificate functionality includes:

- Unique certificate information
- Donor details
- Blood group information
- Donation details
- Issue information
- QR-based verification support

### 🔍 QR Certificate Verification

The platform includes a certificate verification system that allows certificate-related information to be checked through the implemented verification workflow.

### 🏥 Blood Bank Information

Users can access Blood Bank-related information through the platform, keeping relevant supporting information available in one centralized system.

### 📊 Donation History

Donors can view completed donation records in an organized format, including relevant details such as blood group, donation date, receiver or hospital information, location, donation status, and certificate availability.

### 🔔 Notifications

The application includes notification and status-based updates to help users stay informed about important workflow changes.

### 📱 Fully Responsive Design

OneDrop is designed to work across:

- 💻 Desktop
- 💼 Laptop
- 📱 Mobile Devices
- 📟 Tablets

---

## 👥 User Roles

### 🩸 Donor

Donors can:

- Manage their profile
- Browse blood requests
- Accept requests
- Track donation activity
- View donation history
- Access certificates

### ❤️ Receiver

Receivers can:

- Create blood requests
- Manage active requests
- View donor responses
- Track request progress
- Confirm donation completion

### 🛡️ Administrator

Administrators can:

- Manage users
- Monitor blood requests
- Review donation records
- Verify completed donations
- Manage Blood Bank information
- Supervise platform activity

---

## 🔄 System Workflow

```text
Receiver Creates Blood Request
            │
            ▼
Request Stored in Database
            │
            ▼
Donors View Available Requests
            │
            ▼
Donor Accepts Request
            │
            ▼
Receiver Receives Donor Information
            │
            ▼
Blood Donation Takes Place
            │
            ▼
Receiver Confirms Completion
            │
            ▼
Admin Verifies Donation
            │
            ▼
Donation Record Updated
            │
            ▼
Digital Certificate Generated


                 ┌───────────────────┐
                 │     OneDrop       │
                 │   Web Platform    │
                 └─────────┬─────────┘
                           │
          ┌────────────────┼────────────────┐
          │                │                │
          ▼                ▼                ▼
       Donor           Receiver           Admin
          │                │                │
          └────────────────┼────────────────┘
                           │
                           ▼
                   Firebase Services
                           │
              ┌────────────┴────────────┐
              │                         │
              ▼                         ▼
     Firebase Authentication      Cloud Firestore
              │                         │
              └────────────┬────────────┘
                           │
                           ▼
                    Application Data


🛠️ Technologies Used
Frontend
HTML5
CSS3
JavaScript
Backend & Cloud Services
Firebase Authentication
Cloud Firestore
Development & Deployment
Visual Studio Code
Git
GitHub
GitHub Pages
🗂️ Main Functional Modules
Module	Description
🏠 Landing Page	Main entry point of the platform
🔐 Authentication	Registration and login system
🩸 Donor Dashboard	Donor-specific features and requests
❤️ Receiver Dashboard	Blood request creation and management
🛡️ Admin Dashboard	System monitoring and management
🔎 Blood Search	Finding suitable donor information
📝 Blood Requests	Creation and tracking of blood requirements
📊 Donation History	Record of completed donations
📜 Certificates	Digital donation certificates
🔍 QR Verification	Certificate verification workflow
🏥 Blood Banks	Blood Bank information
🔔 Notifications	Workflow and status updates
🔥 Firebase Integration
Firebase Authentication

Used for:

User Registration
Login
Account Management
User Authentication
Cloud Firestore

Used for storing and managing:

User Profiles
Role Information
Blood Requests
Donation Records
Notifications
Blood Bank Information
Certificate-related Records

⚠️ Disclaimer

OneDrop is developed as an academic project. The current version demonstrates the implementation of a web-based blood donation and request management workflow.

A production-level healthcare platform would require additional security, privacy, verification, compliance, and institutional integration measures.

👨‍💻 Developer

Aditya Sharma

GitHub: @aadi-iii

<div align="center">
🩸 Donate Blood. Save Lives. ❤️
OneDrop

⭐ If you like this project, consider giving the repository a star!

</div> ```
            │
            ▼
Certificate Can Be Verified
