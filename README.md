# Hi, I'm Julian

Research engineer in AI for science and final-year PhD researcher at the **University of Surrey**. I build LLM agents that run ML experiments, differentiable solvers that models can be trained through, and neural surrogates for physical simulation, and I release the code and run records needed to check the results.

Open to research engineering roles in AI for science, in London or remote in the UK.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0a66c2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/julian-chan-a86b2921b)
[![Email](https://img.shields.io/badge/Email-ea4335?style=flat&logo=gmail&logoColor=white)](mailto:julianchan8897@gmail.com)

## LLM agents for scientific ML

- **[Prior or Feedback? What an LLM Uses When Adapting Neural Operators](https://arxiv.org/abs/2610.12325)** ([code](https://github.com/julian-8897/budgeted-search-ai4science)): can an LLM agent tune a scientific ML model better than standard search, and is it learning from its results or relying on what it already knows? Given the job of fine-tuning pretrained neural operators for new PDEs, the agent found better settings than random search and Bayesian optimisation in almost every run on the same budget. A replay test shows it changes course when its past scores change, so it is using the feedback and not only its prior. Equal contribution, **NeurIPS 2026 AI4Science Workshop**.
- **[Research Brief Agent](https://github.com/julian-8897/research-brief-agent)**: an agent that answers a research question by reading the arXiv literature and writing a short cited brief. It checks every citation against the papers it actually read, and automated evaluations block any change that would let it invent a source.

## Differentiable simulation

- **[Hybrid physics and ML for turbulence](https://github.com/julian-8897/tesseract-hybrid-closure)** ([walkthrough](https://julian-8897.github.io/tesseract-hybrid-closure/)): coarse turbulence simulations are cheap but miss the small scales, so they drift. Training a neural network inside the simulator lets it learn from how its corrections play out over time, not just from single snapshots. It cut long-run error by about 70% against the simulator alone and beat the same network trained the usual way. Tesseract Hackathon 2026.
- **[Recovering physical parameters from noisy data](https://github.com/julian-8897/tesseract-pinn-inverse-burgers)**: estimates the viscosity in Burgers' equation from a few noisy measurements, comparing three routes: gradients through the solver, physics-informed neural networks, and a learned model that also reports its uncertainty. They are built as interchangeable parts so each can be swapped for another. Honourable Mention, Tesseract Hackathon 2025.

## ML for astrophysics

- **[Fast surrogates for black hole mergers](https://arxiv.org/abs/2601.13019)**: when galaxies merge, their central black holes spiral together over millions of years, and following that takes expensive N-body simulations. A neural ODE trained on those simulations predicts the orbit and how long the pair takes to merge, at a fraction of the cost. First author, **MNRAS**.

## Stack

Python · PyTorch · JAX · NumPy/SciPy · Docker · HPC (SLURM)
