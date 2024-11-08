# CompStrain: A Keras-Based Concrete Strength Prediction Model

**CompStrain** is a deep learning model built using Keras to predict the compressive strength of concrete based on its ingredient composition. This project aims to assist in material optimization and quality control by accurately forecasting concrete strength.

## Project Overview

The model utilizes a regression approach to analyze key factors like cement, water, and aggregate content, predicting the resulting compressive strength. The dataset contains multiple concrete samples, each defined by ingredient volumes and compressive strength values.

## Dataset

The dataset includes:
- Cement (kg in a cubic meter mix)
- Blast Furnace Slag
- Fly Ash
- Water
- Superplasticizer
- Coarse Aggregate
- Fine Aggregate
- Age (days)
  
Each row represents a unique concrete sample and its corresponding compressive strength (target value).

## Model Architecture

The model uses a Sequential Keras model with fully connected layers. It is optimized for regression to output a single value: the predicted compressive strength of the concrete mix.

## Requirements

- Python 3.x
- Pandas
- Numpy
- TensorFlow (with Keras)


