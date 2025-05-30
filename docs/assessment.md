---
layout: default
title: Artifacts Assessment 
nav_order: 4
has_children: false
permalink: /docs/assessment
---

This page provides a detailed outline of our requirements and prompt assessment rubric. All artifacts produced by students in the course, i.e., requirements
specifications (HA, GA, GB, FA and FB) and ChatGPT prompts (PA and PB) were manually graded by two authors of this paper, who were also in the teaching staff of the course.
The graders cross-validated their marks and all disagreement (5% for requirements and 6% for prompts) were resolved with a third author, who was the course instructor.


### Requirements Quality Attributes:

- **Complete** and cover all parts of the project goals, providing sufficient information to implement the system
    - When something is part of the project descriptions and goals, there should be a use case for it. E.g., “Adding a friend can be done in one click”. What about other parts of the use case / other use cases
    - Cover the course required requirements: 5-6 non-trivial requirements and 4 components: live updates, external API, complex logic, and external authentication service.
- **Consistent,** without having contradictory definitions across multiple requirements.
    - E.g., should not use different words for the same use case, failure scenarios should correspond to concrete steps in success scenarios
- **Unambiguous,** i.e., free of multiple, potentially conflicting interpretations of a requirement.
- **Focused,** i.e., defined at the right level of detail (not too coarse-grained or too fine-grained).
    - E.g., “add profile item”, “update profile item”, “delete profile item” are too fine-grained for an ecommerce application. It can be “manage profile”. Not every button click deserves to be a separate use case
- **Relevant** to the project at hand rather than applicable to any project
    - E.g., “response time under 1 sec” should explain why 1 sec is applicable for this project (and not 3 or 0.5).
- **Feasible** to implement given the time/resource constraints.
    - E.g., “the server should be available 24/7”
- **Verifiable/Measurable,** i.e., where it is possible to clearly define corresponding test cases.
    - E.g., “it should perform well” is not measurable
- **Correctly classified:** functional requirements describe functionality that helps meet the needs of its users and stakeholders; Non-functional requirements specify criteria related to system qualities such as performance, reliability, security, and usability
    - E.g., specifying the performance criteria the system must meet, such as response times or throughput is not a functional requirement
    - “User should be able to log-in” is a functional rather than security requirement
- **Well-formatted,** with appropriate notations of use case diagram, success and failure scenarios, etc.

---

### Prompts Quality Attributes:

<!-- ![image](../img/promptQuality.jpg) -->
<img src="../img/promptQuality.jpg" alt="prompts" width="500" height="422">

---

### Assessment Methodology

Both artifacts (requirements specifications and ChatGPT prompts) were assessed using a similar methodology. Our complete rubric is linked below: 

- ##### [Grading Rubric](data/RequirementsandPromptRubric.xlsx).

The file includes two tabs, “Requirements Rubric” and "Prompt Rubric” corresponding to the two types of artifacts. 

Each super-row corresponds to an evaluation attribute, and each row inside the super-row presents concrete issues encountered during artifact evaluation.
For grading, a "severity" score from 0 to 3 is assigned for each concrete issue (0: absent, 1: rare, 2: moderate, 3: abundant). 
Then, the aggregate score (0-5) for each attribute is computed by translating the total sum of severity scores to the Likert scale (0-5) using the conversion criteria mentioned under the column "Conversion".
A score of 5 means “fully satisfactory”, 4 means “mostly satisfactory but minor issues, 3 means “mostly satisfactory but moderate-level of issue”, 2 means “major issues, 1 means “minimal attempt”, and 0 means “fully unsatisfactory”.
Finally, the scores from different attributes are aggregated as the weighted average of attribute scores.
The weights used for each attribute are presented in the column "Weight".
For requirements specifications, this weighted average corresponds to final score assigned to the deliverable.
For prompts, these scores are further combined across categories through simple averaging to compute the final score of the artifact.
