# Requirement Analysis in Software Development.

**Introduction**
Requirement Analysis is a critical phase in the software development lifecycle (SDLC) where the project team gathers, analyzes, and defines the requirements of the software product to be developed. This process ensures that all stakeholders have a clear and mutual understanding of what the system should do and how it should perform.

# What is Requirement Analysis?

Requirement Analysis is a critical phase in the software development lifecycle (SDLC) where the project team gathers, analyzes, and defines the requirements of the software product to be developed. This process ensures that all stakeholders have a clear and mutual understanding of what the system should do and how it should perform.

# The importance of requirement analysis in software development life cycle (SDLC)

The importance of requirement analysis in software development life cycle (SDLC) cannot be overstated.

- It is a critical phase that ensures that all stakeholders have a clear and mutual understanding of what the system should do and how it should perform.
- It helps to identify and document the functional and non-functional requirements of the software product.
- It ensures that the software product meets the needs and expectations of the stakeholders.
- It helps to reduce the risk of project failure by identifying and addressing potential issues early on.
- It helps to improve the quality of the software product by ensuring that it meets the requirements of the stakeholders
- It helps to reduce the cost of software development by identifying and addressing potential issues early on.

# Why is Requirement Analysis Important?

**Reasons why Requirement Analysis is critical in the SDLC**

## Clarity and Understanding

It helps in understanding what the stakeholders expect from the software, reducing ambiguity.

## Basis for Design and Development

It serves as a foundation for the design and development of the software product.

## Cost and Time Estimation

Facilitates accurate estimation of project cost, resources, and time.

# Key Activities in Requirement Analysis.

### Requirement Gathering 🗂️

Requirement gathering involves collecting detailed information about stakeholders' needs and expectations through various methods. Techniques include conducting interviews, distributing surveys or questionnaires, organizing workshops, observing end-users in their work environment, and analyzing existing documentation. These activities help ensure a comprehensive understanding of current functionalities and user needs.

### Requirement Elicitation ✍️

Requirement elicitation focuses on extracting and refining stakeholder requirements through collaborative techniques. Methods include brainstorming sessions to generate ideas, focus group discussions for in-depth insights, and prototyping to help stakeholders visualize the system and refine their expectations. These approaches facilitate clear and actionable requirement definitions.

### Requirement Documentation 📚

Requirement documentation involves formally recording all gathered and elicited requirements. Key deliverables include a detailed Requirement Specification Document (RSD), user stories that describe functionalities from the user’s perspective, and use case diagrams illustrating interactions between users and the system. Proper documentation ensures clarity and serves as a reference throughout the project lifecycle.

### Requirement Analysis and Modeling 📊

This phase involves analyzing, prioritizing, and modeling requirements to ensure they are feasible and well-structured. Activities include prioritizing requirements based on importance, assessing technical, financial, and time feasibility, and creating visual models (e.g., data flow diagrams, entity-relationship diagrams) to better understand and communicate system requirements.

### Requirement Validation ✅

Requirement validation ensures that documented requirements are accurate, complete, and aligned with stakeholder expectations. Key steps include reviewing and approving requirements with stakeholders, defining clear acceptance criteria, and establishing traceability matrices to track requirements throughout development and testing. This phase helps prevent misunderstandings and ensures the final product meets business needs.

# Types of Requirements.

## Functional Requirements ⚙️

**Definition** Describe what the system should do.
Examples: User authentication, property search, booking system, user registration.

## Key Functional Requirements:

- Search Properties: Users should be able to search for properties based on various criteria such as location, price, and availability.
- User Registration: New users should be able to create an account with personal details and login credentials.
- Property Listings: Display properties with essential details and images.
- Booking System: Users should be able to book properties, view booking details, and manage their bookings.
- User Authentication: Secure login and registration process for users.

# Non-functional Requirements 🛡️

**Definition** Describe how the system should perform.
Examples: Performance, security, scalability, usability, reliability.

