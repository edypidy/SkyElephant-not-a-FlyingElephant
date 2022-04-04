# Basic Math

### Subjects
1. Linear Algebra
2. Analysis
3. Mathmatics for Statistics


### 3/31
🐘Objective : 선형대수학, 해석학, 수리통계학 모조리 복습(+ 꾸준함)

🐘Habit : 매일 공부 시작 전, 논문 30분 보고(최소) pdf 노트에 정리하고 깃허브에 올려놓고 나서 책의 한 thm, def, lemma 보고 노트에 정리해서 깃허브에 올리기

🐘Evaluation:
* Monotone Set & Set Function 올려둠. Set Function은 finitely additive 할때 좋은 성질을 갖는듯(더 파면 너무 깊게 갈것 같아서 끊었다. 직관적 이해를 해보자.)


### 4/1
🐘Objective : 선형대수학, 해석학, 수리통계학 모조리 복습(+ 꾸준함)

🐘Habit : 매일 공부 시작 전, 논문 30분 보고(최소) pdf 노트에 정리하고 깃허브에 올려놓고 나서 책의 한 thm, def, lemma 보고 노트에 정리해서 깃허브에 올리기

🐘Evaluation:
* Sigmoid가 확률로 해석되는 것에 딴지를 걸고 싶어서 정리함. 현실에서 만족하기 힘들어보일 가정이라도 찾고 싶었지만 결론은 잘 학습된 모델에서 별다른 가정없이 통계 이론적으로 의미를 가지며 확률로 해석될 수 있다는 것...(feat. 조건부 확률과 베이즈 정리, 로그 오즈등)
* 딱 한가지 걸리는게 있다면 MLE로 학습된 모델에 한해 확률로 해석할 수 있다고 결론낸 것이었는데(MLE는 결국 확률을 최대화 하는 방식이니 출력과 학습 사이 괴리가 없다)..
* 즉, Lossfunction의 확률적 의미를 갖지 않는 변수에 시그모이드 출력값이 들어가고 피드백 된다면 확률로 해석할 수 없겠다(이거 하나 발견함)
* 결론 => iid가정만으로 시그모이드는 확률로 해석해도 되는데 Lossfunction의 변수가 확률적 의미를 갖지 않는 경우만 주의하자!


### 4/4
🐘Objective : 선형대수학, 해석학, 수리통계학 모조리 복습(+ 꾸준함)

🐘Habit : 매일 공부 시작 전, 논문 30분 보고(최소) pdf 노트에 정리하고 깃허브에 올려놓고 나서 책의 한 thm, def, lemma 보고 노트에 정리해서 깃허브에 올리기

🐘Evaluation:
* Probability Set Function의 정의에 대해 정리. 당연하게 여기던 P 함수가 다소 멀게 느껴지는 정의였다. 평소에 P함수나 확률에 대해 생각해볼 때 Sample Space를 그저 함수의 Domain이겠지 막연히 생각했는데 잘못된 생각이었다. 엄밀히 생각해보면 Sample Space의 Power Set이 Domain인데 말이다. 단순히 수학적 논의를 위한 엄밀함인지 실제 여러 현상들에 반영 되기까지 하는 엄밀함인진 모르겠으나 일단은 놓치고 있던 가닥을 하나 잡았다.
