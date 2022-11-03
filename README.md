# Prediction of seafood import price using attention method
<p align="center">
  <img src="assets/front_page.png" width="700">
</p>

2021 빅콘테스트 챔피언 리그 - 수산물 Biz 분야 본선 진출


## Task : 수산물 수입가격 예측을 통한 최적의 가격 예측 모형 도출
<p align="center">
  <img src="assets/task.png" width="700">
</p>

### 분석방향 
- 계절성을 반영 : 해당 수산물 생산국가의 수온 데이터 
- 수산물의 공급량 반영 : 해당 거래의 중량 데이터 
- 기존 데이터 + 수온 데이터 & 중량 데이터 수집 -> **계절성과 수산물의 공급량을 반영한 수산물 수입가격 예측 모델 생성** 

## 

## Requirements
```
tensorflow>=2.x
keras
prophet
neuralprophet 
```
