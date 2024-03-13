---
layout: default
title: Course Summary
nav_order: 2
has_children: false
permalink: /docs/course
---
## Course Summary

CPEN 321 - Requirement Engineering Lecture Summaries

The purpose of this document is to specify how the requirements were defined in the scope of this course and what resources students could use while interacting with ChatGPT. This is to help the reader understand what is considered a good requirement in the scope of this course and based on what information the evaluation was conducted. The topic was covered in 3 lectures, 1 lab session (initial requirement elicitation milestone (B)), and 2 home assignments (project idea (A) and final requirement specification (C) milestones). Examples of good/bad requirements were provided in the lectures and the lab. Feedback was also given on the assignment. 
—------------------------------—------------------------------—------------------------------—-------------------------

●	Requirement engineering process: In this milestone, we focused on requirements elicitation, analysis, specification (not validation and maintenance). 
○	Elicitation: researching and discovering the requirements of a system from users, customers, and other stakeholders. Think about why users want to do something in your app, not just what. 
○	Analysis: critically assessing, refining and modifying the gathered requirements
○	Specification: documenting the elicited requirements in a formal manner to ensure clarity, consistency, and completeness. 
○	Validation: demonstrating that the specified requirements define the system that the customer really wants.
○	Maintenance: managing changed requirements during the system development.

●	Functional Requirements: describe the system functionality, i.e., what is should do [1]. 
○	The use case diagram provide a graphical representation of the system’s intended interactions with its environment and users, making the system’s functionality more understandable.  is used to communicate what a system is intended to accomplish*: 
■	Actors: people, devices, or other systems interact with the system and are external to the system itself. 
■	Use cases: behavior of the software that meet the user’s need and describe all possible interactions with the system, represented by verbs
■	Line associations: connect an actor to a use case in which that actor participates
■	Relationship between actors: Generalization
■	Relationship between use cases: Generalization, Include, and Exclude 
○	The formal requirement specification is the final product that is used to document the requirements in both a graphical and textual format*. 
■	The lightweight use case specification of each requirement includes: 
●	Name, Short description, and Primary Actor(s) 
●	Success Scenarios: normal flow of events in the system. People can relate to these more readily than abstract statement of what they require from a system
●	Failure Scenarios: what can go wrong corresponding to each step in the success scenario and how this is handled

●	Non-Functional Requirements: describe system properties and constraints as a whole [1]. Specify acceptance criteria related to system qualities such as performance, reliability, and usability. 
○	Performance, safety, security, scalability, dependability, reusability, portability
○	Specification of each requirement includes: Textual description, Justification (why needed), and Validation approach (how to confirm).

[1] I. Sommerville and P. Sawyer. Requirements Engineering: A Good Practice Guide. John Wiley & Sons, Inc., 1st edition, 1997

●	Qualities of good requirements (for elicitation and analysis)  
○	Requirements define what the software needs to do. 
○	Requirements tell the problem, not the solution: specify what to build not how
○	The requirement engineering process is a process. Allow (and expect) requirements to change later
○	There are two types of requirements: Functional and Non-functional
○	Requirements should be: 
■	Specific: specific to a particular project (rather than applicable to any project), explainable and defined at the right level of details (not too coarse-grained or too fine-grained)
●	E.g., “response time under 1 sec” should explain why 1 sec is applicable for this project (and not 3 or 0.5). 
●	E.g., “add profile item”, “update profile item”, “delete profile item” are too fine-grained for an ecommerce application. It can be “manage profile”. Not every button click deserve to be a separate use case
■	Verifiable/Measurable: can define a test with a clear spec 
●	E.g., “it should perform well” is not measurable 
■	Feasible: possible to implement given the time and resource constraints
●	E.g., “the server should be available 24/7”
■	Complete: should cover all parts of the project high-level description and goals
●	When something is part of the project descriptions and goals, there should be a use case for it. E.g., “Adding a friend can be done in one click”. What about other parts of the use ase / other use cases
●	Cover the course required requirements: 5-6 non-trivial reqs. and 4 requirements: live updates, external API, complex logic, and external authentication service. 
■	Consistent: should not have contradictory definitions
●	E.g., should not use different words for the same use case, failure points should correspond to concrete steps in success scenarios
■	Unambiguous: include concrete requirement description, success and failure scenarios 
■	Appropriate functional / non-functional classification (separation): functional requirements describe functionality that helps meet the needs of its users and stakeholders; Non-functional requirements specify criteria related to system qualities such as performance, reliability, security, and usability
●	E.g., specifying the performance criteria the system must meet, such as response times or throughput is not a functional requirement 
●	“User should be able to log-in” is a functional rather than security requirement

●	Qualities of good requirements documentation (for specification)  
○	Complete: contain all the necessary information (execution steps, descriptions, etc.) 
○	Well-formatted: appropriate notations of use case diagram, success/failure specs. 
○	Concrete: define concrete sequences of execution steps, failure points, etc.
○	User-focused: use cases should not describe sub-systems but user-facing action [represented by verbs], actors should describe entities interacting with the app (not app developers). 

●	Assignment mistakes
○	Irrelevant content (e.g., failure scenarios are bugs rather than failure cases, duplicated use case, [a picture of a cat]). 








