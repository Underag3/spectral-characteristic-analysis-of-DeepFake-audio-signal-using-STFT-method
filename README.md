# Deepfake Audio Detection using Log-Mel Spectrogram & CNN

**Author:** Mohammad Tyas Subianto, Daris Ikhwana Khoir Suhaya

**Accuracy:** 86% | **Recall (Fake):** 91%

## Overview
Project ini bertujuan untuk mendeteksi audio sintetis (*Deepfake*) menggunakan pendekatan **Pengolahan Sinyal Digital (PSD)**. Sistem mengubah sinyal suara menjadi representasi visual (**Log-Mel Spectrogram**) dan mengklasifikasikannya menggunakan **Convolutional Neural Network (CNN)**.

## Key Results
- **91% Recall pada kelas Fake**: Sistem sangat sensitif mendeteksi serangan manipulasi suara.
- **Visual Evidence**: Ditemukan perbedaan pola distribusi energi yang signifikan antara suara asli dan palsu di domain frekuensi (cut-off frequency & checkerboard artifacts).

## Tech Stack
- **Language:** Python
- **Audio Processing:** Librosa (STFT, Mel-Scale)
- **Deep Learning:** TensorFlow / Keras (CNN)
- **Visualization:** Matplotlib, Seaborn

## Dataset
Project ini menggunakan **The Fake-or-Real (FoR) Dataset - 2 Seconds Version**.
> **Catatan:** Dataset tidak disertakan dalam repo ini karena ukuran file yang besar.
> Silakan unduh dataset asli di: [Link ke Sumber Dataset/Kaggle]

## How to Run
1. Clone repo ini.
2. Download dataset dan letakkan di folder `for-2seconds`.
3. Install dependencies: `pip install librosa tensorflow matplotlib numpy`
4. Jalankan notebook `Try FFT (1).ipynb`.

---
*Project ini dibuat untuk memenuhi Tugas Akhir mata kuliah Pengolahan Sinyal Digital.*
