# Predictive Maintenance for Rotating Machinery

Machine learning approach to predict bearing failures using vibration sensor data from the NASA IMS bearing dataset.

## Overview

This project implements time and frequency domain feature extraction with classification models to identify different bearing fault types including:
- Inner race defects
- Outer race defects  
- Roller defects

## Key Results

- **94% accuracy** in fault classification
- Feature importance analysis for maintenance decision-making
- Visualization of degradation patterns over time

## Dataset

Uses the NASA IMS (Intelligent Maintenance Systems) bearing dataset with accelerometer data from bearing run-to-failure tests.

## Technologies

- **Python**: Pandas, NumPy, Scikit-learn
- **Signal Processing**: Time and frequency domain feature extraction
- **Visualization**: Matplotlib, Seaborn
- **Machine Learning**: Classification algorithms for fault detection

## Applications

Demonstrates predictive maintenance techniques applicable to:
- Industrial rotating machinery
- Wind turbines
- Motors and pumps
- Any mechanical system where early fault detection is critical

## Usage

```python
# Load and process bearing data
# Extract features from vibration signals  
# Train classification models
# Predict bearing health status
```

This project showcases practical machine learning applications in industrial maintenance and condition monitoring.
