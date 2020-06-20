---
title: "인공지능을 위한 선형 대수(2)"
date: 2020-06-20 22:15:00 -0400
categories: Math
---
[Math]

[https://www.edwith.org/linearalgebra4ai/joinLectures/14072] 

인공지능을 위한 선형대수 학습 정리입니다.

**선형 방정식과 선형 시스템**

![2-1](https://user-images.githubusercontent.com/60867950/85202754-b2132000-b343-11ea-9c61-ce364c2413ad.PNG)

선형 방정식 : 가중치의 계수들과 결과인 B로 나타내는 방정식을 의미한다.

![2-2](https://user-images.githubusercontent.com/60867950/85202786-dbcc4700-b343-11ea-8bc2-2d1da5b27497.PNG)

선형방정식 혹은 선형 시스템은 선형 방정식의 모음이다.

![2-3](https://user-images.githubusercontent.com/60867950/85202814-06b69b00-b344-11ea-9c7b-eeacdfc3e312.PNG)

![2-4](https://user-images.githubusercontent.com/60867950/85202846-47aeaf80-b344-11ea-988c-95272422a60d.PNG)

선형 시스템의 예시 : Weight, height, is_smoking에 변수에 따른 Life span의 결과를 나타내는 식이다. (Regression 식, 가중치는 x로 표현)

그림과 같이 3개의 선형 방정식으로 표현 가능하다!

![2-5](https://user-images.githubusercontent.com/60867950/85202861-7593f400-b344-11ea-8f42-c9580470df8f.PNG)

![2-6](https://user-images.githubusercontent.com/60867950/85202880-b4c24500-b344-11ea-925c-2e5b693a6243.PNG)

![2-7](https://user-images.githubusercontent.com/60867950/85202896-c0ae0700-b344-11ea-8f9f-0040671b4dd6.PNG)

![2-8](https://user-images.githubusercontent.com/60867950/85202901-c7d51500-b344-11ea-85f3-40052e8cd77d.PNG)

Matrix을 풀기 위한 역행렬

항등 행렬 : 어떤 벡터를 곱해도 자기 자신의 벡터의 결과가 나온다.
(단 역행렬은 정사각행렬에만 가능, 역행렬 x 행렬 = 항등행렬)

역행렬이 존재하지 않는 경우 : 해가 무수히 많거나 해가 없다. (비율이 똑같을 때)

정사각 행렬이 아닌 경우 : m<n -> infinitely many solutions (무수히 많은 해)
(-> 머신러닝에서는 Regularization을 도입해서 가중치를 설정한다. )

m>n -> no solution exists (해가 없다!)






