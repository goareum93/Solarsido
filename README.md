# 태양광발전 발전량 예측 기반 ESS 운영 방안 제공 서비스  
> 지역별 태양광 발전데이터와 날씨데이터 등을 수집하여 인공지능 기반으로 발전량을 예측하여 최적 ESS 운영방안 제시

## Introduction
- Full demo video  [ [link](https://youtu.be/bqdp7wjlU8k) ]
- Final Report  [ [link](https://github.com/goareum93/2021_KDT_hackathon/blob/master/06%2C%20Submition/Final/1.%20renewable_PPT.pdf) ]




## Project Process
![image-20211029193025699](README.assets/image-20211029193025699.png)

## Dataset

![image-20211029193033257](README.assets/image-20211029193033257.png)

![image-20211029193045457](README.assets/image-20211029193045457.png)

![image-20211029193056419](README.assets/image-20211029193056419.png)

## Models

- ![image-20211029193115136](README.assets/image-20211029193115136.png)

## Evaluation

- 총 3개의 모델 중 DNN 모델의 경우 낮은 score가 나왔기 때문에 제외
- 앙상블 모델 중 SVM과 GBR 사용하기로 결정
- GridSearch를 통해 최적화한 결과 점수가 비슷하지만 상대적으로 가볍고 빠른 GBR를 최종 모델로 선정

![image-20211029193245346](README.assets/image-20211029193245346.png)

## Application

- No-code 툴인 Bubble 활용 앱 디자인 및 구현

![image-20211029193717816](README.assets/image-20211029193717816.png)

![image-20211029193732970](README.assets/image-20211029193732970.png)

![image-20211029193543674](README.assets/image-20211029193543674.png)

## PV+ESS algorithm

![image-20211029193214226](README.assets/image-20211029193214226.png)

## Reference

[[link](https://www.notion.so/Main-b73c0f98c9d743e9ae39d6311c4003eb)]

