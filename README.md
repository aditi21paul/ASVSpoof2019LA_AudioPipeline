Acoustic Feature Extraction for Audio Deepfake Detection

Objective: To extract and analyze acoustic features that can distinguish genuine speech from deepfake speech.

Real-World Context: Most audio deepfake detection systems rely on handcrafted acoustic features before applying machine learning algorithms. Selecting
appropriate features significantly influences detection performance.

Problem Statement: Develop a feature extraction pipeline that computes multiple acoustic features from speech recordings and analyzes their effectiveness for
detecting spoofed speech.

Methodology Guidance:
· Preprocess the audio recordings.
· Extract acoustic features such as:
     o MFCC
     o LFCC
     o CQCC
     o Spectral Centroid
     o Spectral Flatness
     o Zero Crossing Rate
     o RMS Energy
· Compare feature distributions for genuine and spoofed speech.
· Perform statistical analysis to identify discriminative features.

Deliverables:
· Python implementation for extracting multiple acoustic features.
· Feature comparison plots and statistical analysis.
· A report discussing which features best separate genuine and spoofed speech.
