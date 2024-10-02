# SEIR Model in MATLAB

This repository contains the implementation of a **Susceptible-Exposed-Infectious-Recovered (SEIR)** epidemiological model in MATLAB. The SEIR model is used to simulate the spread of infectious diseases in a population over time.

## Table of Contents

- [Overview](#overview)
- [Requirements](#requirements)
- [Usage](#usage)
- [Model Equations](#model-equations)
- [Running the Code](#running-the-code)
- [Parameters](#parameters)
- [License](#license)

## Overview

The SEIR model divides the population into four compartments:
- **Susceptible (S)**: Individuals who are at risk of contracting the disease.
- **Exposed (E)**: Individuals who have been exposed to the disease but are not yet infectious.
- **Infectious (I)**: Individuals who are infectious and can spread the disease.
- **Recovered (R)**: Individuals who have recovered from the disease and are now immune.

This project allows you to simulate different scenarios by varying the parameters such as transmission rate (\(\beta\)) and recovery rate (\(\gamma\)).

## Requirements

- MATLAB (R2020b or later recommended)
- Basic knowledge of differential equations and epidemiological modeling

## Usage

Clone the repository and navigate to the directory containing the code. The main script solves the SEIR model using MATLAB’s `ode45` function and plots the results.

### Clone the repository

```bash
git clone https://github.com/your-username/SEIR-model.git
cd SEIR-model
