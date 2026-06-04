# Graph Report - WK6  (2026-06-04)

## Corpus Check
- 10 files · ~5,165 words
- Verdict: corpus is large enough that graph structure adds value.

## Summary
- 104 nodes · 93 edges · 18 communities (15 shown, 3 thin omitted)
- Extraction: 99% EXTRACTED · 1% INFERRED · 0% AMBIGUOUS · INFERRED: 1 edges (avg confidence: 0.9)
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `bf058f57`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- [[_COMMUNITY_Community 0|Community 0]]
- [[_COMMUNITY_Community 1|Community 1]]
- [[_COMMUNITY_Community 2|Community 2]]
- [[_COMMUNITY_Community 3|Community 3]]
- [[_COMMUNITY_Community 4|Community 4]]
- [[_COMMUNITY_Community 5|Community 5]]
- [[_COMMUNITY_Community 6|Community 6]]
- [[_COMMUNITY_Community 7|Community 7]]
- [[_COMMUNITY_Community 8|Community 8]]
- [[_COMMUNITY_Community 9|Community 9]]
- [[_COMMUNITY_Community 10|Community 10]]
- [[_COMMUNITY_Community 12|Community 12]]
- [[_COMMUNITY_Community 13|Community 13]]
- [[_COMMUNITY_Community 17|Community 17]]

## God Nodes (most connected - your core abstractions)
1. `W6 — Probabilistic Models & Bayesian Inference` - 13 edges
2. `Week 6 Task Progress` - 12 edges
3. `SUBMISSION CHECKLIST` - 9 edges
4. `Git LFS Guide for Large Model Artifacts` - 8 edges
5. `fuseAiF_wk6_probabilistic_models` - 7 edges
6. `PART 3 · MULTIVARIATE GAUSSIANS` - 7 edges
7. `PART 6 · MCMC — BAYESIAN LOGISTIC REGRESSION` - 7 edges
8. `graphify` - 6 edges
9. `PART 1 · THE ESTIMATION TRINITY — MLE, MAP, FULL BAYES` - 6 edges
10. `PART 2 · SEQUENTIAL BAYESIAN UPDATING & DIRICHLET-MULTINOMIAL` - 6 edges

## Surprising Connections (you probably didn't know these)
- `graphify` --references--> `graphify`  [EXTRACTED]
  .github/copilot-instructions.md → GEMINI.md
- `Overview` --references--> `Master Task Plan`  [EXTRACTED]
  README.md → W6_TaskPlan.md

## Import Cycles
- None detected.

## Communities (18 total, 3 thin omitted)

### Community 0 - "Community 0"
Cohesion: 0.25
Nodes (8): Part 1 (Estimation Trinity), Part 2 (Sequential Updating), Part 3 (Multivariate Gaussians), Part 4 (PGMs), Part 5 (GP Regression), Part 6 (MCMC), Submission Artefacts, SUBMISSION CHECKLIST

### Community 1 - "Community 1"
Cohesion: 0.15
Nodes (12): Notes, Notes, Part 1 — Estimation Trinity, Part 2 — Sequential Updating & Dirichlet-Multinomial, Part 3 — Multivariate Gaussians, Part 4 — Probabilistic Graphical Models, Part 5 — Gaussian Process Regression, Part 6 — MCMC Bayesian Logistic Regression (+4 more)

### Community 2 - "Community 2"
Cohesion: 0.17
Nodes (11): ENVIRONMENT SETUP, KNOWN GOTCHAS, Master Task Plan · Fusemachines AI Fellowship, PART 4 · PROBABILISTIC GRAPHICAL MODELS, Q11 · Build and fit Bayesian Network `[ ]`, Q12 · Structure sensitivity: two competing DAGs `[ ]`, Q13 · Markov Random Field `[ ]`, QUICK REFERENCE (+3 more)

### Community 3 - "Community 3"
Cohesion: 0.17
Nodes (9): graphify, graphify-out/graph.json, graphify-out/GRAPH_REPORT.md, graphify, graphify explain, graphify query, /graphify command, graphify-out/wiki/index.md (+1 more)

