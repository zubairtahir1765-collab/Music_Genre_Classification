# Music_Genre_Classification
A comprehensive machine learning project that classifies music into different genres using both audio features and spectrogram images. This project implements and compares multiple approaches including traditional machine learning models, deep neural networks, and constitutional neural networks for music genre classification.

Dataset
This project uses the GTZAN Dataset, which contains:
1000 audio tracks (30 seconds each)
10 genres: blues, classical, country, disco, hiphop, jazz, metal, pop, reggae, rock
Two feature extraction approaches:
Tabular data: 58 audio features (MFCCs, chroma, spectral, rhythm features)
Spectrogram images: Visual representations of audio signals

 Features
1. Data Processing
Audio feature extraction using Librosa
Spectrogram generation from audio files
Comprehensive data preprocessing and normalization

2. Multiple Modeling Approaches
Tabular Data Models:
Random Forest Classifier
Support Vector Machine (SVM)
Dense Neural Network (Model_4)

Image Data Models:
Convolutional Neural Network (CNN) for spectrogram classification
Transfer learning approaches
