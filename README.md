# CPC353-Speaker-Change-Detection

## Intoduction
Speaker change detection is the process of identifying transitions between different speakers in an audio stream. This project leverages F0 and MFCC features, which are widely used in speech processing, to detect speaker changes. The IEMOCAP dataset, which contains dyadic conversations, is used to train and evaluate the system.

## Features
- F0 (Fundamental Frequency): Captures the pitch of the speaker which is unique to each individual.
- MFCC (Mel-Frequency Cepstral Coefficients): Represents the short-term power spectrum of the audio that captures vocal tract characteristics.
- Machine Learning Model: A Neural Network is trained on the extracted features to detect speaker changes.

## Results
The performance of the model is evaluated using metrics such as:
- Classification Report:
              precision    recall  f1-score   support

           0       0.82      0.19      0.30      6905
           1       0.22      0.85      0.35      1838

    accuracy                           0.33      8743
   macro avg       0.52      0.52      0.33      8743
weighted avg       0.70      0.33      0.31      8743

- F1-Score: 0.3462
- Precision: 0.2174
- Recall: 0.8493

