# SIR-model

## Installation

Run the following commands on your terminal of choice:

```{bash}
pip insall numpy
pip install pandas
pip install matplotlib
pip install scipy
```

**Disclaimer:** `scipy` is an optional package that contains numerical solvers that can be used to solve systems of ODEs with initial values; in this project we use our own version of a Runge-Kutta method of 4th order. However, we recommend using `scipy.integrate.solve_ivp` for heavier (and more precise) numerical integrations.

## Usage

This is not a regular Python package, but rather a compilation of Jupyter notebooks used to explore the behavior of the SIR model. Some level of understanding of differential equations is required for a better use of this repository.

## Contents

Here's a brief overview of each phase of this project:

- Phase 1: Basic SIR model
- Phase 2: SIR model with vital dynamics and a vaccine campaign
- Final phase: Implementation of random initial conditions based on random distributions. In this phase all 3 models were tested.

## Contributing

Please, fell free to make a pull request! I'd love to see new models being implemented.

## License

[GPL-3.0 License](https://github.com/JuanEcheagaray75/SIR-model/blob/master/LICENSE)
