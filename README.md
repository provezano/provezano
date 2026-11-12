<h1 align="center">Hi 👋, I'm Felipe Coutinho!</h1>

<p align="center">
  Independent researcher in machine learning and operations research · AI Engineer · Data Scientist
</p>

<p align="center">
  <a href="https://orcid.org/0000-0001-7206-5856"><img src="https://img.shields.io/badge/ORCID-0000--0001--7206--5856-A6CE39?style=for-the-badge&logo=orcid&logoColor=white" alt="ORCID"></a>
  <a href="https://www.linkedin.com/in/provezano"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://github.com/provezano"><img src="https://img.shields.io/github/followers/provezano?style=for-the-badge&label=Follow" alt="GitHub followers"></a>
</p>

I build applied AI systems and do reproducible research in machine learning and operations research: how tabular foundation models are evaluated, when density-based clustering output can be trusted, and when lower bounds prove scheduling optima.
I hold a **Master's degree in Computer Science and Computational Mathematics** from the **University of São Paulo**.

## Open-source contributions

Fixes and documentation I contributed upstream while doing this research.

- **[coin-or/SYMPHONY #248](https://github.com/coin-or/SYMPHONY/pull/248)**: fixed four bugs that crashed the VRP application on master or made it return wrong optima when branching on cuts (a NULL MIP-info dereference, a build-flag mismatch, user cut candidates overwritten by a built-in rule, and a ranged-row convention).
- **[mhahsler/dbscan #101](https://github.com/mhahsler/dbscan/pull/101)**: documented how to set HDBSCAN's minimum cluster size separately from `minPts`.
- **[TutteInstitute/fast_hdbscan #94](https://github.com/TutteInstitute/fast_hdbscan/pull/94)**: clarified that `min_samples` does not count the point itself.

Bug reports with reproductions: [NVIDIA/cuml #8879](https://github.com/NVIDIA/cuml/issues/8879) (HDBSCAN with `nn_descent`), [fast_hdbscan #93](https://github.com/TutteInstitute/fast_hdbscan/issues/93) (`cluster_selection_epsilon` returning the root), [scikit-learn-contrib/hdbscan #757](https://github.com/scikit-learn-contrib/hdbscan/issues/757) (`alpha` ignored by the Borůvka algorithms).

## Selected public projects

### Research and machine learning

- **[Stratified Few-Label Protocols](https://github.com/provezano/stratified-few-label-protocols)**: reproducible research on how stratified few-label evaluation protocols can overstate macro-averaged metrics for tabular foundation models. Includes analysis plans, stored results, audits and regeneration scripts.
- **[Learning with Local and Global Consistency](https://github.com/provezano/lgc)**: implementation of the graph-based semi-supervised learning algorithm.
- **[Statistics Methods for ML Training](https://github.com/provezano/statistics-methods-for-ml-training)**: study materials and notebooks on the statistical methods used in machine learning.

### AI products and data applications

- **[AI Data Analyst](https://github.com/provezano/ecommerce-data-analyst-agent)**: conversational data analysis for e-commerce using CrewAI.
- **[Churn Prediction for a School](https://github.com/provezano/churn_prediction)**: Portuguese-language school churn prediction project.

## Focus areas

`Tabular foundation models` · `Clustering` · `Scheduling and lower bounds` · `Reproducible research` · `Applied AI`

## Connect

- [ORCID](https://orcid.org/0000-0001-7206-5856)
- [LinkedIn](https://www.linkedin.com/in/provezano)
