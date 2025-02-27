# [Programmers 2021 Dev-Matching: 머신러닝 개발자](https://career.programmers.co.kr/competitions/1109)

## 대회 설명
- 227*227 크기의 이미지를 7개의 클래스로 분류

&nbsp;

## Hyper-parameter

- Seed: 0

- epochs: 100

- early stop count: 10

- Learning rate: 1e-3

- batch size: 32

- num workers: 4

&nbsp;

## Architecture

- Model: swsl_resnext50_32x4d (pretrained)

- Optimizer: AdamW

- Loss function: LabelSmoothingLoss

- Scheduler: ReduceLROnPlateau

&nbsp;

## 결과
- Public LB: Score 97.143, Rankings 25
- **Private LB Score 97.1, Rankings 10**

![스크린샷 2022-11-21 오전 10 30 14](https://user-images.githubusercontent.com/33628588/202941968-0ced9808-dcf2-40aa-84e6-3262e5bb008c.png)
