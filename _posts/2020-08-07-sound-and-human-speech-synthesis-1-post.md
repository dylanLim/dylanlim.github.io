---
title:  "소리와 사람의 음성 체계 1 - 소리"
excerpt: "소리의 발생과 전달 원리에 대해 학습한다."

categories:
  - Basics

last_modified_at: 2020-08-07T17:35:00-05:00
---

<style> body { font-size: large; line-height: 1.8;} </style>

## 소리

**소리**에 대해 설명하기 앞서 먼저 소리의 전달 원리에 대해 아주 잘 설명되어 있는 아래의 동영상을 시청하도록 하자.

<iframe width="560" height="315" src="https://www.youtube.com/embed/WqnF-VPfGPw" frameborder="0" allowfullscreen></iframe>
<h6 style="text-align: center;">동영상 1. 소리의 전달 원리</h6>
<br/>

위의 영상에서 본 것처럼, 소리는 일반적으로 공기를 매질으로 하여 전달된다. 우리가 목소리를 내어 말할 때를 생각해보자. 이때, 성대와 같은 음원(sound source)으로부터 나오는 압력에 의해 주변의 공기 분자가 **제자리에서 진동(oscillate in place)**하기 시작한다. 진동하는 공기 분자는 인접한 다른 공기 분자들을 진동시키고 또 다시 인접한 다른 공기 분자들을 진동시킨다. 이 과정을 연쇄적으로 반복하여 압력이 고막까지 전달되어 우리는 소리를 듣게 된다.

![fig_1.1](/assets/figures/fig-1-1.jpg){: .align-center}
<h6 style="text-align: center;">그림 1. 소리 전달 과정에서 공기 분자의 움직임</h6>
<br/>

위의 그림은 소리가 전달될 때 압력에 의한 공기 분자의 움직임을 시계열로 표현한 그래프이다. 여기서 x축은 시간축에 해당하고, y축은 공기 분자의 위치를 나타낸다. 여기서 y=0에 해당하는 위치는 공기 분자에 어떠한 압력도 가해지지 않았을 때 공기 분자의 위치(resting position)에 해당한다. 여기서 공기 분자에 가해진 압력의 크기는 공기 분자가 제자리에서 진동하는 폭에 반영될 수 있는데, 이를 **진폭(amplitude)**이라고 한다. 이는 위의 그래프에서 y값의 최대 변위(공기 분자 위치의 최대 변위)이다. 큰 소리는 공기 분자에 가하는 압력이 크고, 이는 진폭에 반영된다. 즉, 큰 소리는 큰 진폭을 갖는 파형을 나타낸다.

공기 분자의 이동 폭으로 표현되는 소리의 **진폭**은 일반적으로 그 범위가 매우 넓기 때문에, 로그 스케일(logarithmic scale)을 통해 표현되는데 이렇게 표현된 소리의 진폭을 **데시벨(dB; decibel)**이라고 한다. 데시벨은 절대적인 값이 아닌 두 소리의 상대적인 값으로 표현된다.

![eq_1.1](https://latex.codecogs.com/svg.latex?decibels=10log_{10}(P1/P2)){: .align-center}

위 식은 데시벨의 일반적인 정의식이며 P1, P2는 두 신호의 전력(Power)을 의미한다. 소리에 대해서는 SPL(Sound Pressure Level; 음압 수준)으로 나타내는데 이는 아래와 같다.

![eq_1.2](https://latex.codecogs.com/svg.latex?SPL(dB)%20=%2020log_{10}{(\frac{P}{P0})}){: .align-center}

여기서 P는 주어진 소리의 절대적인 음압을 측정한 값이고, P0은 사람이 들을 수 있는 최소 음압이다. 만약, P=P0 라면 해당 소리는 0 dB의 소리이며, 우리가 일반적으로 대화하는 소리의 음압은 대략 60dB이다.

## 레퍼런스
[1] Spoken Language Processing - A Guide to Theory, Algorithm, and System Development, 2001-05-05. Huang, Acero & Hon.  
[2] Propagation of sound, Don't Memorise Channel [링크](https://youtu.be/WqnF-VPfGPw)