## Key Non-functional Requirements:

- Performance: The system should load pages within 2 seconds and handle up to 1000 concurrent users.
- Security: Ensure data encryption, secure login, and protect against common vulnerabilities.
- Scalability: The system should be able to scale horizontally to handle increased traffic.
- Usability: The application should have an intuitive UI/UX, making it easy for users to navigate and perform tasks.
- Reliability: The system should have an uptime of 99.9% and recover quickly from any failures.

# Use Case Diagrams.

A Use Case Diagram is a visual representation in Unified Modeling Language (UML) that illustrates the interactions between actors (users or external systems) and a system to achieve specific goals. It captures the functional requirements of a system by showing:

Actors – Who interacts with the system (e.g., users, admins, third-party services).

Use Cases – What the system does (e.g., "Make Booking," "Process Payment").

Relationships – How actors and use cases connect (e.g., associations, dependencies).

# Benefits of Use Case Diagrams

## Clarifies System Functionality

Provides a high-level overview of what the system does without technical details.

Helps stakeholders (developers, clients, testers) align on requirements.

## Identifies Actors and Interactions

Clearly defines who uses the system (e.g., customers, admins) and their goals.

## Supports Requirement Analysis

Bridges the gap between business needs and technical implementation.

Helps detect missing or redundant features early.

## Improves Communication

Visual and intuitive, making it easier to discuss with non-technical teams.

## Guides Development & Testing

Serves as a reference for creating test cases (e.g., "Can a guest cancel a booking?").

Helps prioritize features during development.

## Scalable & Modular

Use cases can be broken into smaller sub-functions (e.g., "Payment" includes "Validate Card").

# Case Diagram

![alx-booking-uc.png]
![Image](https://github.com/user-attachments/assets/6ee0a3a5-f454-493e-af5a-069e7fa4f56e)

# Acceptance Criteria

Acceptance Criteria (AC) are a set of conditions that a software feature must meet to be considered complete and acceptable to stakeholders. They act as a contract between developers, testers, product owners, and clients, ensuring clarity and reducing ambiguity in requirements.

# Why Acceptance Criteria Are Important?

## Clarifies Expectations

Defines exactly what "done" means for a feature.

Avoids misinterpretations between business and technical teams.

## Guides Development & Testing

Developers use AC to implement features correctly.

QA teams rely on AC to write test cases.

## Reduces Scope Creep

Prevents vague or incomplete requirements from derailing a project.

## Improves Stakeholder Alignment

Ensures everyone (clients, product managers, engineers) agrees on success metrics.

## Supports Agile & User Stories

In Agile, AC are attached to user stories (e.g., "As a user, I want to checkout so I can complete my booking.").

# Examples of acceptance criteria for a feature like the Checkout feature in the booking management system

# User Story:

"As a registered user, I want to complete a booking checkout so that I can confirm my reservation."

# Acceptance Criteria:

## Cart Summary Display

✅ The checkout page must display:

    Booking details (date, time, service).

    Total price (including taxes/fees).

    Applied discounts (if any).

## Payment Method Selection

✅ User can choose between:

    Credit/Debit Card

    PayPal

    Wallet Balance (if available)

## Card Validation

✅ If paying by card:

    System validates card number (16 digits), expiry date (future date), and CVV (3-4 digits).

    Invalid card details show an error message.

## Discount Code Application

✅ User can enter a promo code.

✅ Invalid codes display: "Invalid or expired promo code."

✅ Valid codes update the total price.

## Booking Confirmation

✅ After successful payment:

    A confirmation email/SMS is sent.

    Booking appears in the user’s "My Trips" section.

## Error Handling

✅ If payment fails:

    User sees: "Payment failed. Please try again or use another method."

    No booking is created.

## Guest Checkout (Optional)

✅ Guest users can checkout without an account but must provide:

    Email (valid format).

    Phone number (for confirmation).
