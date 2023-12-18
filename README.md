# MultiObjective Hunger Analysis

## Overview

This repository contains notebooks and resources related to the MultiObjective Hunger Analysis of Brazil Nutrition Data.

## Notebooks

### [MIS.ipynb](MIS.ipynb)

This notebook contains novel methods for finding Maximal Independent Objectives in Many Objectives Optimisation Problems.

### [ML_ManyObjective_Duro.ipynb](ML_ManyObjective_Duro.ipynb)

This notebook contains the implementation for the method proposed by [https://bibbase.org/network/publication/duro-saxena-deb-zhang-machinelearningbaseddecisionsupportformanyobjectiveoptimizationproblems-2014](Duro et al) for finding objective selection in optimisation.

### [MPM_Jorge_Fome.ipynb](MPM_Jorge_Fome.ipynb)

This notebook contains a framework for helping in the implementation of Estimation Distribution Algorithms, it generates the Marginal Probability Models and calculate metrics such as MDL, also do sampling for new populations.

Model complexity:
![image](https://github.com/JorgeLuizFranco/MultiObjectiveHungerAnalysis/assets/63986301/eb1c533f-02ee-4fe2-b033-21af21326711)

Entropy:
![image](https://github.com/JorgeLuizFranco/MultiObjectiveHungerAnalysis/assets/63986301/2a8393a6-e4dd-4b82-a86e-16e77eb4bf79)

![image](https://github.com/JorgeLuizFranco/MultiObjectiveHungerAnalysis/assets/63986301/2385fa09-0e11-4ccf-a074-876ac1e405cb)


### [distribution_Damicore_comparison_dadosFome.ipynb](distribution_Damicore_comparison_dadosFome.ipynb)

This notebook contains a Data Analysis of the Brazil Hunger Dataset using Damicore Methodology. It compares different metrics to substitute district data ( vector, mean and median)

### [outlier_MeanMedian_damicore.ipynb](outlier_MeanMedian_damicore.ipynb)

This is a general implementation of the Damicore Method for the Brazil Hunger Dataset, with specific functions for Analysis, such as Mean/Median substitution and dataset split by income.

## Additional Resources

### [MIS_in_ManyObjective_Problems.pdf](MIS_in_ManyObjective_Problems.pdf)

This PDF contains the Theory of Maximal Independent Sets in the context of many-objective problems. Refer to this document for detailed explanations and theories.

## Usage

The data to run the notebooks can be obtained through request in the email [jorge.luiz@usp.br](jorge.luiz@usp.br)

## Contribution

If you'd like to contribute, please fork the repository and create a pull request. Contributions are welcome!



---
© 2023 GitHub, Inc.
