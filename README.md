# Sparse-BERT

Histone modification은 DNA가 히스톤 단백질에 감싸여 있는 구조인 chromatin에서 일어나는 화학적 변화로, 유전자 발현 조절, 염색질 구조 형성, 세포 분화 및 발달 과정에서 중요한 역할을 한다.
Histone modification peak는 유전체 상의 특정 위치에서 이러한 Histone 수정이 집중적으로 발생하는 지점을 의미한다. 이는 Epigenetic marker로 사용되어, 다양한 생물학적 상태나 질병 상태를 예측하거나 진단하는 데 활용될 있다. 또한 암세포에서 비정상적인 Histone 수정 패턴은 암 진단 및 치료 타겟 발굴에 중요한 역할을 할 수 있다.

이번 연구는 Histone peak 데이터에서 masking된 영역을 복원하는 것으로 Cell type specific하게 Histone modification을 추론하는 것이 최종 목표이다.
Cell type에 따른 Histone의 분석을 위하여 Mixture-of-Expert구조와 BERT 아키텍쳐를 합하였다.

데이터 특성에 따른 BERT를 선택하여 보다 효과적이고 효율적으로 추론하는 추론 모델을 제안한다.
