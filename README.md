# Hi, I'm Julian

Research engineer in AI for science and final-year PhD researcher at the **University of Surrey**. I build LLM agents that run ML experiments, differentiable solvers that models can be trained through, and neural surrogates for physical simulation, and I release the code and run records needed to check the results.

Open to research engineering roles in AI for science, in London or remote in the UK.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0a66c2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/julian-chan-a86b2921b)
[![Email](https://img.shields.io/badge/Email-ea4335?style=flat&logo=gmail&logoColor=white)](mailto:julianchan8897@gmail.com)

## LLM agents for scientific ML

- **[Prior or Feedback? What an LLM Uses When Adapting Neural Operators](https://arxiv.org/abs/2610.12325)** ([code](https://github.com/julian-8897/budgeted-search-ai4science)): an LLM agent that chooses fine-tuning settings for pretrained neural operators, within and across PDE families. With 20 trials it reached lower test error than random search in **36/36** paired runs and than TPE in 35/36. A score-reassignment replay test checks whether the agent uses its feedback or falls back on its prior: reassigning past scores shifted its next proposal more than a notation-only control in all 18 traces. Run records are on Zenodo, with a script that recomputes every reported number. Equal contribution, **NeurIPS 2026 AI4Science Workshop**.

## Differentiable simulation

- **[Differentiable hybrid closure for 2D turbulence](https://github.com/julian-8897/tesseract-hybrid-closure)** ([walkthrough](https://julian-8897.github.io/tesseract-hybrid-closure/)): a PyTorch closure trained through a JAX spectral solver, with gradients passing between two served Tesseract components. Over 500 steps it cuts rollout error by **71.7%** against the solver alone and by 15.7% against a matched baseline trained offline, on all 32 test trajectories. Tesseract Hackathon 2026, Track 3.
- **[Inverse parameter estimation for PDEs](https://github.com/julian-8897/tesseract-pinn-inverse-burgers)**: solver adjoints, PINNs and a flow-matching posterior recover the viscosity of Burgers' equation from sparse, noisy measurements, packaged as swappable JAX and PyTorch components. Honourable Mention, Tesseract Hackathon 2025; presented again at the Tesseract Forum 2026.

## ML for astrophysics

- **[Neural ODE surrogates for black hole binary evolution](https://arxiv.org/abs/2601.13019)**: a parameterised neural ODE trained on N-body galaxy merger simulations that emulates the orbital evolution of black hole binaries and recovers merger timescales at a fraction of the cost of direct simulation. First author, accepted to **MNRAS**.

## Stack

Python · PyTorch · JAX · NumPy/SciPy · Docker
