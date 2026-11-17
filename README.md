# Hi, I'm Julian

I'm a research engineer in **AI for Science** and a final-year PhD researcher at the **University of Surrey**. I build machine learning methods and tools for scientific discovery, spanning LLM agents, differentiable simulation and neural surrogates for complex dynamical systems.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0a66c2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/julian-chan-a86b2921b)
[![Email](https://img.shields.io/badge/Email-ea4335?style=flat&logo=gmail&logoColor=white)](mailto:julianchan8897@gmail.com)

## LLM agents for scientific ML

- **[Prior or Feedback? What an LLM Uses When Adapting Neural Operators](https://arxiv.org/abs/2610.12325)** ([code](https://github.com/julian-8897/budgeted-search-ai4science)): Studied LLM-guided adaptation of Fourier neural operators across PDE regimes. The LLM outperformed random search and TPE in nearly all matched evaluations, while controlled interventions revealed how experimental feedback influences its decisions. Reproducible experiment records and verification tools are available. **Equal contribution.**

  [![NeurIPS 2026 AI4Science Workshop](https://img.shields.io/badge/NeurIPS%202026-AI4Science%20Workshop-6a1b9a?style=flat)](https://arxiv.org/abs/2610.12325)

- **[Research Brief Agent](https://github.com/julian-8897/research-brief-agent)**: Built a tool-using LLM agent that retrieves scientific papers, synthesises technical briefs and verifies citations against source evidence. Uses FastAPI, Qdrant and automated evaluations in CI to assess reliability.

## Differentiable simulation

- **[Differentiable hybrid closure for 2D turbulence](https://github.com/julian-8897/tesseract-hybrid-closure)** ([walkthrough](https://julian-8897.github.io/tesseract-hybrid-closure/)): Developed a neural turbulence closure trained end-to-end through a differentiable spectral solver using PyTorch and JAX. Reduced long-horizon vorticity error by 71.7% relative to the coarse solver and 15.7% relative to conventional supervised training. Demonstrated distributed training across Tesseract services. **Tesseract Hackathon 2026.**

- **[Inverse problems and simulation-based inference for PDEs](https://github.com/julian-8897/tesseract-pinn-inverse-burgers)**: Built a differentiable framework for recovering PDE parameters from sparse, noisy observations, combining solver-based inference, JAX/PyTorch physics-informed neural networks and flow-matching posterior estimation. Includes uncertainty calibration and interchangeable inference methods. **Presented at the Tesseract Forum 2026.**

  [![Tesseract Hackathon 2025 Honourable Mention](https://img.shields.io/badge/Tesseract%20Hackathon%202025-Honourable%20Mention-b8860b?style=flat)](https://pasteurlabs.ai/insights/tesseract-hackathon-winners)

## ML for astrophysics

- **[Neural ODE surrogates for black hole binary evolution](https://arxiv.org/abs/2601.13019)**: Developed a neural ODE surrogate for the orbital evolution of supermassive black hole binaries, trained on N-body simulations of galaxy mergers. Reproduces merger timescales at a fraction of the computational cost of direct simulation. **First author.**

  [![MNRAS 2026](https://img.shields.io/badge/MNRAS-2026-1f4e79?style=flat)](https://arxiv.org/abs/2601.13019)

## Stack

[![Python](https://img.shields.io/badge/Python-3776ab?style=flat&logo=python&logoColor=white)](https://www.python.org/)
[![PyTorch](https://img.shields.io/badge/PyTorch-ee4c2c?style=flat&logo=pytorch&logoColor=white)](https://pytorch.org/)
[![JAX](https://img.shields.io/badge/JAX-4285f4?style=flat)](https://github.com/jax-ml/jax)
[![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)](https://numpy.org/)
[![SciPy](https://img.shields.io/badge/SciPy-8caae6?style=flat&logo=scipy&logoColor=white)](https://scipy.org/)
[![Docker](https://img.shields.io/badge/Docker-2496ed?style=flat&logo=docker&logoColor=white)](https://www.docker.com/)
[![HPC (SLURM)](https://img.shields.io/badge/HPC-SLURM-34495e?style=flat)](https://slurm.schedmd.com/)
