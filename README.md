# EEG-Based Hand Gesture Recognition

### MSc Artificial Intelligence and Robotics | Machine Learning & Deep Learning

## Project Overview

This research investigates the classification of hand movement states using Electroencephalography (EEG) signals and machine learning techniques. The project explores the potential of brain-signal-based gesture recognition to support intelligent patient monitoring and assistive communication systems.

The study compares traditional machine learning algorithms, deep learning architectures, and hybrid CNN–machine learning approaches to identify effective methods for EEG-based movement classification.

## Research Objectives

- Process and prepare EEG signals for gesture classification.
- Classify three movement states: no movement, mild movement, and strong movement.
- Implement and evaluate traditional machine learning classifiers.
- Investigate Convolutional Neural Networks (CNNs) and hybrid CNN–ML architectures.
- Compare classification performance using accuracy, precision, recall, F1-score, and confusion matrices.
- Assess the potential of these approaches for assistive healthcare applications.

## Methodology

1. EEG data collection: A publicly available EEG dataset was used for the research.
2. Data preprocessing: EEG signals were prepared and transformed into structured inputs suitable for classification.
3. Model development: SVM, KNN, Random Forest, XGBoost, and CNN classifiers were investigated.
4. Hybrid modelling: CNN-based feature extraction was combined with machine learning classifiers.
5. Hyperparameter optimisation: GridSearchCV was used to optimise model configurations.
6. Evaluation: Models were compared using classification metrics and experimental results.

## Machine Learning Models

- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Random Forest
- XGBoost
- Convolutional Neural Network (CNN)
- Hybrid CNN–Machine Learning models

## Experimental Results

| Model | Classification Accuracy |
|---|---:|
| XGBoost | 85% |
| Random Forest | 83% |
| CNN | 74% |
| CNN + XGBoost | 69% |
| SVM | 68% |

XGBoost achieved the highest reported classification accuracy of 85%, followed by Random Forest at 83%. The standalone CNN achieved 74%, while the evaluated CNN–XGBoost hybrid reached 69%.

These results suggest that ensemble learning methods can outperform more complex deep learning and hybrid architectures for the EEG classification task investigated.

## Key Findings

- XGBoost demonstrated the strongest overall classification performance.
- Random Forest provided competitive results.
- CNN offered a useful deep learning benchmark.
- Hybrid CNN–ML integration did not outperform the strongest standalone models.
- Model selection and feature compatibility are important considerations for EEG-based classification.

## Potential Applications

- Intelligent patient monitoring
- Brain–computer interface research
- Assistive communication technologies
- EEG-based movement intention recognition
- Human–computer interaction

## Limitations and Future Work

The findings are based on experimental evaluation and do not establish clinical or real-time deployment readiness.

Future work could investigate advanced EEG signal processing, improved hybrid feature integration, testing across participants, real-time inference, and validation in practical healthcare settings.

## Conclusion

This MSc research demonstrates the potential of machine learning for recognising movement states from EEG signals. XGBoost achieved the strongest performance among the evaluated models, highlighting the value of systematic algorithm comparison when developing EEG-based assistive technologies.
