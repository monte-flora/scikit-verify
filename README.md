# scikit-verify

A Python toolkit for computing verification metrics and generating publication-quality diagnostic plots for predictive models, with built-in support for uncertainty quantification through bootstrapping.

## Overview

`scikit-verify` provides a comprehensive suite of verification diagrams and performance metrics commonly used in meteorology, climate science, and machine learning. The package emphasizes statistical rigor by incorporating bootstrap resampling to generate confidence intervals for all metrics and curves.

## Key Features

- **Publication-ready visualizations**: Generate high-quality performance diagrams, ROC curves, reliability diagrams, and attributes diagrams
- **Statistical Significance**: Built-in bootstrap resampling for computing confidence intervals on all metrics and diagram curves
- **Flexible and extensible**: Works with binary and multi-class predictions from any model framework (scikit-learn, XGBoost, PyTorch, etc.)
- **Meteorology-focused**: Includes specialized diagrams for forecast verification (reliability, performance, attributes)
- **Easy integration**: Simple API that follows scikit-learn conventions

## Supported Diagrams

- **Performance Diagrams**: Precision-recall curves with success ratio and bias
- **ROC Curves**: Receiver Operating Characteristic with AUC scores
- **Reliability Diagrams**: Calibration curves showing forecast reliability
- **Attributes Diagrams**: Decomposition of Brier score into reliability, resolution, and uncertainty

## Installation

```bash
git clone https://github.com/monte-flora/scikit-verify
cd scikit-verify
pip install -e .
```