# Labour Ekta - Android Application (Kotlin)

**Labour Ekta** is a comprehensive Android application built using Kotlin that connects admins, operators, and companies to manage job campaigns, vehicle bookings, user profiles, and generate certificates and invoices. It focuses on a seamless user experience with secure OTP-based login and efficient backend integration.

---

## 🧩 Key Features

### 🔐 OTP-Based Registration & Login
- Secure login system using OTP (One-Time Password) authentication.
- Users must verify OTP before accessing the full registration form (company/operator details).

### 📢 Campaign Management
- Admins can create, edit, and manage campaigns.
- All active campaigns are visible to users in the mobile app.

### 👤 Profile Management
- Users can edit their profile (except name, email, and phone number for consistency).

### 📄 Certificates & Invoices
- Automatic generation of certificates for all users.
- Users can download their certificates within the app.
- Invoices are generated for membership payments and donations.

### 🚚 Vehicle Booking System
- Admins can list vehicles for booking.
- Operators and companies can book available vehicles.
- Admin panel receives booking details along with user contact info.

### 🛠 Bug Fixes and Improvements
- Fixed splash screen rendering issues.
- Resolved complaints and tracking bugs.
- Fixed job detail display on Home and Job Details screens.
- Proper handling of job applications:
  - Submits successfully
  - Sends notification email
  - Makes job visible to admins
- Push/email notifications for new jobs.
- Overall app performance enhanced.

---

## 🛠 Tech Stack

- **Language:** Kotlin
- **Platform:** Android (Native)
- **Backend:** (Node.js/Express assumed, not part of this repo)
- **Authentication:** OTP-based (via Firebase or SMS API)

---

## 📁 Project Structure