### Community 4 - "Community 4"
Cohesion: 0.22
Nodes (8): fuseAiF_wk6_probabilistic_models, How to use this repo, Notes, Overview, Repository structure, Setup, Submission artifacts, Master Task Plan

### Community 5 - "Community 5"
Cohesion: 0.22
Nodes (8): Best practice, Cloning this repo in the future, Git LFS Guide for Large Model Artifacts, How to add a new model file, If you already committed a large file, Setup steps, What was added, Why use Git LFS

### Community 6 - "Community 6"
Cohesion: 0.29
Nodes (7): PART 6 · MCMC — BAYESIAN LOGISTIC REGRESSION, Q18 · Feature scaling rationale + model spec `[ ]`, Q19 · Convergence diagnostics `[ ]`, Q20 · Prior sensitivity check `[ ]`, Q21 · Posterior analysis + frequentist comparison `[ ]`, Q22 · Save MCMC trace `[ ]`, ✍️ Reflect 6 `[ ]`

### Community 7 - "Community 7"
Cohesion: 0.33
Nodes (6): PART 1 · THE ESTIMATION TRINITY — MLE, MAP, FULL BAYES, Q1 · Extract experimental groups `[ ]`, Q2a · Compute MLE, MAP, pull table `[ ]`, Q2b · Plot 3 posterior PDFs `[ ]`, Q3 · Monte Carlo P(θ_A > θ_B) `[ ]`, ✍️ Reflect 1 `[ ]`

### Community 8 - "Community 8"
Cohesion: 0.33
Nodes (6): PART 2 · SEQUENTIAL BAYESIAN UPDATING & DIRICHLET-MULTINOMIAL, Q4 · Implement `update_posterior()` `[ ]`, Q5 · Sequential update — posterior evolution plot `[ ]`, Q6 · Decision boundary P(θ > 0.25) vs n `[ ]`, Q7 · Dirichlet-Multinomial `[ ]`, ✍️ Reflect 2 `[ ]`

### Community 9 - "Community 9"
Cohesion: 0.33
Nodes (6): PART 5 · GAUSSIAN PROCESS REGRESSION — MAUNA LOA CO₂, Q14 · Load Mauna Loa `[ ]`, Q15 · Kernel design rationale (fill table BEFORE coding) `[ ]`, Q16 · Gap experiment `[ ]`, Q17 · Extrapolation and confidence boundary `[ ]`, ✍️ Reflect 5 `[ ]` (exactly two sentences)

### Community 17 - "Community 17"
Cohesion: 0.33
Nodes (6): PART 3 · MULTIVARIATE GAUSSIANS, Q10 · 3D Covariance + Condition Number + Marginalisation `[ ]`, Q8a · Fit 2D Gaussian `[ ]`, Q8b · Scatter + 1σ/2σ/3σ confidence ellipses `[ ]`, Q9 · Conditional Gaussian P(MonthlyCharges | tenure=24) `[ ]`, ✍️ Reflect 3 `[ ]`

## Knowledge Gaps
- **73 isolated node(s):** `Repo artifacts found`, `Repo maintenance`, `Part 1 — Estimation Trinity`, `Part 2 — Sequential Updating & Dirichlet-Multinomial`, `Part 3 — Multivariate Gaussians` (+68 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **3 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `W6 — Probabilistic Models & Bayesian Inference` connect `Community 2` to `Community 0`, `Community 6`, `Community 7`, `Community 8`, `Community 9`, `Community 17`?**
  _High betweenness centrality (0.201) - this node is a cross-community bridge._
- **Why does `SUBMISSION CHECKLIST` connect `Community 0` to `Community 17`, `Community 2`?**
  _High betweenness centrality (0.061) - this node is a cross-community bridge._
- **Why does `PART 6 · MCMC — BAYESIAN LOGISTIC REGRESSION` connect `Community 6` to `Community 2`?**
  _High betweenness centrality (0.053) - this node is a cross-community bridge._
- **What connects `Repo artifacts found`, `Repo maintenance`, `Part 1 — Estimation Trinity` to the rest of the system?**
  _74 weakly-connected nodes found - possible documentation gaps or missing edges._