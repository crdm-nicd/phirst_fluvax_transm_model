# Pediatric Influenza Vaccination Impact Model

This repository contains the code and input data used in our study:

"Projecting the impact of pediatric transmission-reducing influenza vaccination in South Africa using a transmission model calibrated to household cohort data"

Preprint available on medRxiv:  https://doi.org/10.1101/2025.04.04.25325228  
Corresponding authors: Jackie Kleynhans jackiel@nicd.ac.za and Kaiyuan Sun kaiyuan.sun@nih.gov 

## Purpose

The study evaluates the potential population-wide impact of pediatric influenza vaccination using a Susceptible–Latent–Infectious–Recovered (SLIR) compartmental model. The model incorporates age-specific differences in susceptibility, infectiousness, and viral shedding duration, and is calibrated using rich virological and immunological data from a multiyear household cohort study conducted in urban and rural South Africa.

Simulations assessed the effectiveness of transmission-reducing vaccines targeting children aged 6 months–5 years or 6–12 years, across various coverage and effectiveness scenarios. 

## Repository contents

- Flu Vax SEIR Kleynhans.ipynb: Jupyter notebook containing the full model code, parameter fitting, and scenario simulations.
- Influenza model input parameters.pkl: Serialized input file containing fixed model parameters. These are loaded by the notebook to reproduce simulations. Fitted parameters (from least-squares fitting to observed attack rates in the PHIRST household cohort) are included in the notebook itself.

The model provides a policy-relevant tool to assess the value of new influenza vaccines, especially in low- and middle-income, high-transmission settings.
