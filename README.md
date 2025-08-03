# EPICAGE

EPICAGE implements the core model from our paper [Integrating Epigenetic and Phenotypic Features for Biological Age
Estimation in Cancer Patients via Multimodal Learning].

## Prerequisites

This project is designed to run on **Google Colab** with a **T4 GPU**.  
Additional dependencies can be installed as shown in the provided code scripts.

Our pipeline includes a feature selection step using **BorutaShap**.  
Due to environment limitations in Google Colab, this step should be performed locally.

## Reproduce Results

The framework adopts a modular architecture, allowing flexible model choices. 
We implement two variants: one using the lightweight ElasticNet and the other leveraging the large-scale foundation model TabPFN.

Example scripts for running **EPICAGE-TabPFN** are provided in `EPICAGE. ipynb`, and scripts for **EPICAGE-ElasticNet** are provided in `EPICAGE-ElasticNet.ipynb`.

Additional details are provided in the Appendix.
