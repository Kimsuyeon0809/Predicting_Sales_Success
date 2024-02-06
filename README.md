# Predicting_Sales_Success
MQL 데이터 기반 B2B 영업기회 창출 예측 모델 개발

[24/02/06]
1차 제출 : baseline code 그대로 DecisionTreeClassifier()모델 사용
실행 결과 -> 정확도: 0.9601 / 정밀도: 0.7356 / 재현율: 0.7814 / F1: 0.7578
제출 결과 -> public score : 0.516304347826087

2차 제출 : baseline code의 DecisionTreeClassifier()모델을 RandomForestClassifier()모델로 변경
실행 결과 -> 정확도 0.9732 / 정밀도 : 0.9553 / 재현율 : 0.7001 / F1 score : 0.8080
제출 결과 -> public score : 0.17677286742034942
원인 분석 : 정밀도에 비해 재현율이 너무 낮다.
