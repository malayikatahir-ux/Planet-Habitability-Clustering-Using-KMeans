<div align="center">

# Planet Habitability Clustering Using K-Means

### Unsupervised Machine Learning Project for Discovering Hidden Planet Groups Through Data Cleaning, Feature Engineering, Normalization, and Multi-Feature Cluster Visualization

</div>

---

# Project Overview

This project demonstrates the practical implementation of the **K-Means Clustering Algorithm** on a large planet habitability dataset containing astronomical and planetary features.

The notebook focuses on understanding how unsupervised machine learning can automatically identify hidden patterns and similarities between planets without using predefined output labels.

Instead of relying only on theory, this project explores:
- real-world preprocessing
- large-scale feature cleaning
- normalization
- clustering
- visualization
- and dimensional understanding of data

through a complete machine learning workflow.

---

# Dataset Processing Journey

The original dataset contained:

<div align="center">

# 69 Features

</div>

Since the dataset included a large number of missing values, preprocessing became one of the most important stages of the project.

A detailed cleaning workflow was performed step by step to improve overall dataset quality before clustering.

---

# Data Cleaning & Preprocessing Workflow

---

## Step 1 — Handling Heavy Missing Values

Columns containing more than 50% missing values were automatically identified and removed to reduce unnecessary noise and improve dataset reliability.

After this filtering process:
- the number of columns reduced significantly
- cleaner features remained for clustering analysis

---

## Step 2 — Removing Highly Incomplete Features

Additional columns containing more than 2 missing values were also removed to further stabilize the dataset structure.

After preprocessing:
- the dataset was reduced from 69 columns to 24 meaningful features

Remaining missing values were carefully filled to preserve useful planetary information.

---

## Step 3 — Heatmap Analysis

A heatmap visualization was created to inspect:
- missing values
- feature completeness
- and overall dataset quality

This helped visually confirm the preprocessing improvements before model training.

---

## Step 4 — Label Encoding

Since the dataset contained multiple categorical planetary features, label encoding was applied to transform string-based values into numerical form suitable for machine learning algorithms.

---

## Step 5 — Normalization

Feature scaling was performed using normalization techniques to ensure balanced distance calculations during clustering.

This step was especially important because K-Means heavily depends on distance-based similarity measurements.

---

# Clustering Process

---

## Step 6 — Initial Feature Visualization

Before applying clustering, scatter plots were created using selected planetary features to visually compare:
- habitable planets
- non-habitable planets
- and general planetary distribution patterns

This helped explore natural patterns present inside the dataset before unsupervised learning.

---

## Step 7 — Applying K-Means Clustering

The K-Means clustering algorithm was implemented to divide planets into:

<div align="center">

# 2 Clusters

</div>

The model grouped planets automatically based on feature similarity and multidimensional distance calculations across the dataset.

Unlike supervised learning models, K-Means created clusters without predefined output labels.

---

# Multi-Feature Cluster Visualization

One of the most important parts of this project was understanding the limitation of 2D visualization in clustering problems.

Since humans can visually interpret only 2D graphs effectively, separate scatter visualizations were created for multiple feature combinations.

Instead of visualizing only one pair of features, multiple feature-pair scatter plots were manually implemented using separate plotting code to explore clustering behavior across many dimensions of the dataset.

This helped observe:
- cluster separation
- feature relationships
- and planetary grouping behavior

from different perspectives within a single visualization workflow.

---

# Technologies Used

<div align="center">

| Technology | Role in Project |
|---|---|
| **Python** | Built the complete clustering workflow |
| **Pandas** | Data cleaning, preprocessing, and feature handling |
| **NumPy** | Numerical operations and array processing |
| **Matplotlib** | Scatter plots and clustering visualization |
| **Seaborn** | Heatmap visualization and data inspection |
| **Scikit-learn** | Label encoding, normalization, and K-Means clustering |

</div>

---

# What This Project Demonstrates

This repository demonstrates:
- large dataset preprocessing
- missing value handling
- feature reduction
- label encoding
- normalization
- heatmap analysis
- unsupervised machine learning
- K-Means clustering
- multidimensional feature understanding
- and advanced cluster visualization techniques

through a complete practical machine learning workflow.

---

# Learning Outcome

This project was developed to strengthen understanding of:
- K-Means clustering
- unsupervised learning
- multidimensional distance calculation
- preprocessing for clustering
- feature normalization
- cluster visualization
- and practical machine learning experimentation using astronomical datasets.

The repository also explores the challenge of visualizing high-dimensional clustering results using multiple 2D feature combinations.

A handwritten mathematical intuition of the K-Means algorithm using Euclidean Distance is also included in this repository to demonstrate the theoretical understanding behind how clustering groups are formed based on similarity and distance between data points.

---

<div align="center">

### Repository Includes

Heatmap Analysis • Missing Value Handling • Label Encoding • Normalization • K-Means Clustering • Multi-Feature Scatter Visualization • Planet Habitability Analysis • Unsupervised Learning Workflow

</div>

---
