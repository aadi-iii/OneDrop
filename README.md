# 🩸 OneDrop

> Saving Lives, One Drop at a Time.

OneDrop is a modern blood donation management platform designed to connect **Donors, Receivers, Blood Banks, and Administrators** through a centralized and user-friendly web application.

The platform simplifies the blood donation process by enabling users to request blood, connect with suitable donors, track donation workflows, verify completed donations, and generate donation certificates.

🌐 **Live Website:** https://aadi-iii.github.io/OneDrop/

---

## ✨ Features

### 🔐 Authentication & User Roles

- Firebase Authentication
- Secure Login and Signup
- Password Reset
- Role-based access for:
  - 🩸 Donor
  - 🆘 Receiver
  - 🛡️ Admin

---

### 🩸 Donor Features

- Personalized Donor Dashboard
- View and manage blood donation requests
- Accept suitable blood requests
- View receiver details
- Contact receivers through available communication options
- Track completed donations
- Complete Donation History
- View donation details
- Download donation certificates
- View registered Blood Banks

---

### 🆘 Receiver Features

- Personalized Receiver Dashboard
- Create blood requests
- Manage active requests
- Receive donor acceptance notifications
- View donor details
- Contact donors
- Confirm successful blood donation
- View registered Blood Banks

---

### 🛡️ Admin Features

- Dedicated Admin Dashboard
- User Management
- Donor and Receiver Management
- Blood Request Management
- Blood Bank Management
- Donation Verification Workflow
- Review completed donation requests
- Verify donation completion
- Manage application data through Firestore

---

## 🏥 Blood Bank Integration

- Admin can add and manage Blood Bank information
- Blood Bank data is stored in Cloud Firestore
- Donors can view registered Blood Banks
- Receivers can view registered Blood Banks
- Centralized Blood Bank information across the platform

---

## 🔔 Donation Workflow

```text
Receiver Creates Blood Request
            ↓
Donor Accepts Request
            ↓
Receiver Receives Donor Information
            ↓
Receiver Confirms Donation
            ↓
Admin Receives Confirmation
            ↓
Admin Verifies Donation
            ↓
Certificate Becomes Available to Donor

📜 Donation Certificates

Dynamic Blood Donation Certificate Generation
Unique Certificate ID
Donor and donation details
Donation verification status
QR Code integration
Certificate verification page
Certificate download functionality
Responsive certificate layout for desktop and mobile devices

🔍 QR Certificate Verification

QR Code generated for donation certificates
QR directs users to the certificate verification system
Verification page displays relevant certificate information
Helps validate donation certificates

📊 Donation History

Donors can access their completed donation records.

Donation History includes:

Receiver information
Blood Group
Donation Date
Donation Location
Donation Status
Certificate access for completed donations

🎨 User Interface

Modern Light Theme
Custom color palette
Glassmorphism-inspired UI elements
Smooth animations and transitions
Responsive design
Optimized layouts for:
Desktop
Tablet
Mobile
📍 Contact & Location
Dedicated Contact Page
Contact information and support section
Embedded location map for Ghaziabad
Responsive map integration

🛠️ Tech Stack

Frontend
HTML5
CSS3
JavaScript
Backend & Database
Firebase Authentication
Cloud Firestore
Deployment
GitHub Pages
Tools
Git
GitHub
VS Code

📁 Project Structure

OneDrop/
│
├── index.html
├── login.html
├── signup.html
├── forgot-password.html
├── donor-dashboard.html
├── receiver-dashboard.html
├── admin.html
├── contact.html
├── verify.html
├── firestore.rules
├── favicon.svg
│
├── assets/
│
└── README.md
🚀 Project Status

🟢 Completed

The core features of the OneDrop platform have been implemented, including:

Authentication
Role-based dashboards
Blood request management
Donor and receiver workflow
Notifications
Donation confirmation
Admin verification
Blood Bank integration
Donation History
Certificate generation
QR-based certificate verification
Responsive user interface

Future improvements may include advanced analytics, enhanced reporting, and additional scalability features.

🎯 Project Goal

The objective of OneDrop is to make blood donation management more organized, accessible, transparent, and efficient through an easy-to-use digital platform.

By connecting donors, receivers, administrators, and blood banks in one system, OneDrop aims to improve the overall blood donation coordination process.

👨‍💻 Developer

Aditya Sharma

🌐 Live Demo

Visit the live project:

https://aadi-iii.github.io/OneDrop/
