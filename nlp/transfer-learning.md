### 2019.11.18 [Exploring the Limits of Transfer Learning with a Unified Text-to-Text Transformer](https://arxiv.org/abs/1910.10683)
-  Github에서 코드를 찾을 수 있다. https://github.com/google-research/text-to-text-transfer-transformer

> *Transfer learning*은 이미 데이터가 충분한 과제를 통해 pre-train한 모델을 후속 과제(task)에서 fine-tune해서 사용하는 방식을 의미한다. 
이 논문에서는 모든 언어 관련 문제들을 text-to-text 형식으로 변환하는 일정한 프레임워크를 소개하면서 *transfer learning* 기술을 살펴본다.

> 본 논문은(Our systematic study*) 언어 이해 과제(language understanding task)의 여러가지 요소인
pre-train의 목표, 아키텍처, label이 없는 데이터셋, transfer 접근방식 등을 비교한다.
또한 연구의 결과로 새롭게 공개하는 말뭉치인 "Colossal Clean Crawled Corpus"를 통해 요약, 질의응답, 문서 분류 등의 여러 자연어처리 과제에서 
최고의state-of-the-art 성능에 도달할 수 있었다. <br>

\* Systematic studies : 직역하면 계통학습. 국어사전에서는 '교육 지식이나 기술 따위를 계통적 체계에 따라 습득하는 학습 형태.'이라고 소개한다.
