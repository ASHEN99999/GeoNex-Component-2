# GeoNex-Component-2
Machine Learning Model Development for Silent Monitoring-Hub Diagnosis in the GeoNex Landslide Early-Warning System
# GeoNex – Component 2

## Silent Monitoring-Hub Diagnosis

This repository contains the machine-learning development work for Component 2 of the GeoNex landslide early-warning system.

The component focuses on diagnosing monitoring-hub silence by combining pre-silence telemetry, communication information, and independent Backup Pipe verification.

## Research Objective

The objective is to develop and evaluate a diagnostic classifier capable of distinguishing:

1. Hardware Failure
2. Communication Failure
3. Possible Physical Zone Damage

## Methodology

The machine-learning workflow includes:

- Dataset preparation
- Data cleaning
- Feature engineering
- Controlled fault-injection data
- Model training
- Model evaluation
- Baseline comparison

## Model

The initial classification model is:

- Random Forest

## Development Environment

- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
