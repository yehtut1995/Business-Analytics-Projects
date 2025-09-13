### Overview

This project describes the Order Management Process, which enables customers to request services, sales assistants to validate and place orders, and stock supervisors to fulfill them. The process ensures that only validated and paid orders are delivered to customers, maintaining operational efficiency and data accuracy. First, relevant stakeholders are described briefly. Then, it has been developed using 4 core activities:

### 1. Business Process Mapping
A diagram was created using UML to visualize the interactions among three main roles: Customer, Sales Assistant, and Stock Supervisor.
The process flow includes:
•	Requesting service
•	Validating and placing orders
•	Processing payment
•	Fulfilling and delivering the order
Decision points (e.g., order correctness) and outcomes (e.g., order rejection) are explicitly modeled. This process map served as the foundation for identifying requirements and system interactions.

### 2. Requirement Gathering
Requirements were derived from the mapped business process.
Stakeholder interviews and process analysis informed the definition of functional and non-functional requirements.
Functional requirements specify what the system must do (e.g., order validation, payment processing, stock updates).
Non-functional requirements specify how the system should perform (e.g., response time, availability, scalability).
Risks, constraints, and assumptions were documented to highlight business dependencies.

### 3. Use Cases
Each functional requirement was translated into one or more use cases, describing system interactions with actors.
Use cases define preconditions, main flows, and alternate flows to capture normal and exceptional scenarios.
Key use cases include:
•	Submitting a service request
•	Validating and placing orders
•	Making payments
•	Filling and delivering orders

These use cases will be further detailed into user stories and acceptance criteria for development and testing.


### 4. Acceptance Criteria
Acceptance criteria define the conditions that must be met for each use case to be considered successfully implemented. They provide clear, testable statements that ensure requirements are fulfilled and stakeholder expectations are aligned. Each acceptance criterion is linked directly to the functional requirements and use cases derived from the business process map. This guarantees end-to-end traceability from business need to tested solution.
