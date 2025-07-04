# What is Requirement Analysis?

This repository is part of the ALX Pro Dev program. It focuses on understanding the process of requirement analysis in building successful software applications.


## Why is Requirement Analysis Important?

Requirement analysis is a crucial phase in the Software Development Life Cycle (SDLC). Here are three key reasons why it is essential:

1. **Clarity and Understanding**  
   It helps ensure that all stakeholders—including developers, clients, and users—clearly understand what the software is expected to do, reducing confusion and miscommunication.

2. **Reduced Development Costs**  
   Identifying and resolving issues early in the planning phase is far less costly than fixing them later in development or after deployment.

3. **Improved Project Success Rate**  
   Well-defined and analyzed requirements provide a strong foundation for planning, designing, and implementing the software, increasing the likelihood of delivering a successful, high-quality product.


## Key Activities in Requirement Analysis

The requirement analysis phase involves several key activities that ensure a thorough understanding of what the software should do:

- **Requirement Gathering**  
  This involves collecting information from stakeholders to understand their needs, expectations, and problems the software must solve.

- **Requirement Elicitation**  
  Techniques like interviews, surveys, and observations are used to extract detailed and relevant requirements from stakeholders.

- **Requirement Documentation**  
  All gathered and elicited requirements are organized and written down clearly in structured formats such as requirement specification documents.

- **Requirement Analysis and Modeling**  
  Requirements are analyzed for feasibility, consistency, and completeness. Models like data flow diagrams or use case diagrams may be created.

- **Requirement Validation**  
  The documented requirements are reviewed and confirmed by stakeholders to ensure they reflect the actual needs and are ready for design and development.



## Types of Requirements

### Functional Requirements

Functional requirements describe the core functions and features that the booking management system must perform. These define **what the system should do**.

Examples:
- Users must be able to create an account and log in to the system.
- Admins should be able to add, update, or remove hotel or property listings.
- The system should allow users to search and filter available bookings by location, date, and type.
- Users must receive confirmation emails after a successful booking.
- The system must provide users with the option to cancel or reschedule their bookings.

### Non-functional Requirements

Non-functional requirements describe **how** the system should perform and the qualities it should have. These include performance, security, and usability aspects.

Examples:
- The system should load search results in under 2 seconds.
- User data must be encrypted to ensure privacy and security.
- The platform should be available 99.9% of the time throughout the year.
- The interface must be responsive and work seamlessly on mobile, tablet, and desktop devices.
- The system must support at least 10,000 concurrent users during peak hours.



## Use Case Diagrams

Use case diagrams are visual representations of the interactions between users (actors) and a system. They help identify the **functional requirements** by showing what users can do with the system. These diagrams provide a clear and simple way to understand the scope of the system and its key functionalities.

### Benefits of Use Case Diagrams:
- Clarify system requirements early in development
- Communicate user expectations and system behavior
- Provide a high-level view of the system for stakeholders
- Serve as a guide for development and testing

### Booking System – Use Case Diagram

![Booking Use Case Diagram](alx-booking-uc.png)




## Acceptance Criteria

Acceptance Criteria are a set of conditions that a software product must satisfy to be accepted by a user, customer, or other stakeholders. In Requirement Analysis, they help ensure that all stakeholders agree on the behavior and expectations of a specific feature before development begins.

### Why Acceptance Criteria Matter:
- Define clear and testable goals for features
- Prevent misunderstandings between developers and stakeholders
- Serve as the basis for writing test cases
- Support Agile and iterative development

### Example: Checkout Feature – Booking Management System

**Feature:** Checkout

**Acceptance Criteria:**
- The user must be able to review selected booking details before proceeding to payment.
- The system should allow the user to choose a preferred payment method (e.g., card, mobile money).
- The payment process must be secure and confirm the transaction within 5 seconds.
- The user must receive a booking confirmation page and email after successful checkout.
- If payment fails, the system should display an appropriate error message and allow retry.


