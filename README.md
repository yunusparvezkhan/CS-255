# CS 255: System Analysis and Design Portfolio

**Author:** \
Yunus Parvez Khan\
(yunus.parvezkhan@snhu.edu)\
Department of Computer Science\
**Course:** System Analysis and Design (CS 255) \
**Instructor:** Dr. Anamika Singh\
Southern New Hampshire University\
Manchester, NH 03106, United States\


**Course:** CS 255 --- System Analysis and Design

## Portfolio Overview

This repository contains two major artifacts developed for the
DriverPass project in CS 255:

-   **Project One --- Business Requirements Document:** Defines the
    purpose and objectives of the proposed DriverPass system, its
    functional and nonfunctional requirements, user-interface needs,
    assumptions, limitations, security considerations, and a project
    schedule.
-   **Project Two --- System Design Document:** Translates the
    requirements into UML models and technical specifications, including
    a use case diagram, activity diagrams, a sequence diagram, a class
    diagram, and hardware, software, infrastructure, and security
    requirements.

Together, these documents demonstrate the process of analyzing a
client's needs and planning a system intended to support those needs.

## Reflection

### 1. Briefly summarize the DriverPass project. Who was the client, and what type of system did they want designed?

DriverPass is a driver-training business established by Liam to help
students prepare for their driving examinations through a combination of
theoretical learning and practical instruction. The proposed system is a
centralized, web-based platform that brings customer registration,
training packages, driving lesson reservations, instructor and vehicle
assignments, online classes, practice tests, and business reporting
together. Customers would be able to manage accounts and appointments
online, while the owner, secretary, driving instructors, and IT officer
would use role-appropriate functions to support business operations.

### 2. What did you do particularly well?

I believe I did well at breaking the business scenario into specific
requirements and considering the needs of different user roles. The
Business Requirements Document covers both functional
requirements---such as registering customers, scheduling lessons,
managing packages, and recording practice-test results---and
nonfunctional requirements, including security, performance,
adaptability, and data accuracy. I also considered operational
accountability by including reservation activity histories and
reporting. In the System Design Document, I used UML diagrams to
communicate system behavior and structure. For example, the activity and
sequence diagrams describe the scheduling workflow, including checking
driver and vehicle availability, saving a reservation, and sending
confirmations.

### 3. If you could revise one part of your work, what would you revise and how would you improve it?

If I could revise one part of my work, I would refine the UML diagrams
and make the relationships between them more consistent and explicit.
The diagrams communicate important workflows and system entities, but
clearer labels, more precise decision paths, and carefully checked
associations would make them easier for another analyst or developer to
interpret. I would also cross-check the class diagram against the
requirements and the scheduling workflows to ensure that the represented
entities and relationships fully support the processes described. This
revision would improve the documents' clarity and make them a stronger
handoff for implementation.

### 4. How did you interpret the user's needs and implement them into your system design? Why is it important to consider user needs?

I interpreted the client's needs by identifying the main activities
DriverPass must support and the responsibilities of the people who use
the system. Customers need to register, select training packages, access
eligible learning materials, and manage reservations. The secretary
needs to register customers and manage appointments on their behalf. The
owner needs business information and reports, while the IT officer needs
account-management and access-control functions. I translated these
needs into documented requirements and represented key interactions
through UML diagrams. Considering user needs is essential because a
technically functional system can still fail if it does not support the
actual work people need to perform. User-focused analysis helps keep the
design relevant, usable, secure, and aligned with business objectives.

### 5. How do you approach designing software? What techniques or strategies would you use in the future?

My approach is to understand the problem and the client's goals before
deciding how the system should work. I would identify stakeholders,
document functional and nonfunctional requirements, clarify assumptions
and limitations, and separate the system's responsibilities according to
user roles. I would then use models such as use case, activity,
sequence, and class diagrams to examine the system from different
perspectives. In future projects, I would also validate the models
against the requirements, check that workflows and data relationships
are consistent, and ask stakeholders to clarify unresolved details
before implementation. This structured approach can reduce
misunderstandings, expose gaps early, and provide developers with a
clearer design to build and test.

## Documents

Place the final versions of the project documents in the folders below:

-   `Project-One/Business-Requirements-Document.pdf`
-   `Project-Two/System-Design-Document.docx`

Update the file names or links in this section if you use different
formats or naming conventions.
