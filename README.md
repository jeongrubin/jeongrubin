

Computer Vision과 Deep Learning을 공부하고 있습니다. 논문이나 아이디어를 직접 구현해보고, 실험 결과를 비교하면서 이해하는 것을 좋아합니다.
주로 Object Detection, Image Classification, 3D Vision 등에 관심이 있습니다.

이 저장소에는 공부하면서 구현한 프로젝트와 실험들을 정리하고 있습니다.

📫 **Contact**: sudongbomi@gmail.com

---

## 🛠 Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLOv8-111F68?style=flat-square&logo=yolo&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

---

## 📌 Projects

### [육계 폐사체 후보 탐지](https://github.com/jeongrubin/broiler-carcass-candidate-detection)
`2025.03 – 2025.09` · 지도교수 연구 (학위논문)

상업 육계사 CCTV에서 개체별 120분 마스크 시퀀스를 분석해 폐사 가능성이 높은 개체를 선별하는 영상 AI 연구. `2×2 타일 YOLOv8s 탐지 → U-Net 이진 마스크 → MobileNetV2-BiLSTM 시계열 분류` 파이프라인을 직접 설계하고, 실제 농장 영상 147개 사례로 종단 간(end-to-end) 평가까지 수행했습니다.

`YOLOv8` `U-Net` `MobileNetV2` `BiLSTM` `PyTorch`

---

### [화재 세그멘테이션 모델 비교](https://github.com/jeongrubin/Performance-Comparison-of-Fire-Segmentation-YOLOv8-Fast-SCNN-and-Mask-R-CNN)
`2024.10 – 2024.11` · 개인 프로젝트

YOLOv8-Seg, Fast-SCNN, Mask R-CNN 세 가지 세그멘테이션 모델의 정확도·속도 트레이드오프를 비교 분석. 정확도(mIoU/F1)와 실시간 처리 속도(FPS)를 함께 측정해, 목적에 따라 어떤 모델이 적합한지 실증적으로 제시했습니다.

`YOLOv8-Seg` `Fast-SCNN` `Mask R-CNN` `PyTorch` `OpenCV`

---

### [전주대 비교과 프로그램 추천 챗봇](https://github.com/jeongrubin/Chat-Bot)
`2025.02` · 개인 프로젝트

학교 비교과 프로그램 데이터를 검색하고 사용자 관심사에 맞는 프로그램을 추천하는 Streamlit 앱. TF-IDF 기반 로컬 검색을 우선 적용해, API 키 없이도 동작하고 답변의 근거를 항상 검색 결과에 두도록 설계했습니다.

`Python` `Streamlit` `scikit-learn`

---

### [차선 훼손 분류](https://github.com/jeongrubin/-Lane-damage-classification)
`2024.03 – 2024.07` · 개인 프로젝트 (4학년)

차량 내부 카메라 영상만으로 차선 훼손 여부를 분류할 수 있는지 탐구한 초기 프로젝트. CNN 베이스라인과 ResNet18을 비교했고, 작은 데이터셋에서의 클래스 불균형 문제를 직접 다뤄본 경험을 담았습니다.

`PyTorch` `CNN` `ResNet18`
