# CS 598 Deep Learning for Healthcare Final Project

This repository contains the implementation of a machine learning model that predicts anticancer drug synergy for understudied tissues using transfer learning techniques. The goal is to leverage data from well-studied contexts to improve predictions in contexts where data is scarce. 

# Data Structure
Obtain drug combination synergy data from drugcomb  \
summary_table.csv # Summary of drug combinations \
cell/ # Cell line features  \
drug/ # Drug features 

## Requirements

To run the scripts, you need Python 3 and the following packages: 

pip install numpy pandas torch torchvision

## Running the Code

Execute the following steps to preprocess the data and run the model:

1. **Preprocess**: Prepare the data for training and testing the model.
2. **Train Model**: Run the training script to build and train the transfer learning model.
3. **Evaluate**: Assess the model's performance on the test dataset.

## Results

The trained model should demonstrate the ability to predict drug synergies with an accuracy reflected by the AUROC and AUPRC metrics, as detailed in our experiments.
