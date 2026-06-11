---
title: "Counterfactual Credit Guided Bayesian Optimization"
authors:
  - admin
  - Haowei Wang
  - Richard Allmendinger
  - Mauricio A. Álvarez

date: "2026-05-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2026-05-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "In International Conference on Artificial Intelligence and Statistics (AISTATS)"
publication_short: "In AISTATS"

abstract: "While traditional Bayesian Optimization (BO) often focuses on building a globally accurate surrogate model (e.g., via Gaussian processes) to represent the entire objective function, practitioners are frequently more interested in identifying the global optimum as quickly as possible. The authors argue that it is often inefficient to treat all historical observations as equally important for this specific goal. To address this, we introduce Counterfactual Credit Guided Bayesian Optimization (CCGBO), a framework that uses 'counterfactual credit' to explicitly quantify the contribution of individual historical observations to the discovery of the optimum. By incorporating these counterfactual credit scores into the acquisition function, the model can more effectively allocate sampling resources toward regions where the global optimum is most likely to reside. We prove that CCGBO maintains sublinear regret and demonstrate through empirical evaluations on both synthetic and real-world benchmarks that the method accelerates convergence to the global optimum compared to standard baselines."

summary: "We introduce CCGBO, a Bayesian Optimization framework that uses counterfactual credit to quantify historical observations' contribution to discovering the optimum, accelerating convergence."

tags: []
featured: true

---

