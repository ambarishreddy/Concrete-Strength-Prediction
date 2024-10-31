# Concrete-Strength-Prediction

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Python](https://img.shields.io/badge/python-3.8+-brightgreen.svg)
![Status](https://img.shields.io/badge/status-active-success.svg)

## Overview
Predicting the compressive strength of concrete based on its composition and age is crucial in construction. This machine learning project aims to create an accurate model that can assist engineers in optimizing concrete mixes for specific strength requirements.

## Project Goals
- **Predict**: Build a machine learning model to predict compressive strength from concrete mix composition.
- **Analyze**: Explore how each ingredient impacts strength.
- **Optimize**: Provide a tool for material selection and quality control.

## Dataset
This project uses a dataset containing nine features of concrete composition and age, with the target variable `strength` representing compressive strength in MPa.

| Feature         | Description                            | Unit     |
|-----------------|----------------------------------------|----------|
| `cement`        | Cement content                        | kg/m³    |
| `slag`          | Blast furnace slag                    | kg/m³    |
| `ash`           | Fly ash                               | kg/m³    |
| `water`         | Water content                         | kg/m³    |
| `superplastic`  | Superplasticizer                      | kg/m³    |
| `coarseagg`     | Coarse aggregate                      | kg/m³    |
| `fineagg`       | Fine aggregate                        | kg/m³    |
| `age`           | Age of the concrete                   | days     |
| `strength`      | Compressive strength                  | MPa      |

## Project Structure

### Notebooks
- **Data_Exploration.ipynb**: Data loading, exploration, and correlation analysis.
- **Model_Training.ipynb**: Training of various regression models.
- **Evaluation.ipynb**: Model evaluation and performance metrics.

### Source Code
- **model.py**: Contains all necessary functions for preprocessing, training, and predicting concrete strength.

### Visualizations
Visualizations, including correlation matrices and feature importance plots, are in the `visualizations` folder.

## Installation

### Clone the Repository
Clone the repository and navigate to the project directory:

```bash
git clone https://github.com/your-username/concrete-strength-prediction.git
cd concrete-strength-prediction



