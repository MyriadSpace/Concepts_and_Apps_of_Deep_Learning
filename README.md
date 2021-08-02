# Concepts_and_Apps_of_Deep_Learning
## 정오표 (errata)
* 18 쪽, 맨 아랫줄: L2 = 17 --> L2 = sqrt(17) 
* 30 쪽, 식 (1.20): <img src="https://render.githubusercontent.com/render/math?math={\left ( y^{k}-w_{1}^{k}x_{1}^{k} %2B w_{2}^{k}x_{2}^{k} %2B ...w_{n}^{k}x_{n}^{k} \right )}^{2} \rightarrow {\left ( y^{k}- \left ( w_{1}^{k}x_{1}^{k} %2B w_{2}^{k}x_{2}^{k} %2B ...w_{n}^{k}x_{n}^{k} \right ) \right )}^{2}">
* 58 쪽, 위에서 7번째 줄: 진화발생생물학 --> 진화발달생물학
* 61 쪽, 아래서 5번째 줄: 헵스 법칙 --> 헵의 법칙, 헵스 룰
* 62 쪽, 위에서 3번째, 4 번째 줄: 헵스 규칙 --> 헵의 규칙, 헵스 학습 --> 헵의 학습
* 104 쪽, 위에서 4번째 줄: 텐서플로우는 --> 텐서플로우의
* 182 쪽, 3번째 줄: n개의 객체 --> n개의 개체
* 216 쪽, 위에서 5번째 줄: 0 ~ 256 사이의 정수 --> 0 ~ 255 까지의 정수
* 252 쪽, 아래서 9번째 줄 ~ 6번째 줄: Xception (eXtreme Inception)과 depthwise separabel convolution 추가 설명 필요
** Xception: 1x1 pointwise convoltuion 이후 너비x높이 공간(spatial) 컨볼루션 계산
** Depthwise Separable Convoltuion: 너비x높이 공간(spatial) 컨볼루션 계산 이후 1x1 pointwise convoltuion 계산
** Xception 방식과 Depthwise Separable Convoltuion 방식의 결과는 차이가 없음
** TensorFlow Keras나 PyTorch는 각각 DepthwiseConv2D, SeparableConv2D 로 지원하고 있음
** 1x1 point-wise 컨볼루션 --> depthwise 분리된 컨볼루션 (depthwise separable convolution) 
* 330 쪽, 맨 아랫줄: 이사전달 --> 의사전달
* 487 쪽, 아래서 두번째 줄: 안정정 --> 안정적
