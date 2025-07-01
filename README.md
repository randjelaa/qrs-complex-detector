# QRS Complex Detection in ECG Signals Using Hilbert Transform

This project implements an algorithm for detecting QRS complexes in ECG signals by applying Hilbert transform-based preprocessing and adaptive decision rules. The solution is developed in Python within a Jupyter Notebook, utilizing signal processing techniques to accurately identify heartbeats from ECG recordings sourced from the MIT-BIH Arrhythmia Database.

---

## About

Electrocardiogram (ECG) signals represent the electrical activity of the heart, where the QRS complex is a key waveform indicating ventricular contraction. Accurate detection of QRS complexes is fundamental for cardiac health analysis.

This project covers:

* Reading and visualizing ECG signals with QRS annotations
* Designing and implementing digital bandpass and derivative filters
* Constructing an approximate digital Hilbert transform filter
* Applying preprocessing steps including filtering and Hilbert transform
* Detecting QRS complex candidates using peak detection and thresholding
* Classifying candidates as true QRS complexes or noise
* Evaluating detection performance with sensitivity and precision metrics
* Visualizing results and analyzing detection accuracy

The notebook combines theoretical background, signal processing implementation, and experimental validation on real ECG data.

---

## Features

* Load ECG data and annotations from `.npz` files
* Plot ECG signals with marked QRS complexes
* Design and analyze digital filters (bandpass, derivative, Hilbert)
* Implement Hilbert transform filtering and peak detection
* Adaptive thresholding for candidate selection
* Performance evaluation with true positive, false positive, and false negative counts
* Visual and quantitative analysis of detector behavior

---

## Technologies Used

* Python 3.x
* Jupyter Notebook
* NumPy, SciPy (signal processing)
* Matplotlib (plotting)

---

## Usage

Open the Jupyter Notebook and run all cells sequentially. Modify parameters for filters and detection thresholds to observe effects on performance.

