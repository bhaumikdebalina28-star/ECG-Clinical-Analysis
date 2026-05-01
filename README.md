# MedTech Data Science: ECG Signal Processing & Arrhythmia Detection

## Project Overview
This project demonstrates a Python-based pipeline for processing raw clinical ECG signals. 
I implemented Digital Signal Processing (DSP) to clean noise and used Machine Learning 
logic to extract clinical metrics (BPM).

## Key Features
**Signal Cleaning:** Butterworth Bandpass filtering (0.5-40Hz).
**Peak Detection:** Automated QRS detection using the `xqrs` algorithm.
**Clinical Analysis:** Automated classification of Tachycardia and Bradycardia.
**Interactive UI:** Zoomable ECG visualizations built with Plotly. Learn more about making these layouts in the [Plotly subplots guide](https://plotly.com).
**Dual View:** Side-by-side layout for visual verification of filters.
**Time-Locked Zoom:** Linked x-axes ensure identical timeframes during inspection.




## Tech Stack
- **Language:** Python
- **Libraries:** WFDB, SciPy, NumPy, Matplotlib
- **Data Source:** MIT-BIH Arrhythmia Database (PhysioNet)
