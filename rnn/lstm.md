### 2019.11.25 Time series forecasting of petroleum production using deep LSTM recurrent networks
keywords: Time series forecasting, Deep neural networks,
Recurrent neural networks,
Long-short term memory,
Petroleum production forecasting

> 과거 데이터를 가지고 미래를 예측하는 시계열 예측Time series forecasting 과제에 해당: 
과거의 예측 기법(통계 or soft computing) 은 1) 시간이 오래 걸리고 2) 방법이 복잡하다.

> 미래의 예측하고자 하는 값과 과거 데이터 간의 관계를 규명하기 위해 본 논문에서는 1) **deep long-short term memory DLSTM**을 
사용하며, 2) 최적의 아키텍처를 찾기 위해 **genetic algorithm**을 사용한다. 


### 2019.11.27 [Unsupervised Learning of Video Representations using LSTMs](https://arxiv.org/abs/1502.04681)

> 이 연구에서는 영상 시퀀스의 표현representation을 찾기 위해 여러 층의 LSTM을 사용한다. *encoder LSTM*이 입력 시퀀스를 고정 길이의 표현representation로 변환한다. 이 representation을 목적에 따라 하나 또는 여러 개의 LSTM을 사용하여 *decode*한다. decode의 목적은 1) 입력 시퀀스의 재구현reconstruct 2) 미래 시퀀스의 예측이다. 

> 입력 시퀀스는 1) 줄줄이 나열한 이미지 픽셀 2) pretrained ConvNet을 사용해 추출한 high-level representation이다. 모델의 성능은 질적으로 얼마나 우수하게 모델이 학습한 영상 representation을 바탕으로 미래 혹은 과거를 추론하는지에 대한 것이다. 모델에 일부러 악조건(길이가 긴 경우/도메인 밖의 데이터)을 주고 시험하기도 했다. *실제 데이터셋을 대상으로 한 실험*에서는 지도학습 문제를 위해 fine-tuning 했고, UCF-101 및 HMDB-51 데이터셋에 대해 human action recognition 을 수행했다. 이 모델을 사용할 때 분류과제 성능이 높아졌고, 관련이 없는 데이터셋으로 pretrain한 모델조차도 action recognition 성능을 높임을 확인했다. 

### 2019.12.21 [Using LSTMs for climate change assessment studies on droughts and floods](https://arxiv.org/abs/1911.03941)

> large datasets에 대한 학습을 진행하는 a large-scale LSTM-based modeling approach를 제안한다. 홍수와 가뭄을 예측한다. 

> 약간 수정한 input gate구조를 가지는 LSTM(Entity-Aware Long Short-Term Memory Network(EA-LSTM))네트워크를 사용한다. train 할 때는 여러 하천으로부터의 기상 정보를 사용했고, 특정 장소에 대한 모델의 조건을 적을 때는 집수의 성격을 고정하여 사용했다. 

### 2019.12.31 [A LSTM-based method for stock returns prediction: A case study of China stock market](https://ieeexplore.ieee.org/abstract/document/7364089)

> 주식 시장 예측에 관한 연구는 꾸준히 이어져 왔고, 뉴럴넷, 유전 알고리즘, 서포트 벡터 머신 등의 다양한 기계학습 알고리즘이 적용되어 왔다. 
주가는 (특히 시간) 순서가 있는 데이터에 해당하기 때문에 다양한 RNN 모델을 사용한 연구가 있어 왔다. 이러한 RNN 아키텍처 중 가장 성능이 좋은 것이 LSTM이다. LSTM은 메모리 셀을 통해 예전의 데이터와 지금의 입력값 간의 연결고리를 찾기 용이하다. 

> 이 논문은 중국 주식 시장에 LSTM 아키텍처를 적용함으로써 예측의 성능을 높인다. 10개의 learning feature와 3일의 'earning rate'를 라벨링한다는 것에 대해 집중해서 본문을 읽어야겠다. 
