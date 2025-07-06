# 🎧  HỆ THỐNG NHẬN BIẾT AUDIO DEEPFAKE NHẰM PHÒNG CHỐNG LỪA ĐẢO QUA CUỘC GỌI

📌 Overview
Hiện nay, sự phát triển nhanh chóng của công nghệ AI mang lại nhiều lợi ích cho đời sống con người, nhưng cũng tiềm ẩn nhiều mối đe dọa khó lường. Một trong số đó là công nghệ “Deepfake”, đặc biệt là mạo danh giọng nói, đang trở thành nỗi lo lớn trong thời đại số. Khóa luận này tập trung nghiên cứu vấn đề lừa đảo qua các cuộc gọi trực tuyến sử dụng giọng nói giả mạo bằng AI nhằm chiếm đoạt tài sản. Qua việc tìm hiểu đặc trưng giọng nói, nhóm nhận thấy tiềm năng xây dựng hệ thống phát hiện giọng nói do AI tạo ra dựa trên những đặc điểm khó bị giả mạo. Về dữ liệu, nhóm xây dựng bộ âm thanh Deepfake tiếng Việt trải dài 3 miền Bắc – Trung – Nam, bám sát theo hướng tiếp cận của bộ dữ liệu ASVspoof2021 [1], gồm hai hình thức giả mạo phổ biến là Text-To-Speech và Voice Conversion. Dữ liệu đảm bảo đa dạng về giới tính, vùng miền, với tổng thời lượng trên 1300 phút.

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


