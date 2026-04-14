# Deepfake Audio Detection using Log-Mel Spectrogram & CNN

Author: Mohammad Tyas Subianto, Daris Ikhwana Khoir Suhaya

Accuracy: 86% | Recall (Fake): 91%

## Overview
This project aims to detect synthetic audio (Deepfakes) using a Digital Signal Processing (PSD) approach. The system converts the audio signal into a visual representation (Log-Mel Spectrogram) and classifies it using a Convolutional Neural Network (CNN).

## Key Results
- 91% Recall in the Fake class: The system is highly sensitive in detecting voice manipulation attacks.
- Visual Evidence: Significant differences in energy distribution patterns were found between genuine and fake audio in the frequency domain (cut-off frequency and checkerboard artifacts).

## Tech Stack
- **Language:** Python
- **Audio Processing:** Librosa (STFT, Mel-Scale)
- **Deep Learning:** TensorFlow / Keras (CNN)
- **Visualization:** Matplotlib, Seaborn

## Dataset
This project uses **The Fake-or-Real (FoR) Dataset - 2 Seconds Version**.
> **Note:** The dataset is not included in this repo due to its large file size.
> Please download the original dataset at: [https://www.kaggle.com/datasets/mohammedabdeldayem/the-fake-or-real-dataset]

## How to Run
1. Clone this repo.
2. Download the dataset and place it in the `for-2seconds` folder.
3. Install dependencies: `pip install librosa tensorflow matplotlib numpy`
4. Run the `Try FFT (1).ipynb` notebook.

---
