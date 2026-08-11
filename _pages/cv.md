---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Download full CV (PDF)]({{ base_path }}/files/Hui-Sun-CV.pdf){: .btn .btn--primary}

Education
======
* Ph.D. in Computer Science, North Carolina State University, Aug. 2023 - Present
  * Advisor: Dr. Wesley K. G. Assunção
  * Research Interests: LLMs, Software Engineering, HCI, AI4AI, AI4SE, Agents
* M.S. in Computer Science, University of Florida, Aug. 2020 - Dec. 2022
* B.E. in Software Engineering, Xidian University, Aug. 2015 - Jun. 2019

Work experience
======
* May 2026 - Aug. 2026: Core-ML Ph.D. SWE Intern
  * {% include google-colored.html %} Inc., Mountain View, CA
  * Host: Ann Yan
  * Architected an Autonomous Agent Platform: Built an end-to-end LLM agent in Python to automate migrating PyTorch models onto {% include google-colored.html %} Cloud TPUs; implemented a 20+ tool MCP server covering AST analysis, automated dependency resolution, and vector RAG.
  * Engineered Closed-Loop Diagnostics & Verification: Developed a two-stage self-healing pipeline using dry-run profiling to detect XLA compiler CPU fallbacks before full-scale training; delivered a production-grade platform across 35+ modules.

* Jan. 2023 - Aug. 2023: Software Engineer, Full Time
  * PAX Technology Inc., Jacksonville, FL
  * Mentor: Yurii Maidaniuk
  * Contributed to a return merchandise authorization system managing repairs and tracking equipment for over 3,400 client companies in North America, from initial documentation to final deployment.
  * Participated in developing a warehouse management system managing 1.4 million devices.
  * Built the counting tax function of a Key Injection purchase system using Spring Boot, generating approximately $840,000 in annual revenue.
  * Contributed to the CyberLab Function, a government-approved robotics kit used by global testing teams to evaluate financially sensitive features such as PIN entry.

* Mar. 2021 - Jun. 2021: Software Engineering Intern
  * IBM, Shanghai, CN
  * Developed and deployed a monitoring function for the Development Bank of Singapore's bank card system, enhancing security across all branches in Asia.
  * Used IBM WebSphere to control and deploy different versions of the Bank Card System, helping manage $134.5 billion in deposits for DBS Bank.
  * Wrote a product requirement document defining raw data formats to support IBM's Singapore and Hong Kong teams in developing Blacklist/Whitelist functions.

Selected projects
======
* **Evaluating Language Models on Cross-Language Code Functional Equivalence** (Aug. 2025 – May 2026), {% include google-colored.html %} Cloud, FUNCAP, CNPq funded project
  * Built PolyHuman, the first dataset for evaluating cross-language code functional equivalence on human-written code (C++/Java/Python, 5,035 problems from CodeContests, 15 sub-tasks).
  * Systematic evaluation of 9 open- and closed-source models shows accuracy drops from 0.998 on synthetic code to 0.84 on human-written code.
  * Manual analysis of 81 misjudged cases produced a three-tier failure hierarchy: Knowledge Failures (21%), Abstraction-Level Reasoning Failures (53%), and dataset-labeling issues (19%).

* **Understanding Reviewer Concerns on Test Code in Pull Requests** (Dec. 2024 – Mar. 2025), NSF funded project in the WISER lab
  * First analysis of GitHub Actions' influence on test code review, leveraging 213,511 pull requests and 600,905 review comments from six large-scale GitHub projects.
  * Found that adoption of GitHub Actions significantly reduced reviewer and developer attention to test code.

* **Software-hardware Co-design Differential Privacy** (Aug. 2023 – May 2024), NSF funded project in the Network Lab
  * First to leverage hardware transistor degradation under voltage drop as a noise source for Local Differential Privacy.
  * Proposed SRAM_DP, a hardware-software co-design for differential privacy on semi-structured data. Published at ISVLSI 2024.

Skills
======
* Agent building, RAG, XLA, Java, Python, C++, R, Matlab, SQL, J2EE, ASP.NET, AI4SE, LLMs, LaTeX, Git
* Frameworks & Libraries: Spring Boot, MyBatis, PyTorch, scikit-learn, Ollama, Pandas, HuggingFace

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
