# Audio Sentiment Analysis

## Abstract
This repository presents a comprehensive methodology for performing audio sentiment analysis using natural language processing techniques and machine learning algorithms. The approach involves noise removal, feature extraction, and classifier training, demonstrated on the Crema D dataset with 7442 labeled audio clips showcasing various emotions.

## Introduction
Sentiment analysis, often focused on textual data, is extended to audio in this paper. The proposed methodology covers noise reduction, feature extraction using techniques like MFCCs and Fourier transform, and classifier training with models such as SVM, KNN, and Neural Networks. The Crema D dataset is employed, offering diverse emotions and ethnic backgrounds.

## Methodology
The methodology details noise removal using the Butterworth method, dataset splitting, and the formulation of mathematical models (KNN, Logistic Regression, Naive Bayes, SVM, and Neural Network). Feature extraction involves techniques like MFCC, Chromagram, Mel-Spectrogram, and more.

## Identification and Extraction of Features
This section explores audio features such as Fourier Transform, MFCC, Mel-Spectrogram, Chromagram, Bi-coherence, Spectral Centroid, Spectral Bandwidth, and Spectral Contrast. Extracted features provide valuable information for sentiment analysis.

## Mathematical Formulation
Mathematical formulations for machine learning models (KNN, Logistic Regression, Naive Bayes, SVM, Neural Network) are presented, outlining their use in multi-class classification for audio sentiment analysis.

## Finding and Results
Results are provided for each classifier, with SVM identified as the best performer based on accuracy and F1 score. The challenges of audio sentiment analysis and potential improvements are discussed.

## Conclusion
The SVM classifier emerges as the optimal choice for audio sentiment detection in diverse datasets, emphasizing the complexity of analyzing emotions in speech patterns across different ethnicities.

## Dataset
The study utilizes the Crema D dataset, containing 7442 labeled audio clips with diverse emotions and ethnic backgrounds.

## Acknowledgments
This work is built upon the Crema D dataset and leverages various machine learning and natural language processing techniques.
