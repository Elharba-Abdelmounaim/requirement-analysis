# 📘 Requirement Analysis in Software Development

This repository is dedicated to exploring the **Requirement Analysis** phase in the Software Development Life Cycle (SDLC).  
It includes documentation, templates, and examples that help identify, analyze, and document software requirements effectively.

---

## 📌 What is Requirement Analysis?

**Requirement Analysis** is a critical phase in the SDLC that focuses on identifying, gathering, analyzing, and documenting the functional and non-functional requirements of a software system.

It involves close collaboration between stakeholders (clients, users, analysts, and developers) to ensure the final product aligns with business goals and user needs.

---

## ❓ Why is Requirement Analysis Important?

Requirement Analysis plays a foundational role in the success of any software development project.  
Here are three key reasons why it's essential in the SDLC:

1. ✅ **Prevents Misunderstandings and Reduces Rework**  
   Clear documentation ensures all stakeholders share the same vision, reducing incorrect features and costly rework.

2. 🕒 **Improves Project Planning and Estimation**  
   Well-defined requirements allow for accurate time, cost, and resource estimation.

3. 🎯 **Enhances Product Quality and User Satisfaction**  
   Accurate requirements ensure the product meets business needs and user expectations, leading to fewer bugs and greater satisfaction.

---

## 🔑 Key Activities in Requirement Analysis

The Requirement Analysis phase includes the following five critical activities:

- 🔍 **Requirement Gathering**  
  Collect expectations from stakeholders using interviews, questionnaires, and observations.

- ✏️ **Requirement Elicitation**  
  Explore hidden or implicit needs through brainstorming, workshops, and analysis.

- 📝 **Requirement Documentation**  
  Systematically record all gathered and elicited requirements for reference and traceability.

- 🧠 **Requirement Analysis and Modeling**  
  Analyze requirements for completeness, consistency, and feasibility, often using models like UML.

- ✅ **Requirement Validation**  
  Review and validate requirements with stakeholders to ensure accuracy and completeness.

---

## 🧩 Types of Requirements

In software development, requirements are categorized into:

### ✅ Functional Requirements

Define **what the system should do** (features, services, and behavior).

**Examples (Booking Management System):**
- Users can book hotel rooms or flights.
- Users can cancel or modify bookings.
- Admins can manage all bookings.
- Confirmation emails are sent after successful bookings.
- Users can filter rooms by date, price, and location.

### ⚙️ Non-functional Requirements

Define **how the system should behave** (quality attributes).

**Examples:**
- System must respond within 2 seconds under normal load.
- 99.9% uptime availability.
- Interface supports English and French.
- Handles 10,000 concurrent users.
- All data is encrypted in transit and at rest.

---

## 🎯 Use Case Diagrams

Use Case Diagrams (UML) visually represent how users interact with the system. They help define functional scope and clarify system behavior.

### 🔍 Benefits of Use Case Diagrams:
- Provide a high-level system overview.
- Define user interactions clearly.
- Help communicate requirements with stakeholders.
- Serve as a base for test case creation.

### 🧩 Use Case Diagram – Booking System

The following diagram shows the main actors and interactions in the booking system:

![Use Case Diagram for Booking System](alx-booking-uc.png)

> ℹ️ *Diagram includes: User, Admin, Booking Use Cases (Create, Cancel, Modify, View Bookings, Checkout, etc.)*

---

## 📋 Acceptance Criteria

**Acceptance Criteria** define specific conditions under which a feature is considered complete and accepted by stakeholders. They serve as the “definition of done”.

### 📌 Why Acceptance Criteria Matter:
- Clarify feature scope and business rules.
- Align understanding across the team.
- Basis for test case creation.
- Ensure deliverables are testable and verifiable.

### ✅ Example – Checkout Feature

**Feature:** Booking Checkout

**Acceptance Criteria:**
- ✅ User can review booking before confirmation.
- ✅ Total price, taxes, and fees are displayed clearly.
- ✅ User can securely enter and save payment details.
- ✅ Confirmation email is sent after successful checkout.
- ✅ Booking appears in the user's profile instantly.
- ✅ Failure in payment displays appropriate error and cancels booking.

---

## 📎 Conclusion

Requirement Analysis is the foundation of successful software.  
It helps teams build the right product, reduces risks, and ensures that user expectations are met from day one.

