# DeconFlow

This repository is the official code base accompanying our paper

Burauel, P., Eberhardt, F., & Besserve, M. (2025). <a href="https://proceedings.mlr.press/v275/burauel25a.html">Controlling for Discrete Unmeasured Confounding in Nonlinear Causal Models</a>. Proceedings of Machine Learning Research, 275, 1–25. 4th Conference on Causal Learning and Reasoning.


main_deconflow.py is the main file from which ray tune experiments are started

dependendencies.py contains required packages


flow_analysis.py generates Figures for the synthetic experiments

flow_architecture.py contains the flow architecture

flow_auxiliary_fns.py contains auxiliary functions for the ray tune experiments
	and the function implementing the deconfounding (deconf_permutation)

toy_data.py generates synthetic data

get_toy_data.py defines data loaders

application_twins_data_preparation.py prepares the twins data

application_twins_analysis.py generates the Figure for the twins experiment
