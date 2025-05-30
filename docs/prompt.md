---
layout: default
title: Prompt Assessment
nav_order: 4
has_children: false
permalink: /docs/prompt
---
### Prompt Quality Metric:

<!-- ![image](../img/promptQuality.jpg) -->
<img src="../img/promptQuality.jpg" alt="prompts" width="500" height="422">

---

### Prompt Quality Grading and Rubric: 
All artifacts produced by students in the course, i.e., prompts (PA and PB), were manually graded by two authors of this paper, who were also in the teaching staff of the course. We assigned 0-5 scale for the quality attributes of the metric. The score of 5 means “fully satisfactory”, 4 means “mostly satisfactory but minor details missing”, 3 means “mostly satisfactory but moderate-level of details missing”, 2 means “major details missing”, 1 means “minimal attempt”, and 0 means “fully unsatisfactory”. The graders cross-validated their marks and all disagreement (6% disagreement rate) were resolved with a third author, who was also involved in course instruction.

We have provided the complete rubric in the file linked below: 

- ##### [Prompt Grading Rubric](data/RequirementsandPromptRubric.xlsx)

The “Prompt Rubric" tab lists attributes used for grading the chatgpt conversations. 
Each meta-row represents a high-level attribute, and each row within it corresponds to one of four quality dimensions: Complete, Clear, Relevant, and Focused.
For each quality, we list specific issues observed during artifact evaluation.
For grading, a "severity" score from 0 to 3 is assigned for each concrete issue (0: absent, 1: rare, 2: moderate, 3: abundant). 
Then, the aggregate score (0-5) for each attribute is computed by translating the total sum of severity scores to the likert scale using the conversion criteria mentioned under the column "Conversion".
Finally, the scores from different attributes are aggregated as the weighted average of each attribute. The weights used for each attribute are presented in the column "Weight".
Note that completeness is given higher weight across all categories/artifacts as missing/incomplete information reduces the likelihood of seeing other issues; thus, is more important.
The final weighted average score is shown in the column "Weighted. Avg".
The final score assigned to the groups' interactions with ChatGPT is computed by simply averaging the scores of each category.