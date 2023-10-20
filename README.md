# Mapping_Block_V1
목적

정형데이터를 2차원 벡터로 변환을 통하여 머신러닝이 주를 이루고 있는 정형데이터 분야에서 딥러닝 활용

정형데이터 분야에서 딥러닝 적용을 통한 추가적인 다양한 어플리케이션(생성 모델링, 준지도 학습…) 적용 가능

데이터셋

- UCI Vehicle silhouttes
- UCI Landsat Satellite
- UCI Image Segmentation
- Forest Cover Type

한계

- 머신러닝이 딥러닝에 비하여 짧은 학습 시간 소요에도 불구하고 비슷하거나 더 좋은 성능을 도출
- 과적합 문제로 인하여 모델 레이어를 깊게 구성하지 못함
- 정형데이터에 적합한 딥러닝 아키텍쳐 필요

method

- CNN이 학습하는 과정을 반대로 진행하여 정형데이터를 2차원 배열로 변환 하는 Mapping Block 제안
- 이미지형식인 2차원 배열로 변환하여 CNN을 접목하여 학습 진행
- 데이터를 변환하는 과정 또한 모델이 학습하며 데이터 변환
- 위를 통해 세가지 데이터셋에서 평균 정확도 90.22%달성

리뷰

정형데이터를 2차원 배열로 변환하며 학습을 진행하는 Mapping Block을 통하여 정형데이터의 딥러닝에서 컴퓨터비전 분야에서 성능이 높은 모델들을 결합하여 정확도 향상에 기여할 수 있을것이라 기대된다.