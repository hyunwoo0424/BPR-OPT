# BPR-OPT

2009년에 나온 Bayesian Optimization 기반에 랭킹 최적화 논문을 바탕으로 모델을 구현했습니다. (https://arxiv.org/abs/1205.2618)
데이터셋은 Rossman , Netflix 데이터셋을 사용하며 Evaluate Method는 Leave one out을 사용했습니다.
AUC로 성능을 평가하며 grid research로 하이퍼 파라미터를 탐색했습니다.