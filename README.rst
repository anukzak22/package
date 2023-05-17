==================
Bass Model Package
==================

Overview
--------

The Bass Model Package provides various functions for analyzing and predicting the diffusion of innovative products using the Bass Model. This package is based on the paper "Forecasting the Diffusion of Innovative Products Using the Bass Model at the Takeoff Stage" by Suddhachit Mitra and Professor Hovhanissyan lectures.

Features
--------

- Calculate diffusion using the Bass Model.
- Estimate parameters using the `bass_f` function.
- Generate cumulative adoption curve using the `bass_F` function.
- Predict future adoption using the `predict_bass_model` function.
- Plot the predicted adoption curve.

Installation
------------

You can install the Bass Model Package from PyPI using pip:

.. code-block:: shell

    $ pip install mybassm

Usage
-----

The package provides the following main functions:

- `diffusion`: Calculate the diffusion of the product based on the Bass Model.
- `bass_f`: Calculates the fraction of the total market that has adopters at time `t` using the Bass diffusion model.
- `bass_F`: Calculates the fraction of the total market that has adopted up to and including time t using the Bass diffusion model.
- `predict_bass_model`: Predicts future adoption rates based on a given set of time periods and the estimated Bass model parameters.
