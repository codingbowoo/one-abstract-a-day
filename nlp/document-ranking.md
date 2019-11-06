### 2019.11.06 [Multi-Stage Document Ranking with BERT](https://arxiv.org/pdf/1910.14424.pdf) <br>

> BERT와 같은 pre-trained 모델을 사용함에 따라 자연어처리 응용분야가 발전했고 document ranking도 그 중 하나이다. 
이 논문에서는 document ranking문제를 pointwise 분류로 보는 **monoBERT**와 pairwise 분류로 보는 **duoBERT**, 두 가지를 제안한다. 
두 모델을 통해 end-to-end 검색 시스템 수행 시 *quality와 latency의 tradeoff의 적당한 균형점*을 찾을 수 있다.
(어떻게: 파이프라인 단계에서 후보가 되는 선택지를 조절함으로써) 
마지막으로 각 컴포넌트가 미치는 영향을 확인하기 위해 Ablation studies* 방식을 사용했음을 밝히고 있다. <br>

> document ranking 문제는 large corpus를 고려해야 하기 때문에, working set을 줄일 필요가 있다.
그렇다면 cosine similarity 등을 이용해 document간의 non-linear한 상관관계를 학습할 수 있는 representational learning, 
그리고 nearest-neighbor search 문제로 근사하고 싶어지는게 인지상정 (?) <br>
그러나 이런 모델은 exploratory하고, 성능이 나오지 않는다면 어차피 여러 단계를 포함해야 한다. (working set reduction을 포함하는 듯 하다)
이 논문이 차용하는 Multi-stage ranking 아키텍처는 그와 비교해 실용적이다. <br>
이 모델은 앞으로 1) end-to-end 성능을 위한 파라미터를 자동 튜닝 하는 등의 파이프라인 통합 2) scoring signal의 활용 3) 길이가 긴 문서에의 적용
등의 방향으로 발전할 수 있다.

\* Ablation studies : Ablation은 제거, 절제를 의미한다. 모델이나 알고리즘이 여러 특징을 가질 때, 각 특징이 성능에 미치는 영향을 알아보기 위해 해당 특징을 지워보는 연구 방식이다.
