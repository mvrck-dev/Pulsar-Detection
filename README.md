# Pulsar Detection: EDA and Dimensionality Reduction

## Overview
This repository explores pulsar candidate data using unsupervised learning techniques. The dataset contains examples of real pulsars and noise caused by RFI (Radio Frequency Interference). The project focuses on:
- Extensive Exploratory Data Analysis (EDA)
- Dimensionality reduction using UMAP, PCA, and t-SNE
- Clustering and performance evaluation in reduced dimensions

## Dataset
The dataset consists of 17,898 examples:
- **16,259 noise examples** (class 0)
- **1,639 pulsar examples** (class 1)

Each example is described by 8 continuous features:
1. Mean of the integrated profile
2. Standard deviation of the integrated profile
3. Excess kurtosis of the integrated profile
4. Skewness of the integrated profile
5. Mean of the DM-SNR curve
6. Standard deviation of the DM-SNR curve
7. Excess kurtosis of the DM-SNR curve
8. Skewness of the DM-SNR curve

The dataset is highly imbalanced, with significantly more noise examples than pulsars.

## Project Structure
The repository contains the following components:
1. **EDA Notebook**: Extensive exploratory analysis of the dataset.
2. **Dimensionality Reduction Notebook**: Implementation of UMAP, PCA, and t-SNE for reducing dimensions.
3. **Clustering Notebook**: Clustering in reduced dimensions using K-Means and DBSCAN.
4. **Performance Evaluation**: Comparison of dimensionality reduction techniques based on visualizations and clustering metrics.

## Installation
To run this project locally:
1. Clone this repository:
