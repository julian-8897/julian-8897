# Hi, I'm Julian

AI research engineer and PhD researcher at the **University of Surrey**. I build LLM agents and ML systems for technical and scientific work, and I test whether they actually work: controlled evaluations, matched baselines, and results you can rerun from the repo.

Open to AI research engineering, applied AI and scientific ML roles in London or remote in the UK.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0a66c2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/julian-chan-a86b2921b)
[![Email](https://img.shields.io/badge/Email-ea4335?style=flat&logo=gmail&logoColor=white)](mailto:julianchan8897@gmail.com)

## LLM agents and evaluation

- **[Research Brief Agent](https://github.com/julian-8897/research-brief-agent)**: a streaming FastAPI service where an LLM agent searches a Qdrant index, pulls new papers from arXiv, reads full text and writes a cited technical brief. It holds back the final brief until it has read the evidence, checks every citation against what it retrieved, and runs scenario evaluations as CI gates. On the core suite: **0 fabricated citations**, about 30 s and $0.10 per brief, every run traced to Langfuse.

## ML for physical simulation

- **[Differentiable hybrid closure for 2D turbulence](https://github.com/julian-8897/tesseract-hybrid-closure)** ([walkthrough](https://julian-8897.github.io/tesseract-hybrid-closure/)): a PyTorch closure trained through a JAX spectral solver, with gradients passing between two served Tesseract components. Over 500 steps it cuts rollout error by **71.7%** against the solver alone and by 15.7% against a matched baseline trained offline, on all 32 test trajectories. Tesseract Hackathon 2026, Track 3.
- **[Neural ODE surrogates for black hole binary evolution](https://arxiv.org/abs/2601.13019)**: a parameterised neural ODE trained on N-body galaxy merger simulations that emulates the orbital evolution of black hole binaries and recovers merger timescales at a fraction of the cost of direct simulation. First author, accepted to **MNRAS**.
- **[Inverse parameter estimation for PDEs](https://github.com/julian-8897/tesseract-pinn-inverse-burgers)**: solver adjoints, PINNs and learned posteriors recover the viscosity of Burgers' equation from sparse, noisy measurements, packaged as swappable JAX and PyTorch components. Honourable Mention, Tesseract Hackathon 2025; presented again at the Tesseract Forum 2026.

## Stack

Python · PyTorch · JAX · FastAPI · Qdrant · Langfuse · Docker · Tesseract · GitHub Actions · SLURM
