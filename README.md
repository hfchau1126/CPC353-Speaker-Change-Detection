# CPC353-Speaker-Change-Detection

## Intoduction
Speaker change detection is the process of identifying transitions between different speakers in an audio stream. This project leverages F0 and MFCC features, which are widely used in speech processing, to detect speaker changes. The IEMOCAP dataset, which contains dyadic conversations, is used to train and evaluate the system.

## Features
- F0 (Fundamental Frequency): Captures the pitch of the speaker which is unique to each individual.
- MFCC (Mel-Frequency Cepstral Coefficients): Represents the short-term power spectrum of the audio that captures vocal tract characteristics.
- Machine Learning Model: A Neural Network is trained on the extracted features to detect speaker changes.

## Results
The performance of the model is evaluated using metrics such as:
- Precision: Percentage of correctly detected speaker changes.
- Recall: Percentage of actual speaker changes detected.
- F1-Score: Harmonic mean of precision and recall.
- Model	Precision	Recall	F1-Score
  SVM	0.85	0.80	0.82
  Random Forest	0.88	0.83	0.85
  Neural Network	0.90	0.87	0.88
