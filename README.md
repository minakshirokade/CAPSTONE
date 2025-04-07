# Capstone
Biometric Authentication with AI.
Description : Use Machine learning and Signal processing for secure Identification.

1. Introduction
Biometric authentication is a recognition system based on the individual's unique biological features for confirming identity. Compared to classical techniques (passwords, PINs), biometric technology provides superior security, convenience, and anti-spoofing capability. The project considers biometric authentication through Electrocardiogram (ECG) signals based on artificial intelligence (AI) and signal processing.

2. Why ECG for Biometrics?
Uniqueness: The ECG waveform of each individual is unique based on anatomical and physiological variability.
Liveness Detection: As ECG is a signal from a living heart, it cannot be easily spoofed or forged.
Security: Hard to forge than fingerprints or facial contour.

3. Machine Learning in ECG-based Authentication
Machine Learning (ML) methods assist in recognizing and distinguishing patterns in the ECG signal. Convolutional Neural Networks (CNNs) are employed by this project to analyze time-series data from ECG and learn features that can identify individuals.
Key ML Contributions:
Feature extraction from raw ECG signals.
Classification and decision-making on features acquired.
Continual improvement with training on varied data.

4. Signal Processing Techniques Used
Signal preprocessing must be done prior to passing data into the ML model. These include:
Noise elimination by filtering.
Scaling so that equal scale is maintained.
Segmentation in order to extract useful beats (e.g., R-R intervals).

5. Workflow Overview
Data Acquisition: Collection of ECG signal from a reputable dataset (e.g., MIT-BIH).
Preprocessing: Pass the signal through bandpass filters.
Feature Engineering: Apply signal processing methods.
Model Training: Apply CNN to differentiate among users and ECG pattern.
Authentication Decision: Compare input ECG with stored identity profiles.

6. Benefits
Offers higher security for high-demand applications (defense, health care, banking).
Offers real-time, continuous verification.
Decreases reliance on traditional methods.

7. Applications
Mobile sign-on protection.
User authentication of wearable device users.
Secure area access control systems.
