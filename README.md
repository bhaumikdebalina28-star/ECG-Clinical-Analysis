# MedTech Data Science: ECG Signal Processing & Arrhythmia Detection

## Project Overview
This project demonstrates a Python-based pipeline for processing raw clinical ECG signals. 
I implemented Digital Signal Processing (DSP) to clean noise and used Machine Learning 
logic to extract clinical metrics (BPM).

## Key Features
- **Signal Cleaning:** Butterworth Bandpass filtering (0.5-40Hz).
- **Peak Detection:** Automated QRS detection using the `xqrs` algorithm.
- **Clinical AnInteractalysis:** Automated classification of Tachycardia and Bradycardia
- Interactive UI: Used Plotly to build interactive, zoomable ECG visualizations. Read more about creating these layouts in the Plotly documentation.
- Dual View: Side-by-side layout for instant visual verification of DSP filters.
- Time-Locked Zoom: Linked x-axes ensure identical timeframes during inspection.


## Tech Stack
- **Language:** Python
- **Libraries:** WFDB, SciPy, NumPy, Matplotlib
- **Data Source:** MIT-BIH Arrhythmia Database (PhysioNet)
