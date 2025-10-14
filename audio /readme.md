Audio Classification using Naive Bayes Model
📘 Project Overview

This Jupyter Notebook presents an audio emotion classification project using a Naive Bayes model.
The project leverages the RAVDESS Emotional Speech Audio Dataset, where actors express different emotions in short audio recordings.
It demonstrates the full pipeline — from audio preprocessing and feature extraction to machine learning classification.

🎯 Dataset Information

Dataset: RAVDESS (Ryerson Audio-Visual Database of Emotional Speech and Song)
Total Samples: 2,880 .wav audio files
Duration: ~3 seconds per audio file
Format: WAV (mono, 48kHz)

📂 Dataset Structure

Actors: 24 (12 male, 12 female)

Emotions:

Neutral

Calm

Happy

Sad

Angry

Fearful

Disgust

Surprised

Repetitions: 2 per emotion per actor

Sample Count Calculation:

24 actors × 8 emotions × 2 repetitions = 1,440 samples

🔧 Technical Implementation
🧠 Libraries Used

Librosa → Audio analysis and feature extraction

Noisereduce → Noise reduction preprocessing

NumPy → Numerical operations

Pandas → Data manipulation

Matplotlib / Seaborn → Visualization

Scikit-learn → Naive Bayes model, training, and evaluation

🎚️ Audio Features Extracted

MFCCs (Mel Frequency Cepstral Coefficients)

Chroma features (harmonic & melodic content)

Spectral contrast (frequency amplitude variation)

Zero-crossing rate (signal oscillation frequency)

RMS energy (signal power)

Spectral flatness (tone/noise ratio)

🚀 Project Workflow
1. Data Loading

Recursively loads all .wav audio files from the dataset directory.

2. Audio Preprocessing

Noise reduction using noisereduce

Feature extraction using librosa

3. Feature Engineering

Extracts multiple acoustic features

Combines them into a structured DataFrame

Prepares numerical inputs for model training

4. Model Training

Implements Naive Bayes Classifier (GaussianNB or MultinomialNB)

Trains model on extracted features

5. Evaluation

Evaluates accuracy and confusion matrix

Analyzes emotion classification performance

📊 Key Highlights

✅ Multi-feature audio analysis pipeline
✅ Noise reduction for cleaner data
✅ Emotion classification across 8 emotional categories
✅ Visualization of waveforms, spectrograms, and model performance
✅ Complete audio preprocessing and machine learning workflow

🎵 Audio Processing Capabilities

The notebook provides functionality to:

Load and play audio samples

Visualize waveforms and spectrograms

Extract detailed audio features

Train and evaluate an emotion classifier

⚙️ Requirements
pip install librosa noisereduce numpy pandas matplotlib seaborn scikit-learn

💻 Usage

Clone the repository:

git clone https://github.com/yourusername/audio-classification-naive-bayes.git
cd audio-classification-naive-bayes


Open the notebook:

jupyter notebook audio-classification-naive-bayes.ipynb


Run all cells sequentially to:

Load the dataset

Extract audio features

Train the Naive Bayes model

Evaluate and visualize results

🧾 Summary

This project showcases how classical machine learning models can effectively classify emotional content in audio signals.
By combining feature extraction, preprocessing, and Naive Bayes classification, it provides a clear and practical introduction to audio emotion recognition using open-source tools.

Would you like me to make a sho
