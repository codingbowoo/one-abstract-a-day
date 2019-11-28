### 2019.11.28 [Making Decisions that Reduce Discriminatory Impact](http://proceedings.mlr.press/v97/kusner19a.html)
on [ICML 2019](https://icml.cc/Conferences/2019/ScheduleMultitrack?event=4860)

> 이 논문에서는 *discriminatory impact problem*에 대한 이야기를 한다. **impact**\*가 현실의 여러 요소 및 결정/판단decision에 어떻게 영향을
받는지를 인과 모델causal model을 통해 설명할 수 있다고 주장하며, 이를 impact에 대한 인과 모델에 대한, 사실과 반대되는 제약조건을 가진 최적화 문제
를 풂으로써 해결할 수 있다고 말한다. 앞으로는 필요 가정을 줄여나감과 동시에 새로운 제약조건의 제시, 최적화 방식에 대한 연구 및 
새로운 인과 모델을 정의하는 방향으로 연구를 진행할 수 있다. 

> *부연설명* // 머신러닝 알고리즘을 실생활에 적용하고자 한다면, 이 알고리즘이 사회적 가치를 거스르지 않는 것이 중요하다. 이것에 대한 연구를 그동안 
'discriminatory prediction problem'이라고 불러 왔다. 즉, *예측 과정에서의 차별을 줄이려면 어떻게 해야 할까?* 에 대한 내용이다. 그러나 이러한 연구들은
실험 조건을 완벽하게 통제할 수 있다는 가정 하에서만 적용할 수 있고, 실제 세상은 그렇지 않다. 그래서 이 연구가 제안하는 것이 *discriminatory impact 
problem*이다. *실생활에서의 여러 판단에 의한 영향**impact**으로부터 나타나는 차별을 줄이려면 어떻게 해야 할까?* 

\* 이 논문에서 정의하는 impact는 자체적으로 치우칠 수 있는 실세계의 이벤트이며, 1) 통제가능한(알고리즘에 따른) 
결정과 2) 통제 불가한 실제 여러 요인(사회적 요인, 사람 의사 결정자)에 종합적으로 영향을 받는다.
