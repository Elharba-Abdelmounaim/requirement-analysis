# requirement-analysis
A repository for documenting the requirement analysis phase in software development
# Requirement Analysis in Software Development

This repository is dedicated to exploring the Requirement Analysis phase in the software development lifecycle.

It includes documentation, templates, and examples that help identify, analyze, and document software requirements effectively. This phase is crucial for ensuring that the software meets stakeholder expectations and business needs.
## What is Requirement Analysis?

Requirement Analysis is a critical phase in the Software Development Life Cycle (SDLC) that focuses on identifying, gathering, analyzing, and documenting the functional and non-functional requirements of a software system.

It involves close communication between stakeholders—including clients, end-users, business analysts, and developers—to ensure that the software being built aligns with business goals and user needs.

### Why is Requirement Analysis Important?

- **Defines the Scope:** It helps determine what needs to be developed, avoiding scope creep and ambiguity.
- **Reduces Risk:** Clear requirements prevent costly misunderstandings and rework later in the development process.
- **Improves Communication:** Acts as a reference point for developers, testers, and project managers.
- **Ensures Quality:** Establishing accurate requirements early contributes to building reliable, user-friendly software.
- **Supports Planning:** Requirements help in estimating costs, timelines, and resource needs effectively.

### Key Activities in Requirement Analysis:

- **Requirement Elicitation:** Collecting requirements through interviews, surveys, observations, or workshops.
- **Requirement Specification:** Writing clear, detailed, and unambiguous requirement documents.
- **Requirement Validation:** Ensuring the requirements are complete, consistent, and feasible.
- **Requirement Management:** Tracking changes and updates to requirements throughout the project lifecycle.

Without a solid requirement analysis phase, the success of a software project is significantly compromised. It lays the foundation for all subsequent design, development, and testing efforts.

## Why is Requirement Analysis Important?

Requirement Analysis plays a foundational role in the success of any software development project. Here are three key reasons why it is essential in the Software Development Life Cycle (SDLC):

### 1. Prevents Misunderstandings and Reduces Rework
By clearly documenting what the client wants, requirement analysis ensures that all stakeholders are on the same page. This minimizes the chances of building incorrect features and helps avoid costly revisions during later stages of development.

### 2. Improves Project Planning and Estimation
Well-defined requirements make it easier to estimate project timelines, resource needs, and budget. This leads to more realistic planning and helps teams avoid delays and unexpected costs.

### 3. Enhances Product Quality and User Satisfaction
When software is built based on accurate and complete requirements, it is more likely to meet user expectations and business goals. This leads to higher user satisfaction and reduces the need for post-launch fixes.

Effective requirement analysis is not just a preliminary step—it is a continuous process that guides the entire development lifecycle and increases the chances of project success.
## Key Activities in Requirement Analysis

The Requirement Analysis phase involves several critical activities that ensure the project starts with a clear understanding of what needs to be built. Here are the five key activities:

- **Requirement Gathering**  
  This is the initial step where stakeholders such as clients, users, and subject matter experts are identified, and their expectations are collected. Techniques like interviews, questionnaires, and surveys are often used.

- **Requirement Elicitation**  
  Elicitation focuses on drawing out the actual requirements from stakeholders, often through workshops, brainstorming sessions, and observation. It aims to uncover needs that may not be initially expressed.

- **Requirement Documentation**  
  All gathered and elicited requirements are documented clearly and systematically. This documentation acts as a
## Types of Requirements

In software development, requirements are generally categorized into two main types: Functional and Non-functional. Understanding the distinction between them is essential for building a system that meets user needs and performs reliably.

### Functional Requirements

Functional requirements describe **what the system should do**. They define specific behaviors, features, or functions that the software must perform.

**Examples for Booking Management Project:**
- The system shall allow users to create a new booking for a hotel room or flight.
- Users shall be able to cancel or modify their existing bookings.
- The system shall send confirmation emails to users after successful booking.
- Admins shall be able to view, update, and delete bookings.
- The system shall allow users to filter available rooms by date, location, and price range.

### Non-functional Requirements

Non-functional requirements describe **how the system performs** its functions. They relate to quality attributes such as performance, usability, reliability, and security.

**Examples for Booking Management Project:**
- The system shall respond to booking requests within 2 seconds under normal load.
- The application shall be available 99.9% of the time (high availability).
- The user interface shall support both English and French languages.
- The system shall handle at least 10,000 concurrent users without crashing.
- All user data shall be encrypted in transit and at rest for security compliance.

## Use Case Diagrams

Use Case Diagrams are a type of Unified Modeling Language (UML) diagram used during Requirement Analysis to visualize the interactions between users (actors) and the system. They help stakeholders understand how users will interact with the system and what functionalities the system must support.

### 🔍 Benefits of Use Case Diagrams:
- Provide a high-level overview of the system functionality.
- Help identify system boundaries and interactions.
- Enhance communication between stakeholders, developers, and testers.
- Serve as a foundation for writing detailed use cases and test cases.
## Acceptance Criteria

Acceptance Criteria are specific conditions or requirements that a product or feature must satisfy to be accepted by the user, client, or stakeholders. They act as a checklist that clearly defines when a feature is "done" and ensures that all team members have a common understanding of the scope and expected outcomes.

### 📌 Importance of Acceptance Criteria:
- Clarify functionality and business rules before development starts.
- Help avoid misunderstandings between developers, testers, and stakeholders.
- Serve as the basis for writing test cases.
- Ensure that requirements are testable and verifiable.

### ✅ Example: Acceptance Criteria for the Checkout Feature

**Feature**: Checkout in the Booking Management System

**Acceptance Criteria:**
- ✅ The user must be able to review selected items (e.g., hotel room or flight) before confirming the checkout.
- ✅ The checkout page must display the total price, taxes, and fees clearly.
- ✅ The user must be able to enter and save payment information securely.
- ✅ A confirmation email must be sent upon successful checkout.
- ✅ The booking should appear under the user’s profile immediately after checkout.
- ✅ If payment fails, an appropriate error message should be displayed and no booking should be created.


### 🧩 Use Case Diagram for the Booking System

The following diagram illustrates the main actors and use cases involved in a hotel/flight booking system.

![Use Case Diagram for Booking System](alx-booking-uc.png)
