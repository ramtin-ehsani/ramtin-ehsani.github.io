+++
title = "Research Projects"
author = "Gabor Parti"
date = "2022-09-01"
plotly = "true"
+++

[<i class="fa fa-graduation-cap" aria-hidden="true"></i> **SOAR Lab**](https://soar-lab.github.io/)

>  I work in the SOAR Lab, where we advance software engineering with large language models and data-driven methods. Below are some of my recent projects and publications:

{{< project
   title="Hierarchical Knowledge Injection for LLM-based Program Repair"
   venue="ASE 2025"
   what="A layered retrieval pipeline (bug → repository → project) that supplies LLMs with the right level of context for the purpose of automated program repair."
   why="Improves correctness across different bug types and shows which levels of context LLMs actually need to generate effective repairs."
   paper="https://arxiv.org/abs/2506.24015"
   code="https://anonymous.4open.science/r/llm-apr-knowledge-injection-1BB7/README.md"
   img="./proj1.png"
>}}

{{< project
   title="Towards Detecting Prompt Knowledge Gaps for Improved LLM-guided Issue Resolution"
   venue="MSR 2025"
   what="A tool (browser extension) that detects missing context, specifications, and unclear prompts in developer–LLM conversations that could hinder bug fixing."
   why="Helps developers craft better prompts so LLMs can return correct fixes faster."
   paper="https://ieeexplore.ieee.org/abstract/document/11025628"
   code="https://github.com/SOAR-Lab/prompt-knowledge-gap"
   img="./proj2.png"
>}}

{{< project
   title="What Characteristics Make ChatGPT Effective for Software Issue Resolution?"
   venue="Empirical Software Engineering 2025"
   what="Analyzes a large corpus of developer–ChatGPT conversations to understand why developers seek help for software bugs and when these interactions lead to successful resolutions."
   why="Provides empirical insights into the qualities of effective developer–AI conversations for software problem solving."
   paper="https://arxiv.org/abs/2506.22390"
   code="https://anonymous.4open.science/r/llm_issue_resolution_analysis-2C53/README.md"
   img="./proj3.png"
>}}

{{< project
   title="A Comprehensive Annotated Dataset of Locked GitHub Issue Threads"
   venue="MSR 2024"
   what="Introduces a large annotated dataset of GitHub issue threads that were locked due to incivility, capturing a range of uncivil interactions in open-source communities."
   why="Offers a rich resource for studying online incivility and designing interventions to improve open-source communities."
   paper="https://dl.acm.org/doi/abs/10.1145/3643991.3644887"
   code="https://github.com/vcu-swim-lab/incivility-dataset"
   img="./proj4.png"
>}}

{{< project
   title="Exploring Moral Principles Exhibited in OSS Communications"
   venue="FSE 2023, NLBSE 2025"
   what="An NLP study of open-source discussions uncovering moral principles behind developer arguments, paired with an ML-based tool to flag toxic conversations."
   why="Shows how moral reasoning can improve toxic conversation detection in open-source projects."
   paper="https://dl.acm.org/doi/abs/10.1145/3611643.3613077"
   code="https://github.com/SOAR-Lab/toxicity-morality-analysis"
   img="./proj5.png"
>}}