# A machine learning model for predicting catalytic activity of CO2 to methanol production.

This repository contains the code for the paper titled A generalized machine learning framework to predict the space-time yield of methanol from thermocatalytic CO2 hydrogenation

- [Overview](#overview)
- [System Requirements](#system-requirements)
- [Installation Guide](#installation-guide)
- [Data preparation](#data-preparation)
- [Model training](#training)

# Overview

This repository contains the codes and dataset to train tree-based model to predict the space-time yield (STY) of higher alcohol synthesis catalysts  
This repository contains the following:

* The main jupyter notebook whihc contains the code used to develop the ML models for the research project.
* For the notebook, we include the curated and labelled dataset in clean Excel sheet
* Necessary instructions to run the model and expected outcome are provided as comments in the notebook.

# System Requirements

## Hardware requirements
The code can run on any standard computer and does not require GPUs or clusters.

## Software requirements
The package has been tested on the following systems:
+ Windows 11 Pro for Workstations with 64-bit operating system, x64-based processor

### Python

A Python version of 3.6 or above is recommended. Most of the code is developed using standrad library packages including:

* Pandas 2.0.3 
* Numpy1.24.3 
* Scikit-learn 1.3.0
* Tensorflow 2.12.1
* Shap 0.40.0

## Installation guide

The codes can also be run on an exisiting environment provided the above listed packages are systemically installed using pip or conda commands.
Alternately users can create a dedicated `conda` environment and install the required the packages. The conda environment can be created by, for example:

* conda create -n HAS python=3.6
* conda activate HAS

## Data preparation

We provide the clean and labelled curated data as Excel sheets titled "Curated data_1234 datapoints.xlsx" which includes all the experimental data used for model training. 

## Model training

The workflow uses standard training process for implementing the tree-based models and we provide instructions for the same. The hyperparameters of the the algorithm are optimized usingthe gridsearch methodology. Users can directly run the model on a local computer by linking with the excel sheet provided.

## Referencing

If you find this work relevant, please cite our published paper:

### A generalized machine learning framework to predict the space-time yield of methanol from thermocatalytic CO2 hydrogenation
 M. Suvarna, TP Araujo, J. Pérez-Ramírez.
Appl. Catal. B Environ. 2022, 315, 121530. (https://www.sciencedirect.com/science/article/pii/S0926337322004714#sec0100)

