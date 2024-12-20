# CS6890_Ass_5_Datagen - Fraud Analytics Course

## Overview

This project involves processing raw data, training a Variational Autoencoder (VAE) model, generating synthetic data, and evaluating its quality. The key steps include data cleaning, scaling, model training, synthetic data generation, and quality evaluation.

## Pipeline Overview

1. **Data Preprocessing:**

    - Cleaned raw data by handling missing values and encoding categorical variables.
    - Applied Min-Max scaling to ensure equal contribution of all features.

2. **VAE Model:**

    - Trained a Variational Autoencoder for 20 epochs to learn the data's distribution.
    - Used reconstruction loss and KL divergence for training.
    - Generated 2,002,225 synthetic data points based on learned latent space.

3. **Evaluation:**
    - Evaluated synthetic data quality using coarse-grained, medium-grained, and fine-grained metrics.
    - Found slight skewness in the generated data, suggesting potential for model improvement.

## Requirements

-   Python 3.x
-   TensorFlow
-   Scikit-learn
-   NumPy
