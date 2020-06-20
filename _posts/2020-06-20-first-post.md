---
title: "1. 인공지능을 위한 선형 대수"
date: 2020-06-20 21:02:00 -0400
categories: jekyll update
---
[Math]

[https://www.edwith.org/linearalgebra4ai/joinLectures/14072] 인공지능을 위한 선형대수 학습 정리입니다.

선형대수 기초

![intro](https://user-images.githubusercontent.com/60867950/85201923-ebe12800-b33d-11ea-95c4-e04da21fbf1c.PNG)

Scalar : 단일 숫자를 의미함

Vector : 순서가 정해진 숫자들

Matrix : 이차원 배열의 숫자(세로는 행, 가로는 열 의미)

![캡처2](https://user-images.githubusercontent.com/60867950/85202081-e6d0a880-b33e-11ea-9189-dfd88c061f02.PNG)

column vector, row vector의 표현 방법

![캡처3](https://user-images.githubusercontent.com/60867950/85202098-ff40c300-b33e-11ea-91c4-1c648c11cc6f.PNG)

Square matrix : row와 column이 같은 벡터, 나머지는 Rectangular vector

Transpose of matrix : 직사각형 벡터를 대각선을 이용해 회전시킨 벡터

![캡처4](https://user-images.githubusercontent.com/60867950/85202130-36af6f80-b33f-11ea-9c03-031e8cc79567.PNG)

Vector/Matrix 를 더할때 크기가 같아야 함(same size)
두 matrix을 곱할시 (n x m)(m x d) = (n x d) matrix로 표현.

![캡처5](https://user-images.githubusercontent.com/60867950/85202165-6c545880-b33f-11ea-97d6-420f53b2ccf8.PNG)

두 matrix를 곱할때 교환법칙이 성립하지 않는다! AB != BA
