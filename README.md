# 🎧  Hybrid Methods for Audio DeepFake Detection Using Spectral and Frequency Features

📌 Overview
Abstract—The rapid advancement of artificial intelligence and audio generation technologies has raised serious concerns about the spread of deepfake audio. Although several datasets exist for detecting audio deepfakes, high-quality resources for the Vietnamese language remain scarce. To address this gap, we introduce ViAudioDetect v1, a dataset designed for Vietnamese audio deepfake detection. Given Vietnamese’s unique phonetic and tonal characteristics, a dedicated dataset allows models to capture these features better, improving detection accuracy. In contrast, models trained on multilingual datasets often underperform when applied to Vietnamese due to language-specificnuances. We adopt an ensemble learning approach using stacking to enhance performance, which helps reduce individual model errors and improves overall robustness. We evaluate the proposed method using four acoustic features: MFCC, CQCC, F0, and Mel-Spectrogram. Experimental results show that our approach achieves over 90% accuracy on both Vietnamese ViAudioDetect v1 and the English ASVSpoof2021 datasets. These findings highlight the effectiveness of ensemble learning in improving deepfake audio detection, p

 ## 🧪 Features Used
- MFCC (Mel Frequency Cepstral Coefficients)

- Mel-Spectrogram

- CQCC (Constant Q Cepstral Coefficients)

- F0 (Fundamental Frequency)

## 🧠 Models Applied

- Baseling models: SVM, RF, XGB, DT, GNB
  
- CNN Architectures: CNN, VGG16, ResNet50, MobileNet

- Ensemble Learning: Stacking Classifier with Decision Tree as the meta-model


## 📁 Source Code Structure

public_project_add_marp/

├── Features Extractor/   # Extracting accoustic features from audio input

├── Tools/                # Ultis functions to help processing.

├── Models/             # Jupyter notebooks for EDA and experiments

├── requirements.txt       

└── README.md

📚 Dataset
| Datasets          | Link |
|------------------|------------|
| ASVSpoof2021  |  [ASVSpoof2021](https://www.asvspoof.org/index2021.html)     |
|  ViAudioDetect v1| [ViAudioDetectV1](https://drive.google.com/file/d/1bBJgSXIdQliAYTxGbnMvkDEYu8mCZN7O/view?usp=sharing)   |


