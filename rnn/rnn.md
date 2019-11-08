### 2019.11.08 [Learning Long-Term Dependencies with Gradient Descent is Difficult](http://ai.dinfo.unifi.it/paolo//ps/tnn-94-gradient.pdf) <br>

> RNN은 입력 시퀀스와 출력 시퀀스를 연결하는데 쓰이는데, 
이 RNN을 학습시킬 때 입출력 시퀀스 간의 간격이 멀어지면 temporal contingencies
(시간에 따른 문제?) 문제가 발생한다. Gradient를 기반으로 하는 학습 방식을 사용할 때 이러한 문제가 생긴다. 
따라서 우리는 gradient descent를 통한 효율적인 학습과,
긴 간격이 있을 때 정보를 오래 보관(latching on information for long periods 라는 표현을 쓴다.)하는 것 사이의 tradeoff를 고려해야 한다.
