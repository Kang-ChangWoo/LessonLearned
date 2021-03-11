# 5. Backpropagation
## a. Lesson learned
- Backpropagation의 가장 핵심 포인트는 거꾸로 미분이다.
  : 기본적으로 정방향으로 진행되는 어떤 계산 그래프가 있다면 각 부분을 나누면 함수의 겹겹으로 구성된다.
    이를 역순으로 미분하면 맨 처음 input 값에 따른 결과값을 알 수 있다.

- Computational graph 계산 그래프의 정의: 계산 과정을 그래프로 나타낸 것
  각 값은 에지로 표현하고, 연산을 노드에 표현한다.

- Node 노드의 정의: 네트워크를 그렸을 때 각 점을 노드라고 한다.

- Edge 에지의 정의: 네트워크를 그렸을 때, 각 연결을 에지라고 한다.

- forward propagation(순전파)과 backward propagation의 차이:
  forward propagation는 계산 그래프를 정순대로 진행하는 것
  backward propagation은 계산 그래프를 역순대로 진행하는 것
  
- 국소적 계산: 계산 그래프 내에서 각 노드는 자기와 연관된 에지의 계산만 고려하면 된다.
  전체 과정이 복잡하더라도 단순하게 계산할 수 있다.
  
- 계산 그래프로 문제를 푸는 이유.
1. 국소적 계산으로 문제를 단순화 가능
2. 중간 계산 결과를 저장할 수 있다.
3. 가장 중요한 것은 미분을 효과적으로 할 수 있다.(?)

- Composite function, 합성함수의 정의:
  합성 함수의 미분은 합성 함수를 구성하는 가 함수의 미분의 곱으로 나타낼 수 있다.

- 연쇄법칙 Chain rules

- 어파인 변환 (Affine Transformation)의 정의: 행렬의 곱

## b. Programming
- 

# Futher study
1. Sigmoid 함수의 미분하는 방법

# Self-made Question


