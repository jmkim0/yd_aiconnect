# AI CONNECT 이어드림 모의경진대회
## 개인전 / 대출자 채무 불이행 예측 (22.01.26 ~ 22.02.08) [[링크]](https://github.com/jmkim0/yd_aiconnect/tree/main/1-bankrupt)
p2p 대부업체의 고객 데이터를 활용한 채무 불이행 여부 예측 과제 수행
- scikit-learn, XGBoost, LightGBM, CatBoost 등 라이브러리의 이진 분류 모델 활용
- 성능 향상을 위해 stacking ensemble 활용
- 총 58명 중 9위 (F1-macro: 0.7126754895)
## 팀전 / 흉부 CT 코로나 감염 여부 분류 (22.02.09 ~ 22.02.15) [[링크]](https://github.com/jmkim0/yd_aiconnect/tree/main/2-covid_ct)
흉부 CT 이미지를 이용해 코로나19 감염 여부를 이진 분류
- PyTorch 기반 CNN 모델 활용 (Resnet, Densenet, Regnet 등 코드 공개된 모델 사용)
- 성능 향상을 위해 data augmentation 활용
- 총 15팀 중 10위 (Accuracy: 0.7285714286)
## 팀전 / 교통 물류 통행량 시계열 예측 (22.02.16 ~ 22.02.22) [[링크]](https://github.com/jmkim0/yd_aiconnect/tree/main/3-highway_traffic)
35개 도로의 시간별 물류 통행량 데이터를 학습, 이를 기반으로 기준시점 이후 물류 통행량을 예측하는 과제
- pandas, matplotlib 등 Python  라이브러리를 활용한 EDA, 단순 통계 모델 (평균, 가중평균 등) 기반 예측
- ARIMA, Prophet 등 시계열 예측 모델 실험
- 총 16팀 중 1위 (RMSE: 3790.5081883203)
## 팀전 / 비매너 댓글 식별 (22.02.23 ~ 22.03.04) [[링크]](https://github.com/jmkim0/yd_aiconnect/tree/main/4-comment_bias_hate)
뉴스 기사의 댓글 (comment) 중 편견, 혐오 표현 (bias, hate)이 포함된 댓글을 식별하는 과제
- Hugging Face Transformers 라이브러리와 BERT, ELECTRA 등 사전학습된 모델을 활용한 분류
- 한국어 뉴스 댓글로 사전학습된 KcELECTRA 모델 사용
- F1-macro 평가 지표 향상을 위해 bias, hate label을 각각  fine-tuning
- 총 16팀 중 2위 (F1-macro: 0.7502138408)
