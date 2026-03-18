# Parameter Estimation for Infectious Disease Models

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/alfaromurillo/parameter_estimation/master?filepath=parameter_estimation.ipynb)

Jupyter notebook on estimating unknown or uncertain parameters in
compartmental transmission models. Developed for a course in
transmission modeling for applied epidemiology, taught at the
[6th International Conference on Mathematical
Biology](http://icmb2018.bucea.edu.cn/index.htm) (Beijing, 2018).

## What this covers

- Fitting ODE-based SIR/SEIR models to observed epidemic data
- Least-squares and maximum likelihood estimation of transmission
  parameters (β, γ, R₀)
- Uncertainty quantification and sensitivity analysis
- Practical considerations: identifiability, data requirements

## Run in your browser

Click the Binder badge above — no installation required.

## Run locally

### Requirements

```
numpy
scipy
matplotlib
ipywidgets
jupyter
```

Install with:

```bash
pip install -r requirements.txt
jupyter notebook parameter_estimation.ipynb
```

Or install [Anaconda](https://www.anaconda.com/download) which
includes all dependencies.

## Part of a series

This notebook is the second in a two-part series:

1. [**`sir_models_intro`**](https://github.com/alfaromurillo/sir_models_intro)
   — model structure and dynamics
2. **`parameter_estimation`** (this repo) — fitting models to data

## Author

[Jorge A. Alfaro-Murillo](https://github.com/alfaromurillo) ·
Mathematical biologist · UCR-CIMPA / Former Yale CIDMA
