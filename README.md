# AI 기초 노트

유튜브 영상으로 짠 AI 커리큘럼을 차수별로 정리한 인터랙티브 공부 노트입니다. 각 차수는 원문 영상의 순서와 예시 숫자를 따르고, 영상에 없는 설명·그림은 (보충)으로 표시합니다.

## 파일

| 파일 | 내용 |
|---|---|
| `ai.html` | 첫 페이지. 차수 목록 |
| `ai-stage1.html` | 1차. 선형회귀와 경사하강법 (개요, 1~4장, 용어·기호) |
| `ai-stage2.html` | 2차. 역전파와 신경망 (개요, 1~4장, 용어·기호) |
| `ai-stage3.html` ~ `ai-stage6.html` | 준비 중 |

모든 페이지 위쪽의 차수 메뉴로 다른 차수와 미적분 노트로 이동할 수 있습니다. 각 페이지는 한 파일 안에 CSS와 JS가 모두 들어 있습니다.

## 보는 법

- 그림 아래 ▶를 누르면 자막과 식이 바뀌며 장면별로 재생됩니다.
- ⏮ ⏭나 장면 점을 누르면 원하는 장면에서 멈춰 볼 수 있습니다.
- 색 뜻(1차): 파랑 = 측정한 데이터, 보라 = 모델(직선)과 예측값, 빨강 = 잔차·오차·손실, 초록 = 손실 곡선의 기울기, 주황 = 한 번에 움직이는 걸음(Step Size).
- 색 뜻(2차): 파랑 = 순전파 값, 초록 = 그래디언트, 주황 = 국소 그래디언트, 보라 = 가중치·바이어스, 빨강 = 손실.
- 글꼴: 본문 Pretendard, 수식 STIX Two Text.

## 미분

미분은 다시 설명하지 않고 [미적분학의 본질 노트](https://juhong-park0823.github.io/The-Essence-of-Calculus/calculus.html)의 해당 장으로 연결합니다.

## 2차 원문 영상

- [Lecture 4 | Introduction to Neural Networks](https://www.youtube.com/watch?v=d14TUNcbn1k) — Stanford CS231n (2017)
- [What is a Neuron?](https://www.youtube.com/watch?v=LHOLedaY2so) — Architecture Bytes - AI
- [Why Do We Need Activation Functions in Neural Networks?](https://www.youtube.com/watch?v=DaixewJTF8k) — NeuralNine
- 3Blue1Brown 한국어 DL1~4 (4장에서 링크)
- 3Blue1Brown 미적분학의 본질 4편 (미적분 노트로 대신)

## 1차 원문 영상

- [Linear Regression in 3 Minutes](https://youtu.be/3dhcmeOTZ_Q) — 3-Minute Data Science
- [38 Mean Squared Error](https://www.youtube.com/watch?v=RQqGEjeYnxc) — cantus
- 3Blue1Brown 미적분학의 본질 1~3편 (미적분 노트로 대신)
- [Gradient Descent, Step-by-Step](https://youtu.be/sDv4f4s2SB8) — StatQuest with Josh Starmer
