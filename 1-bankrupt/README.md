# 대출자 채무 불이행 예측 - 개인전
p2p 대부업체의 고객 데이터를 활용한 채무 불이행 여부 예측 과제 수행
- scikit-learn, XGBoost, LightGBM, CatBoost 등 라이브러리의 이진 분류 모델 활용
- 성능 향상을 위해 stacking ensemble 활용
- 총 58명 중 9위 (F1-macro: 0.7126754895)
- 제출 코드: [tabular_bankrupt.ipynb](https://github.com/jmkim0/yd_aiconnect/blob/main/1-Solo_Competition/tabular_bankrupt.ipynb)
## 폴더 설명
### /catboost_info
CatBoost 학습 log 폴더
### /flaml
FLAML AutoML log, checkpoint, parameter 저장 폴더
### /result
예측 결과 저장 폴더