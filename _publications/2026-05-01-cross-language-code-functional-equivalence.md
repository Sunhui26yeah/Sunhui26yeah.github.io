---
title: "Evaluating Language Models on Cross-Language Code Functional Equivalence"
collection: publications
category: conferences
permalink: /publication/2026-cross-language-code-functional-equivalence
excerpt: 'Introduces PolyHuman, the first dataset for evaluating cross-language code functional equivalence on human-written code, and shows LLMs are far less reliable on human-written code than on synthetic code.'
date: 2026-05-01
venue: 'International Symposium on Empirical Software Engineering and Measurement (ESEM 2026)'
citation: 'Hui Sun, Anderson Uchôa, Rohit Gheyi, and Wesley K. G. Assunção. (2026). &quot;Evaluating Language Models on Cross-Language Code Functional Equivalence.&quot; <i>International Symposium on Empirical Software Engineering and Measurement (ESEM 2026)</i>. Google Cloud Research Award Supported.'
---
We introduce PolyHuman, the first dataset for evaluating cross-language code functional equivalence on human-written code (C++/Java/Python, 5,035 problems from CodeContests, 15 sub-tasks), addressing a gap left by prior benchmarks that focus on a single language or synthetically transformed code. A systematic evaluation of 9 open- and closed-source models shows accuracy drops from 0.998 on synthetic code to 0.84 on human-written code; prediction bias is driven by the model rather than the language, and as problem difficulty rises, models increasingly misclassify non-equivalent code as equivalent. Manual analysis of 81 misjudged cases reveals a three-tier failure hierarchy: Knowledge Failures (21%), Abstraction-Level Reasoning Failures (53%), and dataset-labeling issues (19%), motivating complementary multi-model strategies over single-model use.
