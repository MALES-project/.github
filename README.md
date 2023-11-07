# Discovering deep physics models with differentiable programming

## A project by

|                                                                                                                                                                                    |                                                                                                                                                          |
|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------------------------------------:|
| <a href="https://www.cwi.nl/en/"><img src="https://raw.githubusercontent.com/DEEPDIP-project/.github/741408acacf3aa2675a5a921258d2c309d4bab9a/img/cwi-logo.svg" height="90" /></a> | <a href="https://www.esciencecenter.nl/"><img src="https://raw.githubusercontent.com/DEEPDIP-project/.github/main/img/nlesc-logo.png" height="90" /></a> |


## In a nutshell

### Public

- [Project site](https://research-software-directory.org/projects/deepdip)

### Private

- [Team Nabla's repository](https://github.com/Team-Nabla/) (private access for eScience members only)
- [Slack channel](https://deepdip-workspace.slack.com)

## Abstract

Many physics models feature terms that are either partially unknown or too expensive to simulate. Discovering effective equations that represent such terms is a fundamental challenge in computational science. Multi-scale models are a prominent example: the large-scale behaviour is of main interest, but this cannot be obtained without resolving the fine scales. A well-known example occurs in climate models, which rely on the effect of clouds for accurate forecasts, but simulating clouds individually is computationally intractable.

We propose a new software framework to extend generic physics models with data-driven neural networks (NNs) that represent the effect of small scales on large scales. The framework will use differentiable programming, allowing to couple multi-scale models and NNs while embedded in a learning environment.

We test our framework on turbulent fluid flows. In particular, we develop new differentiable wind-turbine wake models, to be used for optimal control of wind farms.

## Resources

- Recent articles:
	- [Energy-Conserving Neural Network for Turbulence Closure Modeling
](https://arxiv.org/abs/2301.13770)
	- [Comparison of neural closure models for discretised PDEs](https://www.sciencedirect.com/science/article/pii/S0898122123001736)
- MSc thesis:
	- [Machine learning for closure models](https://pure.tue.nl/ws/portalfiles/portal/279333801/Melchers_H.pdf)
- Github documentation:
	- [IncompressibleNavierStokes.jl](https://agdestein.github.io/IncompressibleNavierStokes.jl/stable/)
		- For example, the discretization is outlined [here](https://agdestein.github.io/IncompressibleNavierStokes.jl/stable/equations/spatial/)
- General CFD:
	- Computational methods for fluid dynamics, [Ferziger & Peric](https://link.springer.com/book/10.1007/978-3-642-56026-2).
	- Veldman [lecture notes](https://www.math.rug.nl/~veldman/Colleges/CFD/CFDdictaat1314.pdf) on CFD.
- MUSCLE3
	- [Tutorial](https://muscle3.readthedocs.io/en/latest/index.html)
- Neural differential equations
	- On neural differential equations. [Textbook](https://arxiv.org/abs/2202.02435) by [Dr. Patrick Kidger](https://kidger.site/).
	- Interactive tutorials on [neural closure models](https://github.com/agdestein/NeuralClosure)

### Other
- Announcement on CWI [website](https://www.cwi.nl/en/news/escience-center-grants-cwi-project-on-differentiable-programming/)

## Glossary

- NNs: Neural Networks
- CFD: Computational Fluid Dynamics

---

## Other

<a href="https://www.flaticon.com/free-icons/sea" title="sea icons">Sea icons created by Freepik - Flaticon</a>

