# Higgs Boson Prediction Project

## Overview
This project aims to develop a machine learning model to predict the presence of the Higgs boson from collision events. Utilising data from the ATLAS experiment at CERN, made available through a Kaggle competition, the project seeks to classify events based on their likelihood of indicating the presence of the Higgs boson.

## Dataset
The dataset includes features derived from particle collision events, which encompass measurements related to the energy and momentum of particles. The primary objective is to classify these events into 'signal' (indicative of the presence of a Higgs boson) or 'background' (indicative of its absence).

**Source**: The data is sourced from the [Kaggle Higgs Boson Competition](https://www.kaggle.com/c/higgs-boson).

## Requirements
To run the scripts, you will need the following:

- Python 3.8 or newer
- Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn
- Jupyter Notebook or any Python IDE

## Files and Directories
- `training.csv` - Training data containing the features and labels.
- `test.csv` - Test data without labels, used for making predictions.
- `project1.ipynb` - Jupyter notebook containing all code and analysis.

## Installation
Install the required Python libraries by running:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
