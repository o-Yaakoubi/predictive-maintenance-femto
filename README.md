# Predictive Maintenance using FEMTO-ST Bearing Dataset

Anomaly detection on real bearing vibration data using signal processing and Isolation Forest.

## What This Project Does

Builds a complete predictive maintenance pipeline using free software and a public dataset.

- Time-domain features: RMS, kurtosis, peak-to-peak
- Frequency-domain features: FFT band energies
- Machine learning: Isolation Forest (unsupervised)

## Dataset

FEMTO-ST / IEEE PHM 2012 Data Challenge — bearing degradation dataset.
Available on Hugging Face: Amgharr/FEMTO-ST_DATASET

## Method

1. Load raw acceleration data
2. Extract features per snapshot
3. Standardize features
4. Train Isolation Forest
5. Predict anomalies
6. Visualize results

## Results

Anomalies detected at critical transition points: early kurtosis spikes, operating condition changes, and final failure.

## Tools

Python, Google Colab, pandas, NumPy, scikit-learn, Matplotlib

## Author

Oumaima Yaakoubi
Instrumentation and Intelligent Systems, INSAT, Tunisia
LinkedIn: linkedin.com/in/oumaima-yaakoubi