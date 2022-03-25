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


### 3/22
🐘Objective : 논문 읽기 적응하자~!

🐘Habit : 매일 공부 시작 전, 논문 30분 보고(최소) pdf 노트에 정리하고 깃허브에 올려놓기

🐘Evaluation: 
* 오늘의 파트인 Relation with Spectral Graph Convolution은 쌩뚱맞은 내용이 나와서 뭐 이런 순서로 배치를 하나 싶었지만 고졸의 짧은 가방끈이었다. 내가 이해하기론 이 파트는 선행 연구와의 관계를 설명하면서 연구가 서있는 자리를 더 자세히 말하는 파트이다. Abstract에서 다른 중요성에 밀려 차마 밝히지 못한 선행 연구와 수리적 연결성을 Appendix까지 보여주며 알려주는 것.(친절한 저자에 화난 내용이라 그런지 Appendix가 껴버렸나보다.)
* 내용 때문에 본의 아니게 직교행렬부터 similarity, 대각화, 스펙트럼 분해, 유니타리 행렬까지 복습돼버렸다.. 따로 정리해서 올려놓는 것도 좋을 것 같다.

🐘Link : https://github.com/edypidy/SkyElephant-not-a-FlyingElephant


### 3/23
🐘Objective : 논문 읽기 적응하자~!

🐘Habit : 매일 공부 시작 전, 논문 30분 보고(최소) pdf 노트에 정리하고 깃허브에 올려놓기

🐘Evaluation: 
* 처음으로 읽는대로 이해가 간 파트. 이미 seq2seq 논문을 한번 공부한 상태여서인지 이해에 무리가 가진 않았다.
* 사실 seq2seq 논문에서도 Model Training 시 매 time step마다 예측값이 들어가는 것이 아닌 ground truth observation이 들어간다는 부분이 train_test의 task불일치, 성능저하를 야기한다고 생각해서 왜 그렇게 했는지 이해가 안 갔었는데 Scheduled Sampling(Bengio et al., 2015)를 읽고 그 부분이 seq2seq의 한계였다는 것을 알았다..
* Scheduled Sampling에서 소개된 flip training이 진짜 신박했다. 역시 뭐든지 적당한 랜덤화로 이끌고 가야 하나보다.. 기존 모델에서 어떤 것을 랜덤화 시켜서 개선시킬지 보는 것도 재미있을듯 

🐘Link : https://github.com/edypidy/SkyElephant-not-a-FlyingElephant


### 3/25
🐘Objective : 논문 읽기 적응하자~!

🐘Habit : 매일 공부 시작 전, 논문 30분 보고(최소) pdf 노트에 정리하고 깃허브에 올려놓기

🐘Evaluation: 
* 어제까지만 해도 Related Work를 읽어봐도 이걸 왜 써놨을까 싶었는데(이미 Relation with Spectral Convolution 부분이나 Methodology에서 많이 언급된 부분들 아닌가?..했다) 오늘 와선 연구의 족보?를 말한다는 느낌으로 봤다. 이 연구가 나오기까지 과거에 어떤 연구들이 있었고 어떤 한계들이 있어서 무엇을 개선했는지 더욱 명확히 말하고있다.
* Experiment는 연구의 꽃이긴 하지만 이미 Methodology, Related Work등을 보면서 어떤 실험들이 나올지 보이긴 했다. Spatial & Temporal을 각각 모델링한 것이 기존의 것 또는 하지 않은 것과 얼마나 성능 차이를 보이는지를 두고 실험을 할테니.. 그래도 잠깐 실험 표를 보니 이러한 실험들의 컨벤션을 파악하기 위해서 잘 봐야겠다는 생각이 들었다..(솔직히 그냥 읽기만 하고 지나가고 싶다.)
* 
🐘Link : https://github.com/edypidy/SkyElephant-not-a-FlyingElephant
