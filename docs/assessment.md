---
layout: default
title: Artifacts Assessment 
nav_order: 4
has_children: false
permalink: /docs/assessment
---
The complete rubric we used to assess requirements specifications and ChatGPT prompts is linked below: 

- ##### [Grading Rubric](data/RequirementsandPromptRubric.xlsx).

---

### Requirements Assessment:

The first tab of the file ("Course-defined Requirements Components") lists six requirements specification components defined in the course: actors, use cases, use case diagram, success scenarios, failure scenarios, and non-functional requirements. 

The second tab (“Requirements Rubric”) list the requirements quality attribute, listed in the paper and described below in more detail. 

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

For each quality attribute, we list a set of concrete issues, such as missing or incomplete descriptions, logical or factual errors, and more, identified during artifact evaluation.

Each issue is assigned a severity level from 0 – absent, to 1 – rare, 2 – moderate, 3 – abundant. Severity ranks are then added and normalized for each attribute,
translated into a 0-5 scale attribute score (the higher the
better), based on the conversion criteria provided in the "Conversion" column. 
Finally, the scores from different attributes are aggregated as the weighted average of attribute scores.
The weights used for each attribute are presented in the column "Weight".

---

### Prompt Assessment:

Prompt quality attributes are listed in the paper and summarized in the figure below. 

<!-- ![image](../img/promptQuality.jpg) -->
<img src="../img/promptQuality.jpg" alt="prompts" width="500" height="422">

The third tab of the file above, “Prompt Rubric - How to Ask (H)”, lists concrete issues for each of the 28 quality factors (7 attributes × 4 cross-cutting qualities).
As with requirements, when grading, each issue was assessed by severity and converted into a numeric score on 0 to 5 scale (the higher the better). These scores were then averaged across categories to produce an overall score for the "How to Ask" (denoted by H).

The fourth tab, "Prompt Rubric - What to Ask (W)”, lists all requirements components (as in the first tab). In our evaluation, ChatGPT conversations were checked for the presence of at least one request or question related to each of the six requirements components. The resulting "What to Ask" score is the fraction of requirements components students consulted the ChatGPT about out of all 6 components (denoted by H).

Then, the final score is calculated as H x W.
