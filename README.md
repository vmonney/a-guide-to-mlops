# MLOps - Celestial Body Classification

This repository contains the code from
[A guide to MLOps](https://swiss-ai-center.github.io/a-guide-to-mlops/).

## Usage

The code is divided in various scripts:

- `python3 src/prepare.py <raw-dataset-folder> <prepared-dataset-folder>`: prepare the dataset for training
- `python3 src/train.py <prepared-dataset-folder> <model-folder>`: train the model
- `python3 src/evaluate.py <model-folder> <prepared-dataset-folder>`: evaluate the model

## Notes
**Execute the following command(s) in a terminal**
```bash
# Prepare the dataset
python3 src/prepare.py data/raw data/prepared

# Train the model with the train dataset and save it
python3 src/train.py data/prepared model

# Evaluate the model performance
python3 src/evaluate.py model data/prepared
```