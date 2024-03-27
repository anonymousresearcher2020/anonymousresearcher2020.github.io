---
layout: default
title: Milestone Specifications
nav_order: 3
has_children: false
permalink: /docs/Milestone Setup
---

### Requirement Engineering Milestone Summaries

The purpose of this page is to first explain the overall process of using ChatGPT in the requirement engineering process of this course. Next we specify the information required from students to define the project proposal (section A) as well as the initial (section B) and final (section C) requirement specifications.

---

#### Explanation of the Process
![](../img/overview.pdf)

In an effort to embrace and utilize these advanced AI tools, students were allowed to use them throughout the course. In fact, one of the educational objectives of this course was to expose students to the advantages and disadvantages of using AI tools in SE processes. As such, throughout the course, students systematically used such tools as assistants in completing their assignments and were required to document and critically analyze these uses, identifying strengths and weaknesses of the AI tools. The analysis was submitted together with the assignments 

For the requirements milestone, students were instructed to use ChatGPT version 3.5 (other versions and tools were forbidden, for fairness). To allow students to explore and critically analyze the capabilities of conversational AI, we designed two distinct processes, A and B, of using ChatGPT
to produce requirements specifications, as shown in Figure above. 

The students were first asked to come up, as a group, with two possible ideas for a project they might want to implement in the scope of the course. We randomly split the 20 project groups into two groups of ten and labeled the first idea in the submissions of the first group and the second idea in the submissions of the second group as idea A (IA). The remaining ideas were labeled as idea B (IB). 
This was done to avoid any bias that may arise from personal preferences of students
when picking which idea to work on first.

Next, in the course lab session, the students spent one and a half hours producing requirements specifications for IA (as was typically done in previous offerings of the course, before conversational AI technologies were introduced). Use of any external tools was not permitted in this session, but TAs were available to answer questions, in case students had any. The student were asked to submit the produced version. However, this intermediate submission was not graded in the scope of the course (we later graded it for this study).

Next, students were asked to use ChatGPT to further improve HA through a series of discussions. They had to submit all their conversations with ChatGPT, which we refer to as PA. Students could choose to stop interacting with ChatGPT at any point of this step, if they believed the interactions do not lead to any meaningful improvement. We refer to the requirements specifications we extracted from these conversations as GA. This artifact was not graded in the scope of the course, but we later graded it in the scope of this study.

As the last step in this process, students were asked to produce and submit their final requirement specification for idea A, which we refer to as A. We also asked them whether they used ChatGPT output as is and, if not, what they had to refine and why.

Finally, students repeated the process from idea B (lower part of Figure above). Unlike in process A, they interacted with ChatGPT immediately, without a preliminary session to produce their requirements specifications. We refer to artifacts produced in this process as PB (for ChatGPT conversations), GB (for the requirement specializations produced through this interaction), and B (for the final submission of requirements specifications of idea B, which was graded in the scope of the course).

---

#### A. Project Proposal Assignment to Produce "Project Idea (I)":

- In this assignment, each group of four students is asked to come up with two different ideas that can be implemented during the course.
- Each idea must take into account the following project expectations:
  - **Scope:** 2-3 main actors and 5-6 non-trivial requirements
  - **Required features:**
    - Use of an external authentication service, e.g., Google
    - Use of at least one additional external service accessible via an API, e.g., Google calendar, Google maps, etc.
    - Real-time updates, e.g., multi-user chats, push notifications, etc.
    - Complex logic in either front-end or back-end component (i.e., something that involves an algorithm, not a simple API call or database read/update/delete)
  - **Implementation:** Android Front-end using Java, Node.js backend
- **Submission:** A PDF file containing information about two project ideas.

---
#### B. Initial Requirements Lab Activity to Produce "Initial Submission (H)":

- In this 2-hour long lab activity, each group of students works on the requirement specifications of one of their project ideas (P) randomly selected by a TA.
- Usage of assistive AI technology is strictly prohibited.
- As per the course material, a formal requirement specification is required containing:
  - A use-case diagram connecting actors to functional requirements
  - A description of each actor (1-2 sentences).
  - A list functional requirements specifying the name of the requirement, a short description, primary actor(s), success and failure scenarios, and mockups (optional).
  - A list of 2-3 non-functional requirements with an explanation of why this requirement is needed/relevant for the project and how it will be validated.
- **Submission:** A scanned PDF file containing the formal specification in the format above.

---
#### C. Final Requirement Specification Assignment to Produce "Final submission (F)":

- In this assignment each group of students is asked to submit a formal requirement specification for both of their project ideas.
- Documented usage of AI technology (namely, ChatGPT 3.5) is required.
- Each group uses the following workflow to generate the final requirements:
  - For the idea a group worked on during the lab activity (A), they start from a possibly updated project specification from the lab (A_initial), and refine it with the assistance of ChatGPT to generate the final specification (A_final).
  - For the idea a group has not yet worked on (B), they start from the specification provided by ChatGPT and refine it to generate the final specification (B_final).
- **Submissions:** 
  - 1. A PDF file containing the formal requirement specifications A_initial, A_final, and B_final.
  - 2. HTML files containing ChatGPT conversations used in the process.
  - 3. Reflections about their usage of ChatGPT.

 
