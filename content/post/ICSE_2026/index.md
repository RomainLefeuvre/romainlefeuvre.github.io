---
title: Mining Software Repository (MSR) conference presentation
date: '2026-04-13'
summary: In person presentation of our work at MSR 2026, co-located with ICSE 2026 at Rio de Janeiro
---

Empirical software engineering research depends heavily on datasets of software repository artifacts. Since studying an entire population is rarely feasible, researchers rely on sampling — selecting a subset of elements from an accessible portion of the population. But in practice, obtaining a sample from a software archive is never a single step: it involves filtering, grouping, drawing randomly, and merging intermediate datasets. These **multistage processes** don't fit neatly into the classical population → sampling frame → sample framework, and describing them in natural language leaves critical decisions implicit, ambiguous, and impossible to reproduce.

As part of my PhD, we tackle two related challenges: (1) how to **explicitly describe** complex multistage sampling strategies, and (2) how to **reason about their representativeness** to support generalization claims.

## A DSL for sampling workflows

We propose a **Domain-Specific Language (DSL)** that models sampling strategies as workflows: each node represents a collection of items (an intermediate dataset), and each arc a transformation — Filter, Random, Systematic, Grouping, Set operators. Classical strategies like stratified random sampling or cluster sampling emerge naturally as compositions of these primitives.

The DSL is implemented as a **Python fluent API**, executable on real datasets. We provide a built-in connector to [Software Heritage](https://www.softwareheritage.org/) datasets, enabling workflows to run directly on an a datasets of 27M+ repositories.

## Automatic representativeness reasoning

Having an explicit workflow structure opens the door to automated statistical analysis. The tool derives the needed statistical indicators to justify representativeness arguments in *theoretical generalization reasoning* between a sample and its sampling frame :  

- **Distribution similarity** — Kolmogorov-Smirnov and Chi-square tests comparing each intermediate set to its parent
- **Sample size adequacy** — Cochran's formula applied at each Random Operator to verify the sample is statistically sufficient
- **Breadth analysis** — coverage of metadata classes across the sampling frame





## Try it

```bash
pip install sampling-mining-workflows-dsl
```

-  **Paper:** [hal.science/hal-05478146v2](https://hal.science/hal-05478146v2)
-  **Code & replication package:** [github.com/RomainLefeuvre/SamplingMiningWorkflowDSL](https://github.com/RomainLefeuvre/SamplingMiningWorkflowDSL)