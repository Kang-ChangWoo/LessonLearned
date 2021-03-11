# 4. Neural network learning

- 시그모이드 함수와 계단 함수의 차이점
  : 신경망을 학습할 때, 정확도를 지표로 삼지 않고 손실 함수를 지표로 삼는다.
    정확도는 답을 맞췄다 못맞췄다, 로 나뉘기에 값이 이산적이다.
    손실 함수는 이에 반해 연속 값으로 이루어진다.
    따라서, 매개변수의 변화에 따른 변화값을 추적하기 용이하다.
    
    Sigmoid function과 step function도 이와 같은 원리일 것이다.
    Step function은 값이 한 순간 변화하는 꼴을 띄고 있다.
    Sigmoid function은 값이 지속적으로 변화를 일으킨다.
    
    이를 미분한다는 관점에서, 각 함수의 기울기를 보자.
    Step function은 한 순간만 기울기가 변한다.
    Sigmoid function은 연속적으로 기울기가 변하고 한 순간도 기울기를 0을 갖지 않는다.

- 수치적 미분(Numerical differentiation)과 해석적 미분(Analytic differentiation)의 차이점

- 편미분(Partial derivative)
: 변수가 여럿인 함수에 대한 미분을 편미분이라고 한다.


- 극솟값, 극댓값, 안장점(Saddle point)


- Gradient descent의 설명, 기울기가 양수, 음수, 0, 없는 모든 경우를 봤을 때 점차 최적해를 찾아간다는 설명



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


