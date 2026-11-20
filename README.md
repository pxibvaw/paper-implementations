# Paper Implementations (Computer Vision)

숙명여자대학교 IVPL 학부연구생 활동으로, 분류·탐지·초해상화 논문을 매주 한 편씩 골라 핵심 아이디어를 정리하고 모델을 구현한 뒤 랩에서 발표했습니다. (2026.01 – 2026.07, 14편)

📄 **발표자료(PDF)와 코드 링크 전체 목록:** [Notion 페이지](https://app.notion.com/p/Weekly-Paper-Implementation-41dc620638bf8131a0fdf26db8325474)

## Classification (9)

| # | 논문 | 연도 | 핵심 아이디어 |
|---|---|---|---|
| 1 | LeNet-5 | 1998 | 합성곱·풀링으로 지역 특징을 뽑는 초기 CNN 구조 |
| 2 | AlexNet | 2012 | ReLU·Dropout·GPU 학습으로 깊은 CNN을 대규모 데이터에 학습 |
| 3 | VGGNet | 2014 | 3×3 합성곱을 깊게 쌓아 깊이에 따른 성능 향상 확인 |
| 4 | GoogLeNet (Inception) | 2014 | Inception 모듈과 1×1 합성곱으로 연산 효율화 |
| 5 | ResNet | 2015 | Skip Connection으로 매우 깊은 망의 학습 문제 해결 |
| 6 | Inception-ResNet | 2016 | Inception 모듈에 잔차 연결을 결합해 학습 속도와 성능 개선 |
| 7 | NASNet | 2017 | Neural Architecture Search로 셀 구조를 자동 탐색 |
| 8 | EfficientNet | 2019 | 깊이·너비·해상도를 함께 키우는 Compound Scaling |
| 9 | Noisy Student | 2019 | 노이즈를 준 학생 모델로 반복하는 자기 학습(Self-training) |

## Detection (4)

| # | 논문 | 연도 | 핵심 아이디어 |
|---|---|---|---|
| 10 | Faster R-CNN | 2015 | RPN으로 후보 영역 생성까지 학습하는 2-stage 탐지기 |
| 11 | Mask R-CNN | 2017 | Faster R-CNN에 마스크 분기와 RoIAlign을 더한 인스턴스 분할 |
| 12 | YOLOv3 | 2018 | 다중 스케일 예측을 하는 1-stage 실시간 탐지기 |
| 13 | EfficientDet | 2019 | BiFPN과 Compound Scaling을 적용한 효율적 탐지기 |

## Super-Resolution (1)

| # | 논문 | 연도 | 핵심 아이디어 |
|---|---|---|---|
| 14 | SRCNN | 2014 | 저해상도→고해상도 매핑을 3층 CNN으로 끝단 간 학습한 초해상화 모델 |

## 개인 구현 (1)

랩 발표와 별도로 직접 읽고 구현한 논문입니다.

| 논문 | 연도 | 핵심 아이디어 |
|---|---|---|
| ViT (Vision Transformer) | 2020 | 이미지를 16×16 패치 시퀀스로 보고 Transformer 인코더로 분류 |

## 진행 방식
1. 논문의 문제 설정과 핵심 아이디어를 문제 → 해결 과정으로 정리
2. 모델 구조를 TensorFlow / PyTorch로 직접 구현하고 추론까지 확인
3. 발표자료를 만들어 주 1회 발표
