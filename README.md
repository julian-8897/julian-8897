# Hi, I'm Julian

I work with a **research + production mindset**: develop the method, then build the system around it. My research is on scientific machine learning for dynamical systems (differentiable simulation, inverse problems), and my engineering is agentic workflows, retrieval, evaluation, deployment. I'm completing a PhD at the **University of Surrey**.

[![arXiv](https://img.shields.io/badge/arXiv-2601.13019-b31b1b?style=flat&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2601.13019)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0a66c2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/julian-chan-a86b2921b)
[![Email](https://img.shields.io/badge/Email-ea4335?style=flat&logo=gmail&logoColor=white)](mailto:julianchan8897@gmail.com)

## Research

- **[Neural ODE surrogates for black hole binary evolution](https://arxiv.org/abs/2601.13019)**: a parameterised neural ODE trained on N-body galaxy-merger simulations that emulates the orbital evolution of black hole binaries and recovers merger timescales at a fraction of the cost of direct simulation. First author, accepted to **MNRAS**.
- **[Inverse parameter estimation for PDEs](https://github.com/julian-8897/tesseract-pinn-inverse-burgers)**: solver-adjoints, PINNs, and learned posteriors recover the viscosity of Burgers' equation from sparse, noisy measurements, packaged as swappable components. Honourable Mention, Tesseract Hackathon 2025.
- **[Differentiable hybrid closure for 2D turbulence](https://github.com/julian-8897/tesseract-hybrid-closure)**: a PyTorch CNN closure trained end-to-end through a JAX spectral solver, composed across two served components with reverse-mode gradients. Reduces 500-step rollout error by **71.7%** versus the solver alone. Tesseract Hackathon 2026, Track 3.

## Production

- **[Source-grounded research agents](https://github.com/julian-8897/research-brief-agent)**: a streaming FastAPI service that turns research questions into cited decision briefs, with Qdrant retrieval, full-text paper reading, and guardrails on evidence use, citation validity, tool budgets, latency, and cost. Every run reports latency and cost and is traced to Langfuse.

## Stack

Python · PyTorch · JAX · PyTorch Lightning · W&B · FastAPI · Qdrant · Docker · Git