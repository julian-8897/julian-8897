# Hi, I'm Julian Chan

PhD researcher at the **University of Surrey** working on **Machine Learning for Dynamical Systems** in astrophysics. I build differentiable surrogates for expensive physical simulators, inverse methods for physical-parameter recovery, and research tooling for scientific ML.

First-author work accepted to **MNRAS**; **Honourable Mention** at the Tesseract Hackathon 2025 (Pasteur Labs).

[![arXiv](https://img.shields.io/badge/arXiv-2601.13019-b31b1b?style=flat&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2601.13019)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0a66c2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/julian-chan-a86b2921b)
[![Email](https://img.shields.io/badge/Email-ea4335?style=flat&logo=gmail&logoColor=white)](mailto:julianchan8897@gmail.com)

---

## Selected Work

**Neural-ODE Surrogates for N-body Simulations** &nbsp;·&nbsp; _Accepted to MNRAS_
Parameter-conditioned Neural ODEs as surrogates for N-body galaxy-merger simulations — median fractional error ~10⁻², zero-shot interpolation/extrapolation across unseen parameters, at a fraction of direct simulation cost. End-to-end autodiff through the surrogate recovers physically meaningful parameter sensitivities.
[![arXiv](https://img.shields.io/badge/arXiv-2601.13019-b31b1b?style=flat&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2601.13019)

**Differentiable Inverse Methods for PDE Parameter Recovery** &nbsp;·&nbsp; _Honourable Mention, Tesseract Hackathon 2025_
Burgers viscosity recovery packaged as three swappable Tesseract components — a differentiable spectral solver, a JAX/PyTorch PINN, and an amortized flow-matching posterior (FMPE). Recovers viscosity three ways through one JAX/Optax loop; posterior validated with SBC and TARP coverage. Ongoing collaboration with Pasteur Labs.
[![GitHub](https://img.shields.io/badge/GitHub-Repo-181717?style=flat&logo=github&logoColor=white)](https://github.com/julian-8897/tesseract-pinn-inverse-burgers)
[![Write-up](https://img.shields.io/badge/Write--up-Pasteur%20Labs-6f42c1?style=flat)](https://pasteurlabs.ai/insights/tesseract-hackathon-winners/)

**Zero-Shot Parametric Neural Operators for Chaotic Dynamics**
Extended CFO (ICLR 2026) to a parametric setting: a single PyTorch model that generalises zero-shot across Lorenz systems to unseen parameters without retraining, holding accuracy under sparse, irregularly-sampled observations where autoregressive baselines degrade.
[![GitHub](https://img.shields.io/badge/GitHub-Repo-181717?style=flat&logo=github&logoColor=white)](https://github.com/julian-8897/flow-matched-neural-operators)
[![marimo](https://img.shields.io/badge/marimo-Notebook-7c3aed?style=flat)](https://molab.marimo.io/notebooks/nb_KjqXxSQBsdQUwggJE6qDh3)

**Semantic Search for Scientific Literature**
Deployed Streamlit app that ingests configurable arXiv categories, embeds titles/abstracts with SPECTER, and retrieves cross-domain literature by meaning rather than keyword — built on Sentence Transformers and FAISS.
[![GitHub](https://img.shields.io/badge/GitHub-Repo-181717?style=flat&logo=github&logoColor=white)](https://github.com/julian-8897/arxiv-semantic-search)
[![Live Demo](https://img.shields.io/badge/Live-Demo-ff4b4b?style=flat&logo=streamlit&logoColor=white)](https://arxiv-llm.streamlit.app)

---

## Research Interests

- **Scientific Machine Learning** — Neural ODEs, PINNs, operator learning (FNO, DeepONet), PDE surrogates
- **Inverse Problems & Inference** — amortized posterior inference, simulation-based inference, parameter recovery
- **Generative & Foundation Models for Science** — flow matching, scientific foundation models
- **Interpretability & Discovery** — symbolic regression, equation discovery from data

_Domain knowledge:_ N-body simulations, galaxy mergers, supermassive black hole binaries

---

## Technical Stack

[![Python](https://img.shields.io/badge/Python-3776ab?logo=python&logoColor=white&style=flat)](https://www.python.org/)
[![PyTorch](https://img.shields.io/badge/PyTorch-ee4c2c?logo=pytorch&logoColor=white&style=flat)](https://pytorch.org/)
[![JAX](https://img.shields.io/badge/JAX-d35400?style=flat)](https://github.com/google/jax)
[![PyTorch Geometric](https://img.shields.io/badge/PyG-Graph%20NNs-6f42c1?style=flat)](https://pytorch-geometric.readthedocs.io/)
[![PyTorch Lightning](https://img.shields.io/badge/Lightning-792ee5?style=flat)](https://lightning.ai/)
[![Weights & Biases](https://img.shields.io/badge/W%26B-FFBE00?logo=weightsandbiases&logoColor=black&style=flat)](https://wandb.ai/)
[![Docker](https://img.shields.io/badge/Docker-2496ed?logo=docker&logoColor=white&style=flat)](https://www.docker.com/)
[![Git](https://img.shields.io/badge/Git-f05032?logo=git&logoColor=white&style=flat)](https://git-scm.com/)

---

<p align="center">
  <img src="https://raw.githubusercontent.com/julian-8897/github-stats/master/generated/overview.svg#gh-dark-mode-only" width="60%" alt="GitHub stats (dark)" />
  <img src="https://raw.githubusercontent.com/julian-8897/github-stats/master/generated/overview.svg#gh-light-mode-only" width="60%" alt="GitHub stats (light)" />
</p>

<!---
julian-8897/julian-8897 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
