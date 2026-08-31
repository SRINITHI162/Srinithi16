# 🎬 Movie Ticket Booking Management Application

## 📌 Project Overview

The **Movie Ticket Booking Management Application** is a workflow-based application developed using **Pega Platform™** as part of the **National Internship Program (NIP) – Pega Academy 2026**.

The application is designed to digitize and streamline the movie ticket booking process. It manages the complete booking lifecycle, starting from the customer's booking request and continuing through availability verification, booking cost calculation, customer confirmation, ticket processing, and booking notification.

The application aims to reduce manual processing, improve booking visibility, ensure accurate information handling, and provide a smooth experience for customers and booking staff.

---

## 🎯 Project Objectives

The main objectives of the application are:

- Allow customers to submit movie ticket booking requests.
- Capture and validate movie, show, and ticket information.
- Verify show and seat availability before proceeding with booking.
- Calculate the total booking cost automatically.
- Allow customers to confirm or cancel booking requests.
- Maintain reusable movie and show information.
- Process ticket bookings and allocate seats.
- Generate and maintain booking-related information.
- Notify customers after successful booking confirmation.
- Define SLA-based processing timelines.
- Route booking requests to appropriate work queues based on show type.

---

## 🔄 Case Type

### Movie Ticket Request

The application uses **Movie Ticket Request** as the primary case type.

The case represents the complete end-to-end movie ticket booking process.

### Case Lifecycle

```text
Booking Request
       ↓
Availability
       ↓
Approval
       ↓
Booking Execution
       ↓
Booking Confirmation
