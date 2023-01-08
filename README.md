# Book-Sales-Forecast-Model
> 1~11월 도서 판매 데이터를 활용한 12월 도서 판매량 예측 모델

## Code 순서
1. submit_1_01_make_features_1 : Feature 생성 후 feature_1.pkl로 저장
2. submit_1_02_dnn_model_with_ensemble_1 : feature_1.pkl을 활용한 dnn 모델링
3. submit_1_03_make_features_2 : Feature 생성 후 feature_2.pkl로 저장
4. submit_1_04_dnn_model_with_ensemble_2 : feature_2.pkl을 활용한 dnn 모델링
5. submit_1_05_make_features_3 : Feature 생성 후 feature_3.pkl로 저장
6. submit_1_06_xgb_with_shap : feature_3.pkl을 활용한 xgb 모델링
7. submit_1_07_power_mean_ensemble : dnn 모델과 xgb 모델의 output을 앙상블
8. submit_2_08_make_features : Feature 생성 후 feature_4.pkl로 저장
9. submit_2_09_dnn_model_with_ensenble : feature_4.pkl을 활용하여 dnn 모델링 

## DNN1 Tune
- Train Data : 5월 ~ 11월 데이터
- Test Data : 12월 데이터
- StandardScaler
- Keras DNN
- Batch_size : 2048
- Epochs : 2000
- 모델 전체 seed 변경 20번 실행 

## DNN2 Tune
- Train Data : 7월 ~ 11월 데이터
- Test Data : 12월 데이터
- 세부사항 DNN1과 동일
