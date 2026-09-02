# Hi, I'm Julian

I work across **AI for science** and **AI engineering**: machine learning for dynamical systems (differentiable simulation, inverse problems) on the research side, and agentic workflows, retrieval, evaluation and deployment on the engineering side. I'm completing a PhD at the **University of Surrey**.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0a66c2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/julian-chan-a86b2921b)
[![Email](https://img.shields.io/badge/Email-ea4335?style=flat&logo=gmail&logoColor=white)](mailto:julianchan8897@gmail.com)

## AI for science

- **[Neural ODE surrogates for black hole binary evolution](https://arxiv.org/abs/2601.13019)**: a parameterised neural ODE trained on N-body galaxy-merger simulations that emulates the orbital evolution of black hole binaries and recovers merger timescales at a fraction of the cost of direct simulation. First author, accepted to **MNRAS**.
- **[Inverse parameter estimation for PDEs](https://github.com/julian-8897/tesseract-pinn-inverse-burgers)**: solver-adjoints, PINNs, and learned posteriors recover the viscosity of Burgers' equation from sparse, noisy measurements, packaged as swappable components. Honourable Mention, Tesseract Hackathon 2025, presented again at the Tesseract Forum 2026.
- **[Differentiable hybrid closure for 2D turbulence](https://github.com/julian-8897/tesseract-hybrid-closure)**: a PyTorch CNN closure trained end-to-end through a JAX spectral solver, composed across two served components with reverse-mode gradients. Reduces 500-step rollout error by **71.7%** versus the solver alone. Tesseract Hackathon 2026, Track 3.

## AI engineering

- **[Source-grounded research agents](https://github.com/julian-8897/research-brief-agent)**: a streaming FastAPI service that turns research questions into cited decision briefs, with Qdrant retrieval, full-text paper reading, and guardrails on evidence use, citation validity, tool budgets, latency, and cost. Every run reports latency and cost and is traced to Langfuse.

## Stack

Python · PyTorch · JAX · W&B · FastAPI · Qdrant · Langfuse · Docker