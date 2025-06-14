---
layout: default
title: Course Setup
nav_order: 2
has_children: false
permalink: /docs/course_setup
---

We now specify how the requirements were defined in the scope of this course. The requirements topic was covered in three lectures and two lab sessions. There were two requirements milestones (project idea and final requirement specifications) and an in-lab work (initial submission).

---

### Requirements

- **Requirement Engineering Process:**
  - In this milestone, we focused on requirements elicitation, analysis, specification (not validation and maintenance).
    - Elicitation: researching and discovering the requirements of a system from users, customers, and other stakeholders. Think about why users want to do something in your app, not just what.
    - Analysis: critically assessing, refining, and modifying the gathered requirements
    - Specification: documenting the elicited requirements in a formal manner to ensure clarity, consistency, and completeness.

- **Functional Requirements:**
  - Describe the system functionality, i.e., what it should do.
    - The **use case** diagram provides a graphical representation of the system’s intended interactions with its environment and users, making the system’s functionality more understandable. It is used to communicate what a system is intended to accomplish:
      - Actors: people, devices, or other systems interact with the system and are external to the system itself.
      - Use cases: behavior of the software that meets the user’s need and describe all possible interactions with the system, represented by verbs
      - Line associations: connect an actor to a use case in which that actor participates
      - Relationship between actors: Generalization
      - Relationship between use cases: Generalization, Include, and Exclude
    - The **formal requirement specification** is the final product that is used to document the requirements in both a graphical and textual format.
      - The lightweight use case specification of each requirement includes:
        - Name, Short description, and Primary Actor(s)
        - Success Scenarios: normal flow of events in the system. People can relate to these more readily than abstract statements of what they require from a system
        - Failure Scenarios: what can go wrong corresponding to each step in the success scenario and how this is handled

- **Non-Functional Requirements:**
  - Describe system properties and constraints as a whole. Specify acceptance criteria related to system qualities such as performance, reliability, and usability.
    - Performance, safety, security, scalability, dependability, reusability, portability
    - Specification of each requirement includes: Textual description, Justification (why needed), and Validation approach (how to confirm).


---

### Milestones


- ##### [Project Proposal Assignment to Produce "Project Idea (I)"](data/M1_Project_Ideas.pdf) 

- ##### [Initial Requirements Lab Activity to Produce "Initial Submission (H)"](data/M2A_Requirements.pdf)

- ##### [Final Requirement Specification Assignment to Produce "Final submission (F)"](data/M2B_Requirements.pdf)
