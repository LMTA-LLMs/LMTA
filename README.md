# LMTA: Logs, Metrics, Traces, and Alerts for Root Cause Analysis

## Description
This repository contains the implementation of the LMTA (Logs, Metrics, Traces, and Alerts) methodology for enhancing root cause analysis (RCA). The methodology integrates diverse data streams to generate accurate alerts, improving diagnostic effectiveness compared to traditional methods. The repository includes datasets and samples for training and testing LLMs models for RCA.

## Repository Structure

### Datasets
The `datasets` directory contains two subdirectories: `Micross_LMTA` and `MSDS_LMTA`. Each subdirectory includes a PKL file with mapped log, trace, metric, and alert data for the respective dataset.

- `datasets/Micross_LMTA`: Contains the PKL file for the Micross dataset.
- `datasets/MSDS_LMTA`: Contains the PKL file for the MSDS dataset.

### Training and Testing Samples
The `Training_testing_samples` directory is structured similarly to the `datasets` directory and includes samples used for training and testing large language models (LLMs) for RCA.

- `Training_testing_samples/Micross_LMTA`: Contains training and testing PKL files for the Micross dataset.
- `Training_testing_samples/MSDS_LMTA`: Contains training and testing PKL files for the MSDS dataset.
