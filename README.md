# Bimodal Von Mises Mixture Model for Locust Directional Preferences

This repository contains a **bimodal von Mises mixture model** developed to analyze the directional preferences of individual locusts in response to **virtual swarms of conspecifics in virtual reality (VR)**. The model supports the findings presented in **Sayin et al., 2025**, which challenge classical models of collective motion and propose a **minimal cognitive framework** for locust movement.

## Overview

The **bimodal von Mises mixture model** is designed to:

- **Quantify directional preferences** of individual locusts exposed to VR-generated swarms.
- **Fit a probabilistic model** to the observed data, capturing both individual and population-level responses.
- **Test hypotheses on decision-making mechanisms**, particularly in relation to the vectorial representation of neighbors versus optomotor responses.

## Features

- **Bayesian Inference**: Utilizes **PyMC** for probabilistic modeling of locust movement.
- **Circular Statistics**: Applies **von Mises distributions** to analyze periodic directional data.
- **Preprocessing Pipeline**: Rediscretizes locust trajectories to minimize auto-correlation.
- **Visualization Tools**: Generates trajectory plots and statistical summaries using **matplotlib** and **seaborn**.

## Context & Relevance

This model is part of a broader study on the **behavioral mechanisms of collective motion in desert locusts**, as described in Sayin et al. (2025). The study demonstrates that locusts do not rely on **explicit alignment** with their neighbors but rather use an **internal decision-making framework** based on neural representations of bearings and social interactions.

Key findings that this model contributes to include:
- **Directional bias analysis**: Testing whether locusts prefer certain bearings in response to stimuli.
- **Assessment of individual variability**: Estimating the extent to which different locusts exhibit unique movement tendencies.
- **Evaluation of cognitive models**: Providing empirical evidence against classical self-propelled particle models and supporting a vectorial decision-making approach.

## Usage

The Jupyter Notebook (`locust_mixture_model.ipynb`) contains:
- **Data preprocessing**: Rediscretization of locust trajectories to reduce autocorrelation.
- **Probabilistic modeling**: Implementation of Bayesian inference using **PyMC**.
- **Visualization**: Plotting movement trajectories and fitting mixture models.
- **Statistical inference**: Estimating posterior distributions of directional preferences.


## Citation

If you use this model, please cite:

```latex
@article{sayin2025behavioral,
  title={The behavioral mechanisms governing collective motion in swarming locusts},
  author={Sayin, Sercan and Couzin-Fuchs, Einat and Petelski, Inga and G{"u}nzel, Yannick and Salahshour, Mohammad and Lee, Chi-Yu and Graving, Jacob M and Li, Liang and Deussen, Oliver and Sword, Gregory A and others},
  journal={Science},
  volume={387},
  number={6737},
  pages={995--1000},
  year={2025},
  publisher={American Association for the Advancement of Science}
}
```

## Data Availability

The data used in this study are not yet available but will be released at the following Zenodo repository: [https://doi.org/10.5281/zenodo.14353283](https://doi.org/10.5281/zenodo.14353283)

## License

This repository is licensed under the [Apache 2.0 License](LICENSE).

