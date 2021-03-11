# 5. Backpropagation
## a. Lesson learned
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

## b. Programming
- 10e-50을 float(32형) 32비트 부동소수점으로 나타내면 0.0이 되어 올바르게 표현할 수 없다.
- 반올림 오차(rounding error) 때문이다.
- np.zero_like(x) x와 형상이 같고 그 원소가 모두 0인 배열을 만든다. (array, df 다?)
- x.size (array?)
- 매개변수(Parameters)를 Params 라고 변수 이름을 짓기도 함 (naming convention)
- 클래스에서 사용하는 변수나 클래스의 메서드를 보여주는 방식을 배우면 좋을 듯

# Futher study
1. MSE 와 Entropy cross의 차이 (오차 측정 방식)
2. Source code 확인
3. 왜 미니배치를 했을 때 효과적인지?
4. Epoch과 minibatch의 정확한 차이?


# Self-made Question


