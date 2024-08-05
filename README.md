# Replicating the Study: Step-by-Step Guide

This README provides a comprehensive guide to replicating the study by running five Jupyter notebook files in the specified order. Each notebook serves a specific purpose, from preprocessing raw data to comparing generated datasets. Follow the instructions carefully to ensure successful replication.

## Prerequisites

- Ensure that all required libraries and dependencies are installed.
- Paths to data files and model outputs should be correctly specified in each notebook.
- TensorFlow version 2.15 is utilized, and the study is conducted in the Google Colab environment using GRU units.

## Steps to Replicate the Study

### 1. Preprocessing

**Objective**: Process the raw data files through Exploratory Data Analysis (EDA), feature engineering, session creation, merging, and filtering to produce the final dataset for training.

- **Input**: Raw data files.
- **Output**: A processed dataset (CSV file) ready for training.

### 2. RNN Interaction Model

**Objective**: Train the RNN model for predicting interaction types using the processed dataset.

- **Input**: Processed dataset from the preprocessing step.
- **Output**: A trained RNN model for interaction type prediction.

### 3. RNN Item Model

**Objective**: Train the RNN model for item prediction using the processed dataset.

- **Input**: Processed dataset from the preprocessing step.
- **Output**: A trained RNN model for item prediction.

### 4. Data Generator

**Objective**: Generate new data using the trained RNN models.

**Steps**:
1. Load the processed dataset (same as used for training).
2. Load the trained RNN models for interaction type and item prediction.

- **Output**: A dataset generated using the trained RNN models.

### 5. Baseline and Comparison

**Objective**: Generate a baseline dataset and compare it with the RNN-generated data and the original data.

- **Input**: Generated dataset, baseline dataset, and original data.
- **Output**: Statistical metrics and comparison graphs.

## Notes

- Ensure that all required libraries and dependencies are installed before running the notebooks.
- Paths to data files and model outputs should be specified correctly in each notebook.
- Follow the sequence strictly to avoid errors and ensure proper data flow through the process.
- This study utilizes TensorFlow version 2.15, running in the Google Colab environment with GRU units.

By following these steps, you should be able to replicate the study and achieve similar results. If you encounter any issues, double-check the paths and dependencies, and ensure you are following the sequence accurately.
