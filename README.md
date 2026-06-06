# Eunoia Pilates Management Platform

![Laravel](https://img.shields.io/badge/Laravel-12.0-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-5.3-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-00758F?style=for-the-badge&logo=mysql&logoColor=white)
![Status](https://img.shields.io/badge/Status-Private-red?style=for-the-badge)

---

[![Visit Live Site](https://img.shields.io/badge/Visit%20Live%20Site-eunoiapilates.net-blue?style=for-the-badge&logo=google-chrome)](https://eunoiapilates.net/)

## 🌟 Executive Summary

**Eunoia** is a premium, high-performance studio management ecosystem specifically engineered for **Eunoia Pilates**. It serves as a comprehensive digital hub for core-focused wellness, managing specialized disciplines including **Mobility & Flexibility**, **Reformer Pilates**, **Mat Pilates**, and **Yoga**. The platform orchestrates the complex logistics of studio scheduling, trainer coordination, and multi-tier subscription models within a visually stunning and highly secure environment.

---

## 🛠 Core Studio Pillars

### 1. Adaptive Booking & Class Scheduling

The system provides two distinct, high-conversion flows for studio engagement:

- **Direct Session Booking:** Users can browse the dynamic weekly schedule and book a specific class at a specific time based on live availability.
- **Subscription Packages:** A flexible e-commerce flow where users purchase multi-session packages (credits) and subsequently reserve their preferred slots based on studio availability and package limitations.

### 2. Multi-Role Studio Infrastructure

The platform implements a strict role-based access control (RBAC) system tailored for studio operations:

- **Global Administrator:** Total operational control, including the management of Services (disciplines), individual Classes, Package Types, Subscriptions, and Product inventory.
- **Certified Studio Trainer:** A specialized interface optimized for tracking attendance and viewing live booking schedules for their assigned sessions.
- **Verified Studio Member:** An intuitive dashboard for tracking class credits, managing future bookings, and reviewing transaction history.

### 3. Integrated E-commerce & Payments

- **Dynamic Subscription Engine:** Automated credit management that handles complex business rules for different package tiers.
- **Studio Retail Marketplace:** A fully featured store for physical studio products with real-time order tracking.
- **Kashier Payment Gateway:** Secure, automated payment processing for both subscriptions and physical products.

---

## 🖥 Administrative Command Center

_Engineered for data-driven studio management and total operational oversight._

### 📊 Business Intelligence & Analytics

- **Live Studio Metrics:** Real-time visualization of class occupancy, revenue trends, and member growth.
- **Data Granularity:** Advanced filtering by Member, Package Type, Service Discipline, or Payment Status.

### 👥 Member Security & Auditing

- **Security Auditing:** Real-time tracking of active sessions, featuring IP tracking and device fingerprinting to ensure member data security.
- **Member Management:** Full control over member accounts, verification status (OTP-based), and attendance history.

### 📅 Resource Orchestration

- **Service CMS:** Centralized management of studio disciplines (Yoga, Pilates, etc.) with localized metadata.
- **Trainer Coordination:** Secure linking of trainers to specific weekly schedules with automated capacity auditing.
- **SEO Optimization:** Integrated management of Meta assets and Open Graph protocols to drive studio visibility.

---

## 🏗 Technical Foundation

### Enterprise Tech Stack

- **Backend:** Laravel 12.0 (Modern architectural standards).
- **Database:** Optimized MySQL schemas with complex relational integrity.
- **Frontend:** Bootstrap 5.3 Framework, Slick Interactive components, and premium Vanilla CSS styling.
- **Security:** CSRF protection, salted hashing, and role-isolated middleware layers.

---

---

## ✨ New Features

The following features were requested to be added to the system:

1. Fix issue where bookings made by the Admin send confirmation emails without the client's details — emails will include full client information when booked by Admin.
2. When cancelling an individual booking, a replacement session must be scheduled from the same Service type only (replacement booking compatible with the Service type).
3. Add an input field for notes on the checkout/payment completion page to capture customer remarks at purchase.
4. When creating a Package, allow selecting either `Mix` or one or more specific Services instead of `Mix` only.
5. Implement a waitlist for fully-booked sessions: send an email when a spot becomes available, send an email when the session ends, and after the session time has elapsed restore the deducted session credit to the user.
6. Add a daily log that shows today's bookings and cancellations to provide a daily operational report of bookings and customer cancellations.
7. Update the Trainer account to display only their own schedule; send an email to the trainer when a session is booked or cancelled.
8. Allow the Admin to purchase a package and enter client details manually without performing a real payment (manual purchase / admin-entered client data).
9. Allow the Admin to edit the remaining session count within orders (manual adjustment of credits inside the order).
10. The Bookings Log page should default to showing data from the start of the current week through the end of the next week for easier default viewing.
11. Add a discount code system (percentage-based discount + redeemable code).
12. Allow Admin to close bookings via timing settings: (time threshold before session to close bookings) + (time threshold before cancellation is allowed) + (enabled/disabled flag).
13. Add a Package Type filter and an `is_active` toggle (active/inactive) on the Admin Packages management page.
14. Allow users to select/change the number of participants when booking (within availability), and allow decreasing the number after booking from the booking details page or by cancelling the booking.

---

## 📸 System Gallery

<img src="./screen/1.png" width="100%" alt="screen 1" />

---

<img src="./screen/2.png" width="100%" alt="screen 2" />

---

<img src="./screen/3.png" width="100%" alt="screen 3" />

---

<img src="./screen/4.png" width="100%" alt="screen 4" />

---

<img src="./screen/5.png" width="100%" alt="screen 5" />

---

<img src="./screen/6.png" width="100%" alt="screen 6" />
