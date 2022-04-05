# Bond graph modelling of liver circulation
This repository contains a tutorial notebook on using [BondGraphTools](https://bondgraphtools.readthedocs.io/en/latest/) to model circulation in the liver. The code can be run either locally or online through Binder.

## Dependencies
To run the notebook locally, the following dependencies are required:
- python >= 3.8
- scikits.odes >= 2.6.2
- BondGraphTools >= 0.4.6

The simplest way to run the code locally is to install [Anaconda](https://www.anaconda.com/products/distribution), open Anaconda Prompt, navigate to the folder containing the files in this repository and enter the following into the terminal:
```
conda env create -n liver-circulation -f environment.yml
conda activate liver-circulation
conda install -c conda-forge notebook
jupyter notebook
```

## Binder notebook
The notebook can be run online using the following link: https://mybinder.org/v2/gh/mic-pan/liver-circulation-bg/HEAD?labpath=liver_circulation.ipynb.
