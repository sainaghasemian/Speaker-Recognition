# Speaker-Recognition
This project implements a speaker recognition system using Gaussian Mixture Models (GMMs) in Python. The goal is to classify a speaker's voice based on short audio samples, using Mel-Frequency Cepstral Coefficients (MFCCs) as features. The system is capable of identifying speakers in clean audio recordings and rejecting unknown speakers through threshold-based validation.

## How the System Works
Extracting MFCCs from speech recordings.
Training GMM models for each speaker based on their voice features.
Using log-likelihood scoring to classify new voice samples.
Applying a threshold to reject unknown speakers based on probe samples.

## Project Structure
/Speaker-Recognition
│
├── wav-files/                 # Folder containing training, testing, and probe audio files
│   ├── train/                 # Training data (audio files)
│   ├── test/                  # Testing data (audio files)
│   └── probe/                 # Probe data (unknown speaker samples)
│
├── speaker_recognition.ipynb  # Main script implementing the system
└── README.md                  # Project documentation (this file)

## How to Run This Notebook
1. Clone the Repository
2. Set Up Your Environment: pip install numpy scipy matplotlib scikit-learn python_speech_features
3. Launch Jupyter Notebook, or open the Notebook in a IDE like Visual Studio Code
4. Open speaker_recognition.ipynb and run each cell step by step.
