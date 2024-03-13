---
layout: default
title: Course Summary
nav_order: 2
has_children: false
permalink: /docs/course
---
## Course Summary

### CPEN 321 - Requirement Engineering Lecture Summaries

The purpose of this document is to specify how the requirements were defined in the scope of this course and what resources students could use while interacting with ChatGPT. This is to help the reader understand what is considered a good requirement in the scope of this course and based on what information the evaluation was conducted. The topic was covered in 3 lectures, 1 lab session (initial requirement elicitation milestone), and 2 home assignments (project idea and final requirement specification milestones). Examples of good/bad requirements were provided in the lectures and the lab. Feedback was also given on the assignment. 
—------------------------------—------------------------------—------------------------------—-------------------------

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;●	Requirement engineering process: In this milestone, we focused on requirements elicitation, analysis, specification (not validation and maintenance). 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;○	Elicitation: researching and discovering the requirements of a system from users, customers, and other stakeholders. Think about why users want to do something in your app, not just what. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;○	Analysis: critically assessing, refining and modifying the gathered requirements

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;○	Specification: documenting the elicited requirements in a formal manner to ensure clarity, consistency, and completeness. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;○	Validation: demonstrating that the specified requirements define the system that the customer really wants.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;○	Maintenance: managing changed requirements during the system development.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;●	Functional Requirements: describe the system functionality, i.e., what is should do [1]. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;○	The use case diagram provide a graphical representation of the system’s intended interactions with its environment and users, making the system’s functionality more understandable.  is used to communicate what a system is intended to accomplish*: 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;■	Actors: people, devices, or other systems interact with the system and are external to the system itself. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;■	Use cases: behavior of the software that meet the user’s need and describe all possible interactions with the system, represented by verbs

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;■	Line associations: connect an actor to a use case in which that actor participates

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;■	Relationship between actors: Generalization

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;■	Relationship between use cases: Generalization, Include, and Exclude 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;○	The formal requirement specification is the final product that is used to document the requirements in both a graphical and textual format*. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;■	The lightweight use case specification of each requirement includes: 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;●	Name, Short description, and Primary Actor(s) 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;●	Success Scenarios: normal flow of events in the system. People can relate to these more readily than abstract statement of what they require from a system

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;●	Failure Scenarios: what can go wrong corresponding to each step in the success scenario and how this is handled

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;●	Non-Functional Requirements: describe system properties and constraints as a whole [1]. Specify acceptance criteria related to system qualities such as performance, reliability, and usability. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;○	Performance, safety, security, scalability, dependability, reusability, portability

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;○	Specification of each requirement includes: Textual description, Justification (why needed), and Validation approach (how to confirm).

[1] I. Sommerville and P. Sawyer. Requirements Engineering: A Good Practice Guide. John Wiley & Sons, Inc., 1st edition, 1997

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;●	Qualities of good requirements (for elicitation and analysis)  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;○	Requirements define what the software needs to do. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;○	Requirements tell the problem, not the solution: specify what to build not how

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;○	The requirement engineering process is a process. Allow (and expect) requirements to change later

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;○	There are two types of requirements: Functional and Non-functional

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;○	Requirements should be: 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;■	Specific: specific to a particular project (rather than applicable to any project), explainable and defined at the right level of details (not too coarse-grained or too fine-grained)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;●	E.g., “response time under 1 sec” should explain why 1 sec is applicable for this project (and not 3 or 0.5). 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;●	E.g., “add profile item”, “update profile item”, “delete profile item” are too fine-grained for an ecommerce application. It can be “manage profile”. Not every button click deserve to be a separate use case

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;■	Verifiable/Measurable: can define a test with a clear spec 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;●	E.g., “it should perform well” is not measurable 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;■	Feasible: possible to implement given the time and resource constraints

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;●	E.g., “the server should be available 24/7”

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;■	Complete: should cover all parts of the project high-level description and goals

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;●	When something is part of the project descriptions and goals, there should be a use case for it. E.g., “Adding a friend can be done in one click”. What about other parts of the use ase / other use cases

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;●	Cover the course required requirements: 5-6 non-trivial reqs. and 4 requirements: live updates, external API, complex logic, and external authentication service. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;■	Consistent: should not have contradictory definitions

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;●	E.g., should not use different words for the same use case, failure points should correspond to concrete steps in success scenarios

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;■	Unambiguous: include concrete requirement description, success and failure scenarios 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;■	Appropriate functional / non-functional classification (separation): functional requirements describe functionality that helps meet the needs of its users and stakeholders; Non-functional requirements specify criteria related to system qualities such as performance, reliability, security, and usability

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;●	E.g., specifying the performance criteria the system must meet, such as response times or throughput is not a functional requirement 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;●	“User should be able to log-in” is a functional rather than security requirement

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;●	Qualities of good requirements documentation (for specification)  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;○	Complete: contain all the necessary information (execution steps, descriptions, etc.) 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;○	Well-formatted: appropriate notations of use case diagram, success/failure specs. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;○	Concrete: define concrete sequences of execution steps, failure points, etc.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;○	User-focused: use cases should not describe sub-systems but user-facing action [represented by verbs], actors should describe entities interacting with the app (not app developers). 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;●	Assignment mistakes

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;○	Irrelevant content (e.g., failure scenarios are bugs rather than failure cases, duplicated use case, [a picture of a cat]). 








