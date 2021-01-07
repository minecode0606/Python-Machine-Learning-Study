# KNN Algorithm
첫 번쨰 장에서는 머신러닝의 비지도학습 (Unsupervised Learning)의 가장 간단한 예시중 하나인 (KNN)K-Nearest Neighbor에 대해 알아보도록 하겠다.

## (KNN)K-Nearest Neighbor Algorithm이란
* KNN은 비지도학습 (Unsupervised Learning)릐 가장 간단한 예시입니다.
* 댜양한 레이블의 데이터 중에서, 자신과 가까운 데이터를 찾아 자신의 레이블을 결정하는 방식입니다. (~~거리에만 의존하므로 예즉에 필요한 특징의 갯수가 많아지면 성능이 급격히 떨어진다 ~~)

![CNNpicture](https://github.com/minecode0606/minecode0606/blob/main/images/Python_Machine_Learning/KNN(K_Nearest_Neighbor)/%EB%8B%A4%EC%9A%B4%EB%A1%9C%EB%93%9C.jfif)  

  
* 비매개변수 머신러닝 모델
* 훈련 단계에서 학습을 하지 않는다. (별명: 게으른 학습)
* 테스트 / 검증 잔계에서 테스트 관측값과 가장 근접한 훈련 관측값을 비교합니다.
* 거리에만 의존하므로 차원의 저주에 따라 예측에 필요한 특징의 개수가 늘어나면 성능이 크게 저하됨



