# EEG Hand Gesture Recognition — Experimental Results

## Research Overview

This MSc research evaluates machine learning, deep learning and hybrid CNN–machine learning approaches for classifying hand movement states from EEG signals.

The classification task considers three movement categories:

* No movement
* Mild movement
* Strong movement

## Model Performance Comparison

The following test accuracies were reported in the MSc dissertation.

| Model                              | Reported Test Accuracy |
| ---------------------------------- | ---------------------- |
| XGBoost                            | 85%                    |
| Random Forest                      | 83%                    |
| Convolutional Neural Network (CNN) | 74%                    |
| CNN + XGBoost                      | 69%                    |
| Support Vector Machine (SVM)       | 68%                    |

## Key Findings

**XGBoost achieved the highest reported accuracy of 85%.**

Random Forest achieved 83%, demonstrating competitive performance among ensemble learning approaches.

The standalone CNN achieved 74%, while the CNN–XGBoost hybrid achieved 69%.

The evaluated hybrid approaches did not outperform the strongest standalone machine learning classifiers.

## Evaluation Methods

The research considered:

* Classification accuracy
* Precision and recall
* F1-score
* Confusion matrices
* Hyperparameter optimisation using GridSearchCV

## Research Implications

The findings suggest that conventional ensemble learning algorithms can perform competitively on EEG movement classification tasks without requiring more complex hybrid architectures.

## Limitations and Future Work

Future research could explore:

* Improved EEG preprocessing and feature extraction
* Cross-participant generalisation
* Real-time gesture recognition
* Improved CNN feature integration
* Evaluation in assistive technology applications

## Reproducibility

These results are taken from the original MSc dissertation and have not been independently reproduced in this repository. Original implementation notebooks and additional evaluation outputs will be added when available.

The research represents experimental classification work and is not a clinically validated patient-monitoring system.
