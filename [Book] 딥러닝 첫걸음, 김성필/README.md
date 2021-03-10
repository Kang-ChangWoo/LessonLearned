# 0. 서두 
- MATLAB 코드로 구성된다. (github.com/philbooks/Deep-Learning-for-Beginners)

# 1. Machine learning: 기계학습, 머신러닝
s

# 2. Neural network: 신경망


# 3. 다층 신경망의 학습


# 4. 신경망과 분류


# 5. Deep learning: 딥러닝


# 6. Convolutional neural network: 합성곱 신경망, 컨볼루션 신경망




## 3.2 Programming, hadling Multi-dimensional numpy array
- Numpy에서, np.ndim()을 통해 배열의 차원 수 확인 가능하다.
- Numpy에서, Pandas의 DataFrame과 마찬가지로 Array.shape으로 배열의 형상을 알 수 있다.
- Numpy에서, argmin()은 array 중에서 제일 높은 값의 인덱스를 반환한다.

# Futher study
1. 왜 Sigmoid가 많이 사용되고 중요한지?
2. 편향뉴런은 왜 매번 있는건지..? 통상 선형회귀식의 잔차라고 생각해도 좋은지?
3. 지수함수에 대해 명확히 훈련할 것
4. 시그모이드는 -5, 5까지, Step function도 -5,5 까지, ReLU는 특정 값을 기점으로 이하를 생략한다.  그렇다면 신경망 내부 노드의 가중치의 합은 정규화되어야 하나?
5. 소프트맥스 함수는 단조 증가 함수다.  그래서 대소관계가 그대로기 때문에 어차피 가장 높은 뉴런을 클래스로 인식하기 때문에 생략해도 된다고 한다.  그렇다면 왜 분류에서는 소프트맥스를 사용하는 것인지..?  아예 안써도 좋은것 아닌가
6. Prooagation 뚯이? 전파?
7. dataset_dir = os.getcwd().replace('\\', '/') 
8. np.frombuffer ==> raw data에서 array 값을 얻고 싶을 떄 쓰는 함수


# Self-made Question
1. 1층의 첫번째 뉴런으로 가는 과정을, (1)식 -> (2)행렬식 -> (3) 예시를 들어 설명하라. (85page)

