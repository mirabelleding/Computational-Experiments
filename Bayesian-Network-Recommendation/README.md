# Bayesian Network Recommendation

A probabilistic model for estimating a customer's likelihood of purchasing a product using a Bayesian network.

## Overview

The experiment models purchase decisions using three observable factors: previous purchases of similar products, product review ratings, and the availability of discounts. It uses conditional probability distributions to estimate purchase and non-purchase probabilities, including when some evidence is unavailable.

## Approach

- Define a directed probabilistic network linking purchase history, review rating, and discount availability to the purchase decision.
- Specify prior and conditional probability tables for the variables.
- Perform probabilistic inference with `pgmpy` and variable elimination.
- Evaluate scenarios with complete and partial evidence, marginalizing over unobserved inputs.
- Visualize purchase probabilities across combinations of observed factors.

## Implementation

**Tools:** Python, `pgmpy`, pandas, seaborn, Matplotlib.

**Model inputs:** Past purchase history (yes/no), review rating (good/average/bad), and discount availability (yes/no).

**Output:** Probability distribution over purchase and non-purchase decisions.

The conditional probabilities in this experiment are specified for demonstration rather than fitted to observed customer transactions. Consequently, the results illustrate Bayesian inference, not validated predictive accuracy on real e-commerce data.

## Notebook

[Jupyter Notebook](model_development.ipynb)
