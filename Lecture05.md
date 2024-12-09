*2024-12-09*

# ROA

![](./images/roa-slidea.png)

![](./images/roa-slide1.png)

# Domain-Driven Design (DDD)

Domain-Driven Design (DDD) is an approach to software development that emphasizes the importance of modeling the domain (business logic) and building a deep understanding of the domain's complexities.

**Benefits:**

- Improved alignment between the business and the software model.
- Enhanced maintainability and scalability through well-defined boundaries and models.
- Better handling of complex business rules and processes.

**Use Cases:**

- Complex business applications with intricate domain logic.
- Systems where deep collaboration between technical and domain experts is essential.

![](./images/ddd-proscons.png)

## Are all Enterprise solutions DDD?

1. Complex Enterprise System: A large e-commerce platform with intricate
pricing rules, inventory management, and customer personalization
which need to manage the complex interactions and business logic. (DD)
2. Simple CRUD Application: A basic employee management system that
requires simple Create, Read, Update, Delete (CRUD) operations on
employee records. (Monolithic mvc/layered)
3. Real-Time Data Processing : An application that processes streaming data
from loT devices in real-time which requires handling the continuous
flow of data and trigger responses. (event driven)
4. Integrating Legacy Systems : A banking application that needs to
integrate various legacy systems for customer account management and
also to facilitate communication between the different systems. (SOA)

# Event-Driven Architecture (EDA)

- Event-Driven Architecture (EDA) is an architectural style in which
events are the primary means of communication between decoupled components.
- An event signifies a significant change in state or an occurrence that components react to.
- Use Cases:
    - Real-time analytics and monitoring systems.
    - Applications requiring decoupled and scalable communication, such as e-commerce platforms and loT systems.

## Event-Driven Architecture (EDA) - Key Concepts

- **Event**: A signal that something of interest has happened, such as a state change or a user action. Events can carry data about the occurrence.
- **Event Producer**: A component that generates and publishes events.
- **Event Consumer**: A component that subscribes to and reacts to events.
- **Event Channel**: The medium through which events are transmitted from producers to consumers, often implemented using message brokers or event buses.

(Order service and shipping service)

![](./images/roa-slide3.png)

## Example Scenarios:

1. A large-scale online travel booking platform.
- The platform needs to handle various services like flight bookings, hotel
reservations, car rentals, and user reviews.
- Each service needs to be independently scalable to handle high traffic and
frequent updates.
- The platform must integrate with multiple third-party APIs and support real-
time availability and pricing updates.
2. A local restaurant's online ordering system.
- The system needs to provide a simple interface for customers to browse the
menu, place orders, and make payments.
- The development team is small, and the restaurant wants to quickly deploy
the system with minimal complexity.
- The volume of traffic is relatively low and manageable within a single
codebase.

3. A modular home automation system.
- The system includes various components such as lighting control, security
monitoring, temperature)regulation, and energy management.
Each component needs to be developed and updated independently while
working together seamlessly.
- Users should be able to customize their system by adding or removing
components based on their needs. 

(Event driven/Microservice)

4. An educational platform for online courses and learning management.
- The platform needs to manage user accounts, courses, quizzes, and grades.
- It requires a clear separation between data (students, courses), the user
interface (course pages, quizzes), and control logic (user authentication, course
enrollment).
- The development team wants to follow a structured approach to ensure
maintainability and scalability as the platform grows. 

(Layered)

5. A university management system to manage courses, students, and faculty.
- The system needs to handle user interactions (student portal, faculty portal),
application logic (course registration, grading), and data management (student
records, course catalog).
- Each layer (presentation, business logic, data access) is clearly defined and separated.
- This separation promotes maintainability and simplifies development and testing.

(MVC)

# Software System Architecture

This means

- The high-level structure and organization of software components that define how they interact and work together.
- An effective software architecture provides a solid foundation for building scalable, maintainable, and efficient enterprise applications.
- Key components and principles of software system architecture:
Overview of architectural components such as modules, interfaces, data stores, and architectural principles ..

## What is the architecture view?

- A view means the manner of looking at something
- For better understanding and managing , multi dimensional view must be taken
for any complex entity , multiple parameters / specialties involved.
- For example, what are the views of a building ...
- Room layout
- 3D view of building / room
- Electrical diagram
- Plumbing diagram
- Security alarm diagram etc ... etc ...
- Which of the above view is Architecture ?
- Not one but ALL of them ( sets of parts work together as a successful whole)
- In Software, What are views ?

## Definition of Software View

- Software architecture descriptions are commonly organized into <ins>*views*</ins>,
- Each <ins>*view*</ins> addresses a set of system concerns, following the conventions of
its <ins>*viewpoint*</ins>.
    - Viewpoint - <ins>A position or direction</ins> from which something is observed or considered;
    - View - Dotails or full specification considered from that viewpoint
        - (describes the notations, modeling and analysis techniques that express the architecture in
question from the perspective of a given set of stakeholders )
- **So, a view of a system is a representation of the system from the perspective of a viewpoint.**

## Examples of Software Views

A <ins>view</ins> allows a user to examine a portion of a particular interest area.

- A Logical View ( top / overall / bird's eye view) 
    - all functions,
    - organizations,
- Implementation(Deployment) view
    - Technology ( HW and networking)
    - Module sequence
- Developmental view
    - Front end
    - Backend
    - Database connectivity

- Process View
    - Modules and its functions,
    - Their interactions
    - Control points
    - Non Functional Requirements
- Security View
    - User Id / Password
    - Graphical password
    - Transactional password
- +++ other views

## Uses of Views

- Communication:
    - Stakeholder Communication
    - Clarity and Understanding
- Documentation:
    - Detailed Documentation
    - Reference Material
- Design Validation:
    - Consistency Checks
    - Scenario Validation
- Analysis and Optimization:
    - Performance Analysis
    - Deployment Planning