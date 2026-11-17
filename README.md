# Hi, I'm Julian

Research engineer in AI for science and final-year PhD researcher at the **University of Surrey**. I build LLM agents that run scientific ML experiments, train neural closures through differentiable solvers, and fit neural surrogates to expensive simulations. I release the code and run records needed to check the results.

Open to research engineering roles in AI for science, in London or remote in the UK.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0a66c2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/julian-chan-a86b2921b)
[![Email](https://img.shields.io/badge/Email-ea4335?style=flat&logo=gmail&logoColor=white)](mailto:julianchan8897@gmail.com)

## LLM agents for scientific ML

- **[Prior or Feedback? What an LLM Uses When Adapting Neural Operators](https://arxiv.org/abs/2610.12325)** ([code](https://github.com/julian-8897/budgeted-search-ai4science)): an LLM as the search policy for fine-tuning pretrained Fourier neural operators on PDEBench, across 12 adaptation tasks within and between PDE families. On a 20-trial budget it reached lower test nRMSE than random search in all 36 paired runs and than TPE in 35. To separate prior knowledge from in-context feedback, a score-reassignment replay perturbs the observed history; the next proposal shifts more than under a notation-only control in every trace, so the agent conditions on feedback and not only on its prior. Run records and a claim-verification script are released. Equal contribution, **NeurIPS 2026 AI4Science Workshop**.
- **[Research Brief Agent](https://github.com/julian-8897/research-brief-agent)**: a tool-using LLM agent served through FastAPI that retrieves from a Qdrant index of arXiv papers, reads full text and writes a cited technical brief. Every citation is verified against the retrieved evidence, and scenario evaluations gate CI, with zero fabricated citations on the core suite.

## Differentiable simulation

- **[Differentiable hybrid closure for 2D turbulence](https://github.com/julian-8897/tesseract-hybrid-closure)** ([walkthrough](https://julian-8897.github.io/tesseract-hybrid-closure/)): a PyTorch CNN closure for a coarse JAX/Exponax spectral solver, trained a posteriori by backpropagating through the solver rollout so it is optimised for long-horizon behaviour rather than one-step error. It cuts 500-step vorticity error by 71.7% against the coarse solver and by 15.7% against the same CNN trained a priori, on every test trajectory. The solver and network also train as separate Tesseract services, exchanging vector-Jacobian products. Tesseract Hackathon 2026.
- **[Inverse problems and simulation-based inference for PDEs](https://github.com/julian-8897/tesseract-pinn-inverse-burgers)**: recovers the viscosity of Burgers' equation from sparse, noisy observations through one gradient interface, using either a differentiable solver adjoint or interchangeable JAX and PyTorch PINNs. An amortised flow-matching posterior over viscosity and initial conditions adds uncertainty, with calibration checked by SBC and TARP coverage. Honourable Mention, Tesseract Hackathon 2025; presented at the Tesseract Forum 2026.

## ML for astrophysics

- **[Neural ODE surrogates for black hole binary evolution](https://arxiv.org/abs/2601.13019)**: a parameterised neural ODE trained on N-body simulations of galaxy mergers that learns the coarse-grained orbital evolution of black hole binaries and recovers merger timescales at a fraction of the cost of direct integration. First author, **MNRAS**.

## Stack

[![Python](https://img.shields.io/badge/Python-3776ab?style=flat&logo=python&logoColor=white)](https://www.python.org/)
[![PyTorch](https://img.shields.io/badge/PyTorch-ee4c2c?style=flat&logo=pytorch&logoColor=white)](https://pytorch.org/)
[![JAX](https://img.shields.io/badge/JAX-4285f4?style=flat)](https://github.com/jax-ml/jax)
[![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)](https://numpy.org/)
[![SciPy](https://img.shields.io/badge/SciPy-8caae6?style=flat&logo=scipy&logoColor=white)](https://scipy.org/)
[![Docker](https://img.shields.io/badge/Docker-2496ed?style=flat&logo=docker&logoColor=white)](https://www.docker.com/)
[![HPC (SLURM)](https://img.shields.io/badge/HPC-SLURM-34495e?style=flat)](https://slurm.schedmd.com/)
