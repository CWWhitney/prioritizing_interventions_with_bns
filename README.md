# Bayesian Network Modeling for Climate Change Adaptation 

This is a repository for Bayesian Network (BN) modeling of [Fernandez et al. 2022](https://link.springer.com/article/10.1007/s13593-022-00809-0) farm management interventions for climate change adaptation and mitigation in banana plantations. This project aims to provide a comprehensive overview of the assumptions underlying the BN models developed for assessing the effectiveness of various interventions.

## Purpose

The purpose of this project is follow up on the underlying assumptions and structure models used to evaluate the impact of farm management interventions on climate change adaptation and mitigation outcomes in banana plantations. Expressing these assumptions as BNs, we aim to enhance transparency and facilitate a deeper understanding of the modeling process.

## What's Included

- **BN Models**: This repository contains BN models implemented in R to simulate the relationships between outcomes and interventions.
- **Model Assumptions**: Detailed documentation outlining the assumptions and dependencies embedded within the BN models.
- **Data**: Datasets and references to data sources used for model parameterization are included.
- **Documentation**: Supplementary materials explaining the BN modeling methodology and interpretation of results.

## Model Assumptions

1. **Causal Relationships**: The BN models assume causal relationships between various farm management interventions and climate change adaptation/mitigation outcomes.
2. **Variable Dependencies**: Dependencies between variables, such as the influence of soil quality on yield or the impact of adaptation measures on production risks, are explicitly modeled.
3. **Uncertainty Representation**: Uncertainty in model parameters and relationships is represented using probability distributions, allowing for probabilistic inference.
4. **Temporal Dynamics**: Temporal dynamics, such as seasonal variations in climate and farming conditions, are incorporated into the models where relevant.
5. **Scale Considerations**: The models account for differences in scale, recognizing that the effectiveness of interventions may vary based on factors such as farm size and geographical location.

## Impact pathways

These form the basis for the BNs

![Screenshot 2024-06-19 at 3 47 40 PM](https://github.com/CWWhitney/prioritizing_interventions_with_bns/assets/19190662/669c1a80-35ab-430d-92da-6d27457a146d)

Graphical impact pathway describing the adaptation, mitigation, and ecological effects of farm management interventions proposed by GIZ for banana production systems in Latin America to comply with international certification schemes.

![Screenshot 2024-06-19 at 3 47 54 PM](https://github.com/CWWhitney/prioritizing_interventions_with_bns/assets/19190662/2f0bc079-58e1-4344-9133-2c5dd45fb5c0)

Simplified illustration of the general impact pathway implemented in the mathematical model for estimating climate change mitigation and adaptation outcomes as well as risks (increase and decrease), costs, expected change in yield, and ecological impact of farm management interventions in banana plantations.

## References

Fernandez, E., Do, H., Luedeling, E. et al. Prioritizing farm management interventions to improve climate change adaptation and mitigation outcomes—a case study for banana plantations. Agron. Sustain. Dev. 42, 76 (2022). https://doi.org/10.1007/s13593-022-00809-0
