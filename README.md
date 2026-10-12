# Hi, I'm Julian

**AI Research Engineering · Agentic AI · Scientific Machine Learning**

I'm a PhD researcher at the **University of Surrey**, working at the intersection of AI agents, scientific machine learning, and computational research.

I build AI systems for complex technical and scientific problems, from LLM-powered research agents to learned models of physical dynamics. My focus is on combining research with practical engineering, rigorous evaluation, and reproducible results.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0a66c2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/julian-chan-a86b2921b)
[![Email](https://img.shields.io/badge/Email-ea4335?style=flat&logo=gmail&logoColor=white)](mailto:julianchan8897@gmail.com)

## Agentic AI & Evaluation

- **[Prior or Feedback? What an LLM Uses When Adapting Neural Operators](https://arxiv.org/abs/2610.12325)**: Investigates LLM-guided adaptation of Fourier Neural Operators across PDE regimes. Benchmarks against random search and TPE under matched experimental budgets, with controlled interventions to distinguish scientific priors from experimental feedback. **Accepted at the NeurIPS 2026 AI for Science Workshop.**

- **[Research Brief Agent](https://github.com/julian-8897/research-brief-agent)**: An end-to-end LLM research agent built with FastAPI, Qdrant, and Langfuse. Retrieves papers from arXiv, reads full-text evidence, and produces citation-verified technical briefs. Includes streaming, execution tracing, and CI-based scenario evaluations. Achieved **zero fabricated citations on the core evaluation suite**, at approximately 30 seconds and $0.10 per brief.

## AI for Science & Physical Simulation

- **[Differentiable Hybrid Closure for 2D Turbulence](https://github.com/julian-8897/tesseract-hybrid-closure)** ([walkthrough](https://julian-8897.github.io/tesseract-hybrid-closure/)): Couples a PyTorch neural closure with a differentiable JAX spectral solver, training directly through simulation rollouts. Reduced 500-step rollout error by **71.7% relative to the standalone solver** and **15.7% relative to a matched offline-trained baseline**, across 32 test trajectories. *Tesseract Hackathon 2026.*

- **[Neural ODE Surrogates for Black Hole Binary Evolution](https://arxiv.org/abs/2601.13019)**: Developed parameterised neural ODE surrogates for black hole binary dynamics using N-body galaxy merger simulations, enabling efficient prediction of orbital evolution and merger timescales. **First author, accepted to MNRAS.**

- **[Inverse Parameter Estimation for PDEs](https://github.com/julian-8897/tesseract-pinn-inverse-burgers)**: Combines solver adjoints, physics-informed neural networks, and learned posteriors for parameter inference from sparse, noisy measurements. Implemented as interchangeable JAX and PyTorch components. *Honourable Mention, Tesseract Hackathon 2025; Tesseract Forum 2026.*

## Technical Stack

**ML & Scientific Computing:** Python · PyTorch · JAX · Neural Operators · Neural ODEs

**Agents & Backend:** LLM Agents · FastAPI · Qdrant · Langfuse

**Infrastructure & Tools:** Docker · GitHub Actions · SLURM · Tesseract
