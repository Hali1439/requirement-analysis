# requirement-analysis
# Requirement Analysis in Software Development

## 📘 Introduction

This repository is part of the **FeatureForge: Crafting Your Project Blueprint** project from the ALX ProDev program. It focuses on mastering the process of **requirement analysis**—a critical phase in the Software Development Life Cycle (SDLC).

The purpose of this repository is to:
- Define and document the functional and non-functional requirements of a **Booking Management System**.
- Analyze the system from a user and business perspective.
- Create use case diagrams and acceptance criteria.
- Apply best practices to simulate a real-world requirement engineering process.

All tasks will be documented in structured Markdown files and diagrams to reflect industry standards.

## 🧠 What is Requirement Analysis?
Requirement Analysis is a critical phase in the Software Development Life Cycle (SDLC) that involves gathering, interpreting, and defining the needs and expectations of stakeholders for a software project. It serves as the foundation for designing, developing, testing, and delivering a successful system.

During this phase, software engineers, business analysts, and project managers work collaboratively with stakeholders—such as clients, users, and domain experts—to clearly understand what the system must do (functional requirements) and how it should perform (non-functional requirements).

### 🔍 Why Requirement Analysis Matters
✅ Clarifies Scope: It eliminates ambiguity by clearly defining what needs to be built and avoids feature creep later in the development process.

✅ Aligns Expectations: Ensures that both developers and stakeholders are on the same page before any code is written.

✅ Reduces Rework: Identifying issues early saves time and resources that would otherwise be spent fixing misunderstood requirements.

✅ Guides Design & Development: All architectural and technical decisions stem from well-defined requirements.

✅ Improves Quality: With clearly documented requirements, developers can build features that directly address user needs, improving usability and satisfaction.

## 📌 Why is Requirement Analysis Important?

Requirement Analysis is one of the most critical stages in the Software Development Life Cycle (SDLC). It ensures the success of a software project by defining clear goals and aligning all stakeholders. Below are three key reasons why it matters:

### 1. ✅ Prevents Miscommunication and Misalignment
Clearly defined requirements help developers, stakeholders, and users stay on the same page. This minimizes assumptions, prevents confusion, and ensures that the project scope is understood and agreed upon from the beginning.

### 2. 🛠️ Reduces Development Costs and Rework
By identifying what is needed early, teams can avoid costly changes later in development. Solid requirement analysis reduces unnecessary features, last-minute changes, and rework that delay timelines and inflate budgets.

### 3. 🚀 Ensures Delivery of a Useful, User-Centric Product
Requirements focused on real user needs lead to features that provide genuine value. This boosts user satisfaction, improves product usability, and increases the overall success rate of the software.

## 🧩 Key Activities in Requirement Analysis

Requirement Analysis involves a series of structured activities that help ensure the system being built meets both user needs and business goals. Below are the five key activities involved:

- **Requirement Gathering**
  - Involves collecting information from stakeholders (e.g., clients, users, business analysts).
  - Sources include interviews, surveys, existing documentation, and observation.
  - Goal: Understand the problem space and business context.

- **Requirement Elicitation**
  - Focuses on drawing out hidden, implicit, or non-obvious needs from stakeholders.
  - Techniques include brainstorming, workshops, focus groups, and use case analysis.
  - Ensures nothing critical is overlooked early in the process.

- **Requirement Documentation**
  - Captures all gathered and elicited requirements in a clear, structured format.
  - Typically documented in Software Requirement Specification (SRS) or user stories.
  - Acts as the official reference for all teams involved.

- **Requirement Analysis and Modeling**
  - Involves refining, prioritizing, and organizing requirements for clarity and feasibility.
  - Includes identifying dependencies, conflicts, and modeling use cases, workflows, or diagrams.
  - Tools: Use case diagrams, flowcharts, UML diagrams.

- **Requirement Validation**
  - Verifies that the documented requirements truly reflect stakeholder needs.
  - May involve reviews, walkthroughs, prototypes, or feedback sessions.
  - Ensures that requirements are accurate, complete, and testable before development begins.

## 🧮 Types of Requirements

In software engineering, requirements are typically categorized into two main types: **Functional** and **Non-functional**. Both are essential to define what a system should do and how it should perform.

---

### ✅ Functional Requirements

Functional requirements describe the **specific features, behaviors, and functions** of a system. They define **what** the system should do to meet business needs.

#### Examples from the Booking Management System:
- Users (customers/managers) can create and authenticate accounts.
- Customers can search for hotels using filters (location, price, amenities).
- Hotel managers can list, update, or delete properties.
- Customers can book available rooms with check-in/check-out dates.
- The system processes secure payments via third-party payment gateways.
- Users can view current and past bookings in their dashboard.

---

### ⚙️ Non-functional Requirements

Non-functional requirements describe **how** the system performs its functions. These are system qualities such as performance, security, scalability, and maintainability.

#### Examples from the Booking Management System:
- The system must handle **up to 10,000 concurrent users** without performance degradation.
- **Response time** for search results must be less than 1.5 seconds.
- System data must be **replicated across regions** for high availability.
- Booking records older than 1 year must be **archived using Cassandra** for optimized querying.
- Use **Redis** for caching frequently accessed data to improve performance.
- The application must comply with **payment security standards (e.g., PCI-DSS)**.
- **99.9% uptime** required to ensure platform availability.

## 🎯 Use Case Diagrams

A **Use Case Diagram** is a type of UML (Unified Modeling Language) diagram that visually represents the **functional interactions** between users (actors) and a system. It is commonly used in the Requirement Analysis phase to clarify the system’s intended behavior and scope from a user perspective.

### 📈 Benefits of Use Case Diagrams:
- Helps stakeholders quickly understand **how users will interact** with the system.
- Clearly defines **system boundaries** and user roles.
- Identifies key **features and functions** the system must support.
- Serves as a communication bridge between technical and non-technical stakeholders.

### 🧑‍🤝‍🧑 Actors in the Booking Management System:
- **Customer**: Searches, books, pays, and views bookings.
- **Hotel Manager**: Creates and manages hotel listings.
- **System**: Handles authentication, notifications, and payment processing.

### 📌 Use Case Diagram



