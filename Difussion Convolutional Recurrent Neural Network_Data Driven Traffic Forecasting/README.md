# Yaguang Li, Rose Yu, Cyrus Shahabi, Yan Liu "DIFFUSION CONVOLUTIONAL RECURRENT NEURAL NETWORK: DATA-DRIVEN TRAFFIC FORECASTING"


### 3/18
🐘Objective : 논문 읽기 적응하자~!

🐘Habit : 매일 공부 시작 전, 논문 30분 보고(최소) pdf 노트에 정리하고 깃허브에 올려놓기

🐘Evaluation: 
* Abstract랑 Introduction만 읽고 정리하는데 시간이 다갔다.. 너무 정갈하게 정리하려해서 그런가?
* 논문 구조에 대한 감이 올듯 안올듯 하다. 시간은 좀 걸리더라도 계속 정리하면서 구조를 파악해야할듯.
* GCN공부랑 마르코프 체인도 복습이 필요하다. 공간적 구조를 표현한 directed graph를 convolution 연산에 어떻게 사용한다는 것인지, diffusion process는 구체적으로 어떤 과정인지 궁금해졌다.

🐘Link : https://github.com/edypidy/SkyElephant-not-a-FlyingElephant


### 3/19
🐘Objective : 논문 읽기 적응하자~!

🐘Habit : 매일 공부 시작 전, 논문 30분 보고(최소) pdf 노트에 정리하고 깃허브에 올려놓기

🐘Evaluation: 
* 조금만 하려했는데 Appendix를 만드느라 시간이 걸렸다..
* 라플라시안 행렬, 확산 과정, 확률 미방, 마르코프 체인 Appendix를 차근차근 만들어야겠다.
* 내용이 재미있어서 할맛이 났다. 근데 구현은 어떡하지?...

🐘Link : https://github.com/edypidy/SkyElephant-not-a-FlyingElephant


### 3/20
🐘Objective : 논문 읽기 적응하자~!

🐘Habit : 매일 공부 시작 전, 논문 30분 보고(최소) pdf 노트에 정리하고 깃허브에 올려놓기

🐘Evaluation: 
* 용어가 생소해서인지 앞뒤 과정의 연결성이 이해가 잘 안갔다. (확산행렬과 재시작 확률을 가진 마르코프 과정이 충분히 많이 반복되면 정상분포 P를 갖는 정상과정으로 수렴하므로 뒤에 모델링한 diffusion convolution layer를 학습시키면 filter파라미터가 학습 되면서 정상분포 P를 구할 수 있기에 시점 무관 예측이 가능해진다는 맥락으로 이해하긴했다.)
* 아무래도 문제의 목적을 잘 이해 못했던 것 같다.(긴 기간을 예측하기 위해 시점 무관 확률과정을 모델링하는데 공간적 구조를 곁들인...)
* 시간 너무 많이 쓴다.. 전공 공부도 하자..
* 
🐘Link : https://github.com/edypidy/SkyElephant-not-a-FlyingElephant


### 3/21
🐘Objective : 논문 읽기 적응하자~!

🐘Habit : 매일 공부 시작 전, 논문 30분 보고(최소) pdf 노트에 정리하고 깃허브에 올려놓기

🐘Evaluation: 
* Network Data Analysis의 Chapter3에서 P의 closed form solution 유도 과정을 발견했다. Methodology_Traffic Forecasting and Appendix2에 Network Data Analysis 부분의 참고를 추가하였다.
* 그래프에서 W_ij를 네트워크 간 거리로 해석했어서 이해하는데 더 힘들었던 것 같다.(연결 강도로 해석하는 것이 맞아보임) Experiment에 나와있었을 줄이야.. 다음부터 이해 안될땐 Experiment 파트로 컨닝해야겠다.
* 논문 하나 읽으려고 다른 논문 몇개를 찾아본건지 모르겠다. 핵심내용이나 관련내용을 따로 정리하는 시트가 있으면 좋을 것 같다. (제목, 저자, 학술지, 년도, 방법론, 메트릭, 핵심내용, 관련내용, 결론, 한계)

🐘Link : https://github.com/edypidy/SkyElephant-not-a-FlyingElephant
