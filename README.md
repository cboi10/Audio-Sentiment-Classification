# Audio Sentiment Classification

## Introduction
This project aims to classify emotions in speech using the Ryerson Audio-Visual Database of Emotional Speech and Song (RAVDESS). The model employs machine learning techniques, specifically utilizing Mel Frequency Cepstral Coefficients (MFCC) for feature extraction and a deep learning architecture to predict emotions.

## Dataset
The RAVDESS dataset contains 1440 audio files categorized into eight emotional labels: calm, happy, sad, angry, fearful, disgusted, surprised, and neutral. It offers a balanced representation of gender and emotions, making it suitable for training a robust model.

## Implementation
The implementation involves the following steps:
1. **Data Preprocessing**: Audio files are loaded, and features are extracted using MFCC.
2. **Model Development**: A neural network model is constructed using Keras, with hyperparameters optimized through Keras Tuner.
3. **Training**: The model is trained on the extracted features, validating its performance on a separate test set.

## Applications
The Voice Sentiment Classification model has various applications, including:
- **Customer Service**: Analyzing customer interactions to gauge satisfaction and emotional tone.
- **Mental Health**: Assisting in the diagnosis and treatment of emotional disorders by monitoring speech patterns.
- **Human-Computer Interaction**: Enhancing user experience by enabling systems to respond to the emotional state of users.

## Conclusion
This project showcases the potential of machine learning in understanding human emotions through speech. Future work could focus on expanding the dataset and refining the model for improved accuracy and real-time application.
