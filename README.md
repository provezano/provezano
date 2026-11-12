<h1 align="center">Felipe Provezano Coutinho</h1>

<p align="center">
  Researcher in machine learning and operations research · Applied AI engineer
</p>

<p align="center">
  <a href="https://orcid.org/0000-0001-7206-5856"><img src="https://img.shields.io/badge/ORCID-0000--0001--7206--5856-A6CE39?style=for-the-badge&logo=orcid&logoColor=white" alt="ORCID"></a>
  <a href="https://www.linkedin.com/in/provezano"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
</p>

My research asks when a standard result can be trusted: whether an evaluation protocol changes the scores it reports, whether a clustering survives a small change of its parameter, and whether a simple lower bound already proves a schedule optimal. Each study ships with its code, data and the checks needed to reproduce it.
I hold a **Master's degree in Computer Science and Computational Mathematics** from the **University of São Paulo**.

## Research

### Evaluating tabular foundation models
- **Why Stratified Few-Label Evaluation Changes the Scores of Tabular Foundation Models: An Exact Bayesian Account.** Preprint, [doi:10.5281/zenodo.23967812](https://doi.org/10.5281/zenodo.23967812).
- **[stratified-few-label-protocols](https://github.com/provezano/stratified-few-label-protocols)**: code, analysis plans, stored results and regeneration scripts for a study of how stratified few-label protocols can overstate macro-averaged metrics.

### Reliable density-based clustering
- **Why HDBSCAN\*'s flat clustering changes with minPts: shrinking clusters, a one-run predictor and a certificate.** Preprint, [doi:10.5281/zenodo.24039671](https://doi.org/10.5281/zenodo.24039671).
- **[minpts-check](https://github.com/provezano/minpts-check)**: a Python package that checks, from a single HDBSCAN\* run, which clusters are at risk when `min_samples` changes. It works with `sklearn.cluster.HDBSCAN` and the `hdbscan` package.

### Scheduling, lower bounds and optimality proofs
- **Lower bounds explain why the distributed assembly permutation flowshop benchmark is easy.** Data and code, including the schedules and their lower bounds: [doi:10.5281/zenodo.24038696](https://doi.org/10.5281/zenodo.24038696).
- **Union-of-predecessors bounds and a forward–backward local search for multi-door cross-dock truck scheduling.** Code and data: [doi:10.5281/zenodo.23933867](https://doi.org/10.5281/zenodo.23933867).

## Open-source contributions

Fixes and documentation I contributed upstream while doing this research.

- **[coin-or/SYMPHONY #248](https://github.com/coin-or/SYMPHONY/pull/248)**: fixed four bugs that crashed the VRP application on master or made it return wrong optima when branching on cuts (a NULL MIP-info dereference, a build-flag mismatch, user cut candidates overwritten by a built-in rule, and a ranged-row convention).
- **[mhahsler/dbscan #101](https://github.com/mhahsler/dbscan/pull/101)**: documented how to set HDBSCAN's minimum cluster size separately from `minPts`.
- **[TutteInstitute/fast_hdbscan #94](https://github.com/TutteInstitute/fast_hdbscan/pull/94)**: clarified that `min_samples` does not count the point itself.

Bug reports with reproductions: [NVIDIA/cuml #8879](https://github.com/NVIDIA/cuml/issues/8879) (HDBSCAN with `nn_descent`), [fast_hdbscan #93](https://github.com/TutteInstitute/fast_hdbscan/issues/93) (`cluster_selection_epsilon` returning the root), [scikit-learn-contrib/hdbscan #757](https://github.com/scikit-learn-contrib/hdbscan/issues/757) (`alpha` ignored by the Borůvka algorithms).

## Other projects

- **[lgc](https://github.com/provezano/lgc)**: an implementation of Learning with Local and Global Consistency, the graph-based semi-supervised algorithm of Zhou et al. (2004).
- **[ecommerce-data-analyst-agent](https://github.com/provezano/ecommerce-data-analyst-agent)**: conversational data analysis for e-commerce with CrewAI.
