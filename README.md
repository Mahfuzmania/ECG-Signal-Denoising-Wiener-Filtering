# ECG Signal Denoising and Wiener Filtering

## Project Overview
This project explores advanced signal processing techniques to enhance the quality of electrocardiogram (ECG) signals by removing noise and detecting QRS complexes. The methods used include synchronous averaging, moving average filters, cross-correlation functions for QRS complex detection, and Wiener filtering. 

## Key Techniques:
- Synchronous averaging for noise reduction.
- Moving average filters for signal smoothing.
- Cross-correlation for QRS complex detection.
- Wiener filtering for artifact removal.

## Objectives
1. Implement Wiener filtering to remove noise from ECG signals.
2. Apply synchronous averaging to improve the signal-to-noise ratio (SNR).
3. Detect QRS complexes using cross-correlation.
4. Use moving average filters of varying lengths to smooth signals.

## Methodology
### 1. Synchronous Averaging
The process involves averaging multiple noisy ECG signal instances to reduce random noise while preserving the core signal components. This method significantly improves the SNR.

### 2. QRS Complex Detection
A template-based cross-correlation technique was used to detect QRS complexes, facilitating the accurate identification of heart activity markers.

### 3. Moving Average Filters
Two different window sizes (2-point and 4-point) were applied to smooth the ECG signal. The 4-point moving average offered better noise reduction but at the cost of some signal detail.

### 4. Wiener Filtering
Wiener filtering was applied based on the statistical properties of the ECG signals to remove artifacts and improve overall signal clarity.

## Results
- **Synchronous Averaging:** Improved SNR and reduced random noise.
- **QRS Complex Detection:** Accurate detection of QRS complexes using cross-correlation.
- **Moving Average Filters:** Effective noise reduction with varying degrees of smoothing.
- **Wiener Filtering:** Clear removal of artifacts and enhanced ECG data for diagnostic purposes.

## Tools and Technologies
- **Programming Language:** Python (or MATLAB, depending on implementation)
- **Signal Processing Techniques:** Wiener Filtering, Cross-Correlation, Moving Average Filter
- **Data:** ECG signals with simulated noise

## Team Members and Contributions
- **Md. Faiyaz Abrar Fahim:** Led the coding efforts and conceptualized the project’s framework.
- **Mahfuzul Islam:** Collected and prepared ECG datasets and analyzed noisy recordings.
- **Redwan Ul Bari:** Focused on coding, debugging, and ensuring the effectiveness of the algorithms.

## Conclusion
This project successfully enhanced ECG signal quality using synchronous averaging, moving averages, and Wiener filtering. These methods provide a robust framework for clinical ECG signal analysis and the detection of QRS complexes.
