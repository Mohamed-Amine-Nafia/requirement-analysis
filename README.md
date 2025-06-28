# requirement-analysis
## 📄 Introduction

Welcome to the **Requirement Analysis in Software Development** repository.

This repository is created to provide a clear understanding of how requirement analysis is performed in the software development life cycle (SDLC). It includes explanations, examples, templates, and documentation that showcase the importance of gathering, analyzing, and documenting requirements before starting the development process.

The purpose of this repository is to help developers, students, and stakeholders understand how to capture functional and non-functional requirements effectively to ensure the success of software projects.

## ❓ What is Requirement Analysis?

**Requirement Analysis** is the process of gathering, analyzing, and defining what a software system should do based on stakeholder needs. It helps ensure the final product meets user expectations and business goals.

## ⚠️ Why is Requirement Analysis Important?

1. **Ensures Clear Understanding**  
   It helps all stakeholders have a shared and clear understanding of what the software should do, reducing confusion and miscommunication.

2. **Reduces Risks and Costs**  
   Identifying requirements early prevents costly changes and rework during later stages of development.

3. **Improves Project Planning**  
   Accurate requirements enable better estimation of time, resources, and budget, leading to more efficient project management.

   ## 🔑 Key Activities in Requirement Analysis

- **Requirement Gathering**  
  Collecting initial information from stakeholders about what the system should do.

- **Requirement Elicitation**  
  Engaging with stakeholders through interviews, surveys, and workshops to uncover detailed needs and expectations.

- **Requirement Documentation**  
  Recording all gathered requirements clearly in structured documents like the Software Requirements Specification (SRS).

- **Requirement Analysis and Modeling**  
  Analyzing requirements to detect conflicts, gaps, or ambiguities and representing them using diagrams, models, or workflows.

- **Requirement Validation**  
  Reviewing requirements with stakeholders to ensure accuracy, completeness, and agreement before development begins.

## 🗂️ Types of Requirements

### 🔹 Functional Requirements

Functional requirements define **what the system should do** — the core features and functions.

**Examples for the Booking Management Project:**
- Allow users to create new bookings for services.
- Enable users to view, edit, or cancel existing bookings.
- Send booking confirmation emails to customers.
- Provide administrators with the ability to manage bookings (add, update, delete).
- Generate reports for all booking activities.

---

### 🔸 Non-Functional Requirements

Non-functional requirements define **how the system should perform** — qualities, constraints, and standards.

**Examples for the Booking Management Project:**
- The system should load the booking page within **2 seconds**.
- Support **up to 1,000 concurrent users** without performance degradation.
- Ensure **99.9% uptime** for the booking platform.
- All user data and bookings must be protected with **end-to-end encryption**.
- The user interface should be responsive and accessible on **desktop, tablet, and mobile devices**.

## 🗺️ Use Case Diagrams

### 📌 What are Use Case Diagrams?

A **Use Case Diagram** visually represents the interactions between users (**actors**) and the system. It shows the different functionalities (use cases) that the system offers and who can perform them.

### ✅ Benefits of Use Case Diagrams:
- Provides a clear overview of system functionality.
- Helps identify system boundaries and user interactions.
- Improves communication between developers, stakeholders, and users.
- Useful for requirement validation and analysis.

---

### 🎨 Use Case Diagram for the Booking System

alx-booking-uc.png
![Image](https://github.com/user-attachments/assets/de151ae7-3734-40ea-86cc-20e9b8359d3a)


### 👥 **Actors:**
- **Customer** – Books services, manages their bookings.
- **Administrator** – Manages bookings, customers, and generates reports.

### 🏷️ **Use Cases:**
- Create Booking
- View Booking
- Edit Booking
- Cancel Booking
- Receive Confirmation
- Manage Bookings
- Manage Customers
- Generate Reports

## Acceptance Criteria

Acceptance Criteria play a crucial role in Requirement Analysis by defining the specific conditions that a feature or system must satisfy to be accepted by stakeholders. They provide clear, testable requirements that guide developers and testers, ensuring that the delivered functionality meets the expected behavior and business needs. Well-defined acceptance criteria help prevent misunderstandings, scope creep, and rework by setting precise expectations upfront.

### Example: Acceptance Criteria for Checkout Feature in Booking Management System

- The user must be able to review their booking details (dates, number of guests, price) before proceeding.
- The system should calculate and display the total price including taxes and fees.
- Users must be able to enter valid payment information (credit card, debit card, or digital wallet).
- The checkout process should validate payment details and reject invalid or expired cards.
- Upon successful payment, the system must generate a booking confirmation and send a confirmation email to the user.
- If payment fails, an appropriate error message should be displayed, and the user must be able to retry the payment.
- The checkout process should complete within 10 seconds under normal network conditions.
- The feature must comply with applicable security standards (e.g., PCI-DSS) to protect payment data.

These criteria help ensure the checkout feature is functional, user-friendly, secure, and reliable.


