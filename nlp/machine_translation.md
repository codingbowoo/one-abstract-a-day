### 2019.11.15 [Neural Machine Translation with Byte-Level Subwords](https://arxiv.org/pdf/1909.03341.pdf)

> 현존하는 거의 모든 기계번역 모델들은 글자(character) 단위의 vocabulary를 사용한다. 그러나 일본어나 중국어처럼, 글자 수가 많은(한자를 사용하기 때문으로 추정)
언어나 자주 사용되지 않는 글자를 포함할 경우 vocabulary가 불필요하게 커지고, 모델의 간결함을 해치게 된다. 
이런 문제를 해결하기 위해, 바이트 수준의 텍스트 표현(representation)과 vocabulary로 256 byte set을 사용하고자 한다.

>  이 논문에서는 1) character vocabulary보다 간결하고 2) Out-Of-Vocabulary 토큰이 없는 Byte-level BPE*를 제안한다.
이 BBPE는 기존 BPE와 비교해 1/8크기인데다가, 여러 언어에 대해 공동의 vocabulary의 사용성을 높일 수 있다. 
또한 서로 문자 집합이 서로 겹치지 않는 언어들의 경우 언어 간의 model transfer가 가능하다.

\* BPE: Byte Pair Encoding 알고리즘. 어떤 데이터가 있을 때 해당 데이터에 나오지 않는 문자로 일정 연속하는 byte열을 대체하는 것. subword segmentation에 사용한다. [Sennrich et al.](https://www.aclweb.org/anthology/P16-1162/)
