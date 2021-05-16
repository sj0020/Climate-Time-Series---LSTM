목표: 기온 훈련 데이터(기간:  2017-01-01 to 2021-01-01) 로 LSTM을 이용해서 날씨 예측 모델을 만들고, <br>
이를 테스트 데이터(기간: 2021-01-01 to 2021-03-31)와 적용 및 비교

1. 데이터분석 , 데이터 전처리

2. 데이터 변환
sklearn 전처리 과정을 사용해 0과 1사이로 스케일링 해서 데이터를 처리


3. 데이터 훈련
케라스로 sequential 순차모델 생성
trainX : 입력값, trainY: 입력된 값들이 실제 출력되기를 바라는 값, epochs: 학습시키는 크기, batch_size: 학습시킬때 묶음. 샘플의 수
이 훈련에서는 32 묶음 씩 100번을 학습시킴


출처: https://www.kaggle.com/ieshaan/delhi-climate-time-series-lstm
