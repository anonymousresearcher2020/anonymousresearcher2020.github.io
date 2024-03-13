---
layout: default
title: Benchmark
nav_order: 2
has_children: false
permalink: /docs/benchmark
---
## InPreSS Case Study Subjects

### Here is the list of all clients failed after the upgrade (168 client-library pairs):
* ###  [Failed Clients](../assets/AllFailedClients.xlsx)
---

### Here is the list of libraries categorized in 8 bins (84 unique libraries):
* ### [List of Libraries and bins](../assets/Libs.xlsx)
---

### Here, there is a page for each subject including the client and the library GitHub links as well as the zip files of the source code for the specific versions used in the study: 

* ### [Subject#1 (Jettison/Xstream)](data/s1.md)

* ### [Subject#2 (Square-Dagger/Modelmapper)](data/s2.md)

* ### [Subject#3 (Moshi/Retrofit)](data/s3.md)

* ### [Subject#4 (Jackson-Core/Mockserver)](data/s4.md)

* ### [Subject#5 (Antlr4-Runtime/Fizzed-Rocker)](data/s5.md)

* ### [Subject#6 (Httpcomponents-Client/Wasabi)](data/s6.md)

* ### [Subject#7 (Jackson-Databind/OpenAPI-Generator)](data/s7.md)

* ### [Subject#8 (Alibaba-Druid/Dble)](data/s8.md)
---

### As running the client and library projects needs merging two projects in one and creating a merged jar to run Slicer4J, we provide the merged and ready to run folders in a Google Drive folder (https://drive.google.com/file/d/1XZ_lJG7cgMJvOSvlURCJgSG3Hu-cFvWM/view?usp=share_link).
---
---

## Defects4J
### Moreover, this prototype can be run on Defects4J bugs (https://github.com/llmhyy/defects4j). You can checkout the buggy version and fixed version by a script (https://github.com/llmhyy/defects4j/blob/master/checkout.sh) and get the bug file structure as follows:

|__ Chart<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|__ 1 (bug_id)<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|__ 2 (bug_id)<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|__ ...<br />
|__ Closure<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|__ 1 (bug_id)<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|__ 2 (bug_id)<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|__ ...<br />
