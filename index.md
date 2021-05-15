---
layout: default
title: Home
nav_order: 1
description: "LibRE: Summarizing Library Changes to Explain Client Regression Failures"
permalink: /
---

### LibRE: Summarizing Library Changes to Explain Client Regression Failures

---

Software nowadays relies on a large number of third-party libraries, which encapsulate functionality used by multiple software systems. 
When a library is upgraded, e.g., to add new features or fix bugs and security vulnerabilities, clients often 
need to upgrade their code as well, to integrate it with the new library version. 
In practice, they often postpone doing so as upgrades consume time, require handling complex scenarios and undocumented changes, and can introduce unexpected failures. 

A number of approaches have been recently proposed to help developers debug upgrade-related failures (a.k.a. regression failures). 
Most such approaches rely on dynamic analysis of execution traces of the original/correct and new/faulty software versions,
helping developers to pinpoint reasons for failures. 
They aim at identifying the root cause of a regression failure and explain how the failure is propagated from its origin to its manifestation site. 
While such explanations help library developers, the internal details of the library code are of low relevance to client developers. 
In this paper, we propose a formalism and an approach for summarizing the failure propagation paths in the library code, 
producing a concise representation that can explain the essence of the relevant changes in a library and their effect on the failure in the client code. 
We demonstrate how our approach, implemented in a tool called LibRE, can help explain failures induced by library changes, including those where no documentation is available. 

This website contains artifacts used for experimental evaluation described in the paper. We anonymized all information which can be related back to the authors of the paper.
