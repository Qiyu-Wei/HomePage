---
title: "Gradient-based Sample Selection for Faster Bayesian Optimization"
authors:
  - admin
  - Haowei Wang
  - Zirui Cao
  - Songhao Wang
  - Richard Allmendinger
  - Mauricio A. Álvarez

date: "2025-04-12T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-04-12T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "arXiv preprint arXiv:2504.07742"
publication_short: "arXiv"

abstract: "Standard Bayesian Optimization (BO) typically relies on Gaussian Process (GP) surrogate models. Because fitting a GP has $O(n^3)$ computational complexity (where $n$ is the number of data samples), BO becomes difficult to scale to large-budget scenarios. In this work, we propose a gradient-based sample selection (GSSBO) method designed to improve the computational efficiency of BO. Instead of using the entire dataset to fit the GP, the model is constructed using only a selected subset of samples. These samples are chosen by leveraging gradient information to eliminate redundancy while maintaining the diversity and representativeness of the dataset. Theoretical analysis in the paper provides explicit sublinear regret bounds for the framework. Experimental results on both synthetic and real-world tasks indicate that the method significantly reduces GP fitting costs while maintaining performance comparable to baseline methods."

summary: "We propose GSSBO, a gradient-based sample selection method that scales Bayesian Optimization to large-budget scenarios by selecting a representative subset of historical observations based on gradient information."

tags: []
featured: false

---

