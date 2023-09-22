# Topology-Aware Reinforcement Learning for Tertiary Voltage Control
This repository accompanies our paper *Topology-Aware Reinforcement Learning for Tertiary Voltage Control* submitted at PSCC 2024.

## Datasets
- The script that creates the three variants *Standard*, *Condenser* and *Reduced* from the initial [case60nordic](https://github.com/MATPOWER/matpower/blob/master/data/case60nordic.m) test case can be found [here](https://github.com/bdonon/updating_case60nordic/tree/PSCC24).
- The script that generates datasets from initial operating conditions can be found [here](https://github.com/bdonon/powerdata-gen/tree/PSCC24).
- Links to the three generated datasets are provided below. Notice that it also contains the test sets modified by the baseline and the trained policies.
  - [*Standard* dataset](https://zenodo.org/record/8367765)
  - [*Condenser* dataset](https://zenodo.org/record/8367614)
  - [*Reduced* dataset](https://zenodo.org/record/8367757)
- The tool we use to compare datasets can be found [here](https://github.com/bdonon/powerdata-view/tree/PSCC24)

## Optimization Baseline
- The optimization baseline can be found [here](https://github.com/montefiore-ms/ACOPF4TVC)
- As this baseline only works with matpower data, one needs to preprocess (resp. postprocess) data before (resp. after) applying the baselin. Both scripts can be found [here](https://github.com/bdonon/ACOPF4TVC_converter/tree/PSCC24).

## GNN training
- The code used for the training of our Graph Neural Network policies is available [here](). Notice that this version provides trained policies as well as the configuration files that were used in our experiments.

## Supplementary Material
A supplementary material to our paper can be found [here](https://hdl.handle.net/2268/306778).
