# 정수빈 포트폴리오

Python으로 컴퓨터 비전 모델을 학습하고 결과를 분석해 왔습니다. 객체 탐지와 세그멘테이션, 시계열 영상 분석에 관심이 있습니다.

이메일: sudongbomi@gmail.com

## 학력

- 전주대학교 인공지능학과 졸업 (2021.03–2025.02)

- 전주대학교 일반대학원 Agro AI학과 석사 졸업, 학·석사 연계과정 (2025.03–2026.08)

## 주요 프로젝트

### [마스크 시퀀스 분석을 이용한 육계 폐사체 후보 탐지](https://github.com/jeongrubin/broiler-carcass-candidate-detection)

2025.03–2025.09 · 학위논문 연구

상업 육계사 CCTV에서 폐사 가능성이 높은 개체를 먼저 찾는 연구입니다. 한 장의 이미지로는 휴식 중인 개체와 폐사체를 구분하기 어려워, 개체별로 120분 동안 생성된 이진 마스크의 변화를 분석했습니다.

데이터 구축부터 YOLOv8s 탐지, U-Net 마스크 생성, MobileNetV2-BiLSTM 분류와 실제 농장 영상 평가까지 진행했습니다. 147개 영상 사례를 평가했으며, 최종 모델의 F1-score는 0.7961이었습니다.

사용 기술: Python, PyTorch, YOLOv8, U-Net, BiLSTM

### [화재 영역 세그멘테이션 모델 비교](https://github.com/jeongrubin/Performance-Comparison-of-Fire-Segmentation-YOLOv8-Fast-SCNN-and-Mask-R-CNN)

2024.10–2024.11 · 개인 프로젝트

YOLOv8-Seg, Fast-SCNN, Mask R-CNN을 학습해 화재 영역 분할 성능과 처리 속도를 비교했습니다. 저장된 가중치와 테스트 데이터로 결과를 다시 확인한 기록도 함께 정리했습니다.

### [전주대학교 비교과 프로그램 추천 챗봇](https://github.com/jeongrubin/Chat-Bot)

2025.02 · 개인 프로젝트

학교 비교과 프로그램을 검색하는 Streamlit 앱입니다. TF-IDF 로컬 검색을 기본으로 사용하며, Gemini API가 설정된 경우 검색 결과를 바탕으로 답변을 생성합니다.

[배포된 챗봇 실행하기](https://jeongrubin-chatbot-demo.streamlit.app/)

### [차선 훼손 분류 및 세그멘테이션](https://github.com/jeongrubin/-Lane-damage-classification)

- 2024.03–2024.07: 차선 훼손 등급 분류 및 폴리곤 라벨링
- 2026.09: 기존 라벨 데이터를 활용한 U-Net 세그멘테이션 추가 실험

차량 카메라 이미지로 차선의 훼손 등급을 분류하고, 폴리곤 라벨을 이용해 훼손 위치를 찾는 U-Net 실험을 진행했습니다.

## 사용 기술

Python을 주로 사용합니다. PyTorch로 모델을 학습하고 OpenCV로 영상과 이미지 데이터를 처리했습니다. 결과 확인용 웹 화면은 Streamlit으로 구현했습니다.
