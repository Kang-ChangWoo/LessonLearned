# 2. Perceptron
- 퍼셉트론은 신경망(딥러닝)의 기원이 되는 알고리즘이다.
- 머신러닝의 선형회귀에 대치되는 개념이라고 볼 수 있다.

- 퍼셉트론은 입출력을 갖춘 알고리즘이다.
- 입력을 받아서 특정 조건에 부합하면 1, 0을 출력해준다.
- AND, NAND, OR 세 가지 게이트가 대표적인 조건이다.
- 위의 연산은 직선형 영역만 표현 가능하다는 한계가 있다.

- 따라서, 여러 게이트를 쌓아서 비선형 영역을 표현할 수 있다.
- 다층 퍼셉트론으로 표현할 수 있는 게이트는 XOR 게이트다.
- 이를 위해 0층인 input layer, 1층인 NAND&OR gates, 2층인 AND gate로 구성된다.
- 책에 따라 2층 혹은 3층 퍼셉트론이라고 한다.

- 퍼셉트론 개념을 통해 이론적으로 컴퓨터도 구축할 수 있다. (소자)


# Futher study

1. 각 게이트(OR, AND, NAND)의 결과값을 선형 공간 상에서 표현하기. 가능하다면, XOR 까지!
2. 『The Elements of Computing Systems: Building a Modern Computer from First Principles』 (The MIT Press, 2005) 읽고 소자 및 컴퓨터의 컨셉 이해하기