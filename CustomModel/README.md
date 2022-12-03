# [Reference Model & Code]
* Yury Gorishniy, Ivan Rubachev, Valentin Khrulkov, Artem Babenko "Revisiting Deep Learning Models for Tabular Data". NIPS2021.
* https://arxiv.org/abs/2106.11959v2
* https://github.com/lucidrains/tab-transformer-pytorch#readme

<img src="./Bicon_FT_Transformer1.png" width="1000px"></img>

Visualize Attention Score to explain how binary condition(bicon) contribute to each tabular feature

<img src="./Bicon_FT_Transformer2.png" width="1000px"></img>

# ToDo
1. Separation of Main Effects from Co-Effects in Binary Conditions
2. => Main Tokens & Interaction Tokens
3. Interaction Tokens => 2^n => Too Many!! => 2~3 Interaction => n^2 ~ n^3 vs 2^n


### 생각 초안..
+ Idea
Image Class activation Map을 임베딩한 Token과 Tabular Token의 유사도를 Attention Score로 쓸 수는 없을까?
=> Tabular 데이터가 주어졌을 때, 모델이 한 Feature로부터 이미지의 어떤 부분에 가중치를 주었는지 역추적하여 확인할 수 있을 것.
