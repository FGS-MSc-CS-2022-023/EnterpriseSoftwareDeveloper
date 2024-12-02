*2024-12-02*

## Component Based Architecture

![](./images/interface.png)
![](./images/oracleerp.png)

## Component Based Architecture

Why Component architecture ?

- Enterprise Applications Involved high complexity
- Adopt new functionality in low cost manner
- Easier for new customers to implement
- Existing customer should be able to upgrade to new functionality


## What is Component

Individual module which has following attributes

- Separation - All data and Functions are semantically related
- Interfacing - Which can upgrade with new components
- Standardization - Agreed standard interface

Example: PC
- Constructed by different manufacturers
- Assembled very rapidly
- Assembler is not an expert in internals of each component

## Disadvantages of Component Based

- Performance overhead
- Difficult to change interfaces 

## Component Based Architecture Goals

- Goal 01: Software Construction

![](./images/softwareConstruction.png)

- Goal 02: Reuse

![](./images/reuse.png)

- Goal 03: Maintanance

![](./images/maintainance.png)

Exam: Compare major benefits or drawbacks between different architecture patterns.

# Monolithic Architecture

- A Monolithic Architecture is a software pattern in which a
single application is built as a single, indivisible unit.
- All components of the application are interconnected and
run as a single process.

    - Single Codebase: All functionality exists in a single codebase.
    - Unified Deployment: The application is deployed as a single
unit.
    - Tight Coupling: Components are tightly coupled and
interdependent.
    - Single Process: Runs as a single process on a server.

- A monolithic architecture is a traditional approach where the entire
application is a single, integrated unit.
- As the application grows, complexity increases, making maintenance and scaling difficult.
    - Limited Scalability: All components must scale together, leading to inefficiencies.



