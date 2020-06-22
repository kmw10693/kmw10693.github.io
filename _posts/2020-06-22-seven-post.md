---
title: "인공지능을 위한 선형 대수(7)"
date: 2020-06-22 18:47:00 -0400
categories: Math
---
[Math]

[https://www.edwith.org/linearalgebra4ai/joinLectures/14072] 

인공지능을 위한 선형대수 학습 정리입니다.

**Least Squares Problem 소개**



![62](https://user-images.githubusercontent.com/60867950/85273777-04c21880-b4b9-11ea-9823-bd848b042fd6.PNG)

Overdetermined System : 해가 유한하고 방정식이 무수히 많은 경우이다. 해가 없을 수 있다.

Equations >> variables 

위 사진에서는 벡터가 3개인데, dimension이 100일 경우, 주어진 벡터 b가 공간에 들어갈 확률 낮아진다.

전체공간이 넓어지므로 b가 span안에 들어가기 힘든 문제점!

![63](https://user-images.githubusercontent.com/60867950/85274082-6da99080-b4b9-11ea-9fda-78be926bca1d.PNG)

해가 없을 경우 -> least squares problem을 이용 (근사적인 solution)

![64](https://user-images.githubusercontent.com/60867950/85274132-81ed8d80-b4b9-11ea-8bf6-2a650563a457.PNG)
![65](https://user-images.githubusercontent.com/60867950/85274184-92056d00-b4b9-11ea-9d54-5bde69c6c64e.PNG)

Inner product(내적)

두 개의 벡터가 같은 공간에 있을 때, element 끼리 곱셈하고 덧셈함.

1.	첫 번째 벡터를 transpose하고 오른쪽 벡터를 곱함.
2.	선형 결합을 먼저하고 내적 하거나, 나중에 선형 결합하거나 똑같음.

![66](https://user-images.githubusercontent.com/60867950/85274210-992c7b00-b4b9-11ea-8466-c757f6268777.PNG)

Vector norm (벡터 길이)

1.	자기 자신의 벡터의 내적으로 표현 가능

2.	벡터의 상수 배로 나타낼 수 있음.


![67](https://user-images.githubusercontent.com/60867950/85274299-b82b0d00-b4b9-11ea-9cfd-60f1ef07b57e.PNG)

Unit Vector(단위 벡터)

1.	어떤 벡터의 길이를 1로 만드는 normalization

2.	Unit vector라고 부른다. (original vector 에다가 자기 자신의 크기로 나눔)

![68](https://user-images.githubusercontent.com/60867950/85274342-c6792900-b4b9-11ea-815f-37f495dc894a.PNG)

Inner product and Angle between vectors

![69](https://user-images.githubusercontent.com/60867950/85274349-c7aa5600-b4b9-11ea-9ed4-949c852b1b67.PNG)

Orthogonal Vectors (직교 벡터)

1.	두 개의 벡터 내적은 0

![70](https://user-images.githubusercontent.com/60867950/85274353-c8db8300-b4b9-11ea-9e9e-a83e130fbbe0.PNG)
![72](https://user-images.githubusercontent.com/60867950/85274441-e6a8e800-b4b9-11ea-9784-f763000a1aa1.PNG)
![71](https://user-images.githubusercontent.com/60867950/85274443-e7da1500-b4b9-11ea-932f-6dc1595acf38.PNG)

Back to over-determined system

에러가 4가지인 경우 
에러 합산 : total error를 계산하는 것 : sum of squared errors

Least squares problem : b- Ax를 minimize를 어떻게 하는 가?

