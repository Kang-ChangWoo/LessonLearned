# 4. Object Detection
## a. Lessonlearned
- 학습 목표는 아래와 같다.
  - Basics and the difference between localization and detection
  - Various datasets and their descriptions
  - Algorithms used for object localization and detection
  - TensorFlow API for object detection
  - Training new object detection models
  - Pedestrian detection on a moving car with YOLO algorithm

- 동향
  - Object detection application이 많다.
  - CV 안에서 중요하다고 여겨지는 필드
  - Imageclassification tasks, deeper networks가 detection에 성능이 좋다.
  - 현재 완성도가 높고 다양하게 사용된다.

- Localization과 Detection은 다르다.  그 차이는 객체의 수에 있다.  작은 차이지만, Architectures for deep learning model을 짤 때 어떻게 디자인을 해야할 지에 따라 달라진다.
  - Localization detects one object in an image within a label
  - Detection finds all the objects within the image along with the labels

- 데이터셋은 아래를 사용
  - ImageNet dataset: 200 objects 470,000 images, an average of 1.1 objects per image
  - PASCAL VOC challenge: from 2005 to 2012, 20 classes, 11,530 images 27,450 annotations for regions of interest
  - COCO object detection challenge: The Common Objects in Context, 200,000 images, 500,000 object annotations in 80 categories. the average number of object is 7.2 per image
  
- Evaluating datasets using metrics
  - 정확히 object를 사람이 규정하는 게 어렵다.  사람마다 기준이 다르기 때문
  - Intersection over Union(IoU) is used to evaluate the localization task.
  - Mean Precision Average(mAP) is used to evaluate the detection task. 
  
  
- Interscetion over Union
  - 교집합과 합집합 간의 비율을 통해 lebeled 된 것과 predicted 된 것 간의 pixel 차이를 계산한다.
  
- mAP: The mean average precision
  - the product of precision and recall of the detected bounding boxes./  
  - ranges from 0 to 100, The higher the bumer, the better it is.
  - average precision(AP) ?
  
  
- Localization algorithms 
  - The final layer of CNN outputs the probabilistic value, belonging to each of the labels.  This can be extended to localizae the objects.
  
- Localizing objects using sliding windows(what difference between the terms filter and sliding windows?)
  - Sliding window(필터)를 움직여가면서 부분을 잘라서 해석하는 방식
  - 두 가지 문제점 존재
    1. object 사이즈가 window 사이즈 보다 크다면 detection 못한다.  더 큰 window가 필요하다.  이를 막기 위해 scale space 개념을 착안했다.
    2. a lot of extra computation을 야기해서 the system을 slow down 한다.  이를 피하려면 convolutional laters에서 trick을 사용해야 한다.
    
  1. The scale-space concept
    - The scale-space is the concept of using images that are of various sizes.
    - 여러 Window size를 사용하기 때문에 a lot of extra computation를 야기한다. (computational complexity)
    - Speed-up and Accuracy 간의 Trade off 관계다.
    - the idea of the sliding window could be made efficient with a fully convolutional implenetation of sliding windows
    
  2. Training a fully connected layer as a convolution layer
  
- Thinking about localization as a regression problem

  
사진



- 1차원 배열은 벡터(Vector), 2차원 배열은 행렬(Matrix), 벡터와 행렬을 일반화 한것을 텐서(Tensor)라고 한다.  좀 더는 Scalar -> Vector -> Matrix -> 3D Tensor -> 4D Tensor... 단계로 변화한다고 보면 된다.

<p align="center">
 <img src="../resource/image/figure1_what_is_tensor.png"  width="600">
 <h4>What is Tensor</h4>
 <a href="https://rekt77.tistory.com/102">https://rekt77.tistory.com/102</a>
</p>


# 

   

## b. Programming
### b.1 pure Python
#### b.1.1 Concept
- 

#### b.1.2 Command
-   
# 

   

### b.2 Numpy
#### b.2.1 Concept

- 

#### b.2.2 Command
- 

   

# Futher study
1.
# 

   

# Self-made question
1. 
