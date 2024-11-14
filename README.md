# Option Pricing by Monte Carlo Simulation

This repository contains a Jupyter Notebook that applies Monte Carlo Simulation for pricing financial options. The approach is used to estimate the value of options based on probabilistic simulations, offering flexibility for different scenarios and market conditions.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Methods](#methods)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Monte Carlo Simulation is a technique used to understand the impact of risk and uncertainty in prediction and forecasting models. This project focuses on using Monte Carlo methods for financial option pricing, demonstrating how simulations can be utilized to calculate the fair value of derivatives like options.

## Features

- Simulation-based pricing of European call and put options.
- Customizable parameters, including volatility, strike price, risk-free rate, and number of simulations.
- Visualization and statistical analysis of the results.

## Installation

To run this notebook locally, you'll need to have Python and Jupyter Notebook installed. We also recommend using a virtual environment.

### Prerequisites

- Python 3.7 or higher
- Jupyter Notebook
- Common Python libraries such as:
  - NumPy
  - Pandas
  - Matplotlib
  - SciPy (if applicable)

### Setup Instructions

1. Clone this repository:
    ```bash
    git clone https://github.com/Rowan77/OptionPricingByMonteCarloSimulation.git
    cd OptionPricingByMonteCarloSimulation
    ```

2. Create a virtual environment (optional but recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

Open the Jupyter Notebook:

```bash
jupyter notebook
Then, navigate to Quant_Method_CW_K23023533.ipynb in your browser. The notebook guides you through the process of using Monte Carlo methods for option pricing, including input parameters, simulation processes, and results analysis.
```
### Example
To run the Monte Carlo simulation for a simple European call option with a given set of parameters, simply set the parameters in the notebook and execute the code cells step by step.

### Methods
The Monte Carlo simulation approach used in this project is based on generating multiple paths for the underlying asset price using stochastic processes, typically assuming geometric Brownian motion (GBM). The simulated paths are used to estimate the expected payoff, which is then discounted to calculate the option's present value.

Key aspects covered:

- Geometric Brownian Motion (GBM) modeling
- European Call and Put options pricing
- Convergence and statistical analysis
