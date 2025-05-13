🎧 DeepFake Audio Detection using Acoustic Features
A machine learning and deep learning based approach to detect deepfake audio using acoustic features like MFCC, Mel-Spectrogram, CQCC, and F0.

📌 Overview
This project focuses on detecting deepfake (AI-generated) audio using various acoustic features and deep learning models. We extract features such as MFCC, Mel-Spectrogram, CQCC, and F0, then apply CNN-based architectures (like VGG16, ResNet50, and MobileNet) and ensemble methods with Stacking Classifier to classify genuine vs fake audio.

🧪 Features Used
MFCC (Mel Frequency Cepstral Coefficients)

Mel-Spectrogram

CQCC (Constant Q Cepstral Coefficients)

F0 (Fundamental Frequency)

🧠 Models Applied
CNN Architectures: VGG16, ResNet50, MobileNet

Ensemble Learning: Stacking Classifier with Decision Tree as the meta-model

Optimization: Genetic Algorithm (GA) for model selection and hyperparameter tuning

🏗️ Architecture
Preprocessing: Convert audio files into acoustic features

Feature-Specific Modeling: Train a dedicated CNN for each feature type

Ensemble: Combine predictions using Stacking Classifier

Optimization: Use Genetic Algorithm to optimize model combination

📁 Project Structure
bash
Sao chép
Chỉnh sửa
deepfake-audio-detection/
├── data/                  # Audio data
├── features/              # Extracted features
├── models/                # Saved models
├── notebooks/             # Jupyter notebooks for EDA and experiments
├── utils/                 # Feature extraction and training scripts
├── main.py                # Main pipeline
├── requirements.txt       
└── README.md
🚀 Getting Started
Clone the repo
bash
Sao chép
Chỉnh sửa
git clone https://github.com/your-username/deepfake-audio-detection.git
cd deepfake-audio-detection
Install dependencies
bash
Sao chép
Chỉnh sửa
pip install -r requirements.txt
Run the pipeline
bash
Sao chép
Chỉnh sửa
python main.py
🧬 Genetic Algorithm Optimization
We use GA to:

Select the best CNN model for each feature

Optimize stacking weights and meta-model hyperparameters

📊 Results
Feature	Best Model	Accuracy
MFCC	VGG16	92.5%
Mel-Spectrogram	ResNet50	94.1%
CQCC	MobileNet	91.3%
F0	VGG16	89.8%

Stacking Ensemble achieves an overall accuracy of 96.4%.

📚 References
WaveFake: Detecting Fake Speech using Audio Fingerprints

DeepSonar: Towards Effective and Robust Detection of AI-Synthesized Fake Voices

📄 License
This project is licensed under the MIT License.
