---
title: "3. 인공지능을 위한 선형 대수"
date: 2020-06-20 21:02:00 -0400
categories: Math
---
[Math]

[https://www.edwith.org/linearalgebra4ai/joinLectures/14072] 

인공지능을 위한 선형대수 학습 정리입니다.

**선형 결합**

![3-1](https://user-images.githubusercontent.com/60867950/85204224-fc999a00-b34d-11ea-97c8-a012a558d29a.PNG)

선형 결합 : 많은 벡터들에 스칼라 값을 곱해주는 것

![3-2](https://user-images.githubusercontent.com/60867950/85204246-2783ee00-b34e-11ea-87f5-ecebfa69296d.PNG)
![3-3](https://user-images.githubusercontent.com/60867950/85204247-28b51b00-b34e-11ea-99eb-e74ed7ab5e06.PNG)
![3-4](https://user-images.githubusercontent.com/60867950/85204249-294db180-b34e-11ea-86cb-2c93007ac501.PNG)

**Span : 유한한 벡터를 이용하여 만든 선형결합(부분 집합 : 얇은 평면)**

연립 방정식 해를 판단하는 것 : span으로 판단 

![3-5](https://user-images.githubusercontent.com/60867950/85204251-2a7ede80-b34e-11ea-9a50-b3186db30184.PNG)
![3-6](https://user-images.githubusercontent.com/60867950/85204252-2b177500-b34e-11ea-9db4-62505ed1c4ed.PNG)
![3-7](https://user-images.githubusercontent.com/60867950/85204253-2bb00b80-b34e-11ea-8c4b-99442bd7a598.PNG)

행렬의 곱셈 : linear combination으로 표현 가능

Row 벡터의 combination

Sum of rank-1 Outer products (외적) -> 워드 임베딩에 많이 사용
(covariance matrix in Gaussian, gram matrix in style transfer)


