---
layout: page
title: Softwares
permalink: /softwares/
---

<h1 style="display: inline;"><img title="tellurium logo" src="/assets/images/tellurium_logo.png" height="50" style="display: inline; vertical-align:middle"/>&nbsp;&nbsp;tellurium and &nbsp;&nbsp;<img title="libroadrunner logo" src="/assets/images/libroadrunner_logo_tan.jpg" height="40" style="display: inline; vertical-align:middle"/>&nbsp;&nbsp;libRoadRunner</h1>

Tellurium is a self-contained Python-based environment for model building, simulation, and analysis that facilitates the reproducibility of models in systems and synthetic biology.
Here are some of the features of Tellurium:

- A modular, cross-platform, and open-source simulation environment
- First-class support for standards in systems and synthetic biology (SBML, SED-ML, COMBINE, SBOL, etc.)
- Natively integrates libRoadRunner
- Supports Antimony, a human-readable model definition language which can be converted to and from SBML
- A fully configured Python distribution with standalone installation support

[Download Tellurium now](https://github.com/sys-bio/tellurium) or run `pip install tellurium`

1. **K. Choi**, J.K. Medley, M. König, K. Stocking, L. Smith, S. Gu, H.M. Sauro. 2018. “Tellurium: An Extensible Python-based Modeling Environment for Systems and Synthetic Biology.” _BioSystems._ 171, 74–79. [10.1016/j.biosystems.2018.07.006.](https://doi.org/10.1016/j.biosystems.2018.07.006)

2. J.K. Medley, **K. Choi**, M. König, L. Smith, S. Gu, J. Hellerstein, S.C. Sealfon, H.M. Sauro. 2018. “Tellurium Notebooks - An Environment for Dynamical Model Development, Reproducibility, and Reuse.” _PLOS Comp. Biol._ 14 (6), e1006220. [10.1371/journal.pcbi.1006220.](https://doi.org/10.1371/journal.pcbi.1006220)

Tellurium uses libRoadRunner, one of the fastest and most scalable SBML simulation engines for dynamical systems of reaction networks. 
Here are some of the features of libRoadRunner:

- A state-of-the-art high-performance and portable simulation engine for systems and synthetic biology
- Supports the latest SBML specification (except algebraic rules and delay package)
- LLVM JIT compiler leads to incredibly fast simulation speed
- Supports deterministic simulations (CVODE, Euler, RK45, etc.), stochastic simulations, steady-state analyses using NLEQ2 and others, metabolic control analysis, and many more.
- Supports plugin system for bifurcation analysis, parameter estimation, bootstrapping, etc.
- Native low-level parallelization support
- Pickled (serialized) RoadRunner
- On-the-run model editing
- Julia bindings

[Download libRoadRunner now](https://github.com/sys-bio/roadrunner) or run `pip install libroadrunner`

1. C. Welsh, J. Xu, L. Smith, M. König, **K. Choi**, H.M. Sauro. 2023. “libRoadRunner 2.0: A High-Performance SBML Simulation and Analysis Library.” _Bioinformatics._ 39 (1), btac770. [10.1093/bioinformatics/btac770.](https://doi.org/10.1093/bioinformatics/btac770)

<br/>
# evoMEG

Evolutionary Algorithm-based Model Ensemble Generation Algorithm (evoMEG) is a powerful meta-modeling algorithm for biochemical reaction network models that generates a model ensemble from perturbation studies.

[Check out evoMEG](https://github.com/kirichoi/evoMEG)

<br/>
<h1 style="display: inline;"><img title="phrasedml logo" src="/assets/images/phrasedml_logo.png" height="45" style="display: inline; vertical-align:middle"/>&nbsp;&nbsp;phraSED-ML</h1>

phraSED-ML is a human-readable simulation setup definition language which can be converted to and from SED-ML.

[Download phraSED-ML now](https://github.com/sys-bio/phrasedml) or run `pip install phrasedml`

1. **K. Choi**, L. Smith, J.K. Medley, H.M. Sauro. 2016. “phraSED-ML: A paraphrased, human-readable adaptation of SED-ML.” _J. Bioinform. Comput. Biol._ 14 (6), 1650035. [10.1142/S0219720016500359.](https://doi.org/10.1142/S0219720016500359)

<br/>
# netplotlib

netplotlib is a purely Python-based visual analysis tool for biochemical reaction network diagrams, utilizing NetworkX and matplotlib packages.

[Download netplotlib now](https://github.com/kirichoi/netplotlib) or run `pip install netplotlib`


