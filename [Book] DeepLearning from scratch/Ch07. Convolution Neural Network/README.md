# 6. Training techniques
## a. Lesson learned
- Neural network(신경망) 학습의 목적은 Loss function(손실 함수)의 값을 가능한 한 낮추는 Parameter(매개변수)를 찾는 것이다.

- 이러한 과정을 Optimization(최적화)라고 한다.
- SGD는 단순하지만 효과적이다.  이와 다른 최적화 기법도 존재한다.

- SGD의 단점: 비등방성(anisotropy) 함수라는 점.

- Momentum: SGD에 속도 개념을 추가하여 비교적 빠르게 최적해를 찾아간다.

- AdaGrad: adaptive learning rate를 이용한다.

- Adam
- 가중치의 초깃값을 0으로 둔다는 말을 이해 못했음
- 대략적으로 이해한 것은, 가중치라는 것이 신경망 내부의 가중치다.
- 근데 어차피 초기에 가중치를 넣어줘야 하는데, 랜덤하게 넣어줘야한다.
- 근데 그대로 출력해주면 시그모이드라 0과 1에 수렴한다.
- 이를 방지하기 위해서 표준편차를 0.01로 변경하거나 Xavier 초깃값을 사용하면 가중치의 분포로 고루 펼쳐진다.

- 층이 깊어져도 가중치 분포가 균일하게 되어야 한다.
- 점차 한쪽으로 치우치게 되면 Gradient vanishing이 된 것이다. (기울기 소실)

- 배치 정규화

- 

## b. Programming
- 

# Futher study
1. Sigmoid 함수의 미분하는 방법
2. Adam의 구현?
3. SGD, 모멘텀, AdaGrad, Adam 중 장단점이 무엇일까? (책 기준 많은 연구에서 SGD를 쓰고 모멘텀과 AdaGrad도 가치 있지만, Adam을 많이 쓰는 듯.
4. 6.1.8 그리기
5. Norm의 개념이 정확히 필요

# Self-made Question


