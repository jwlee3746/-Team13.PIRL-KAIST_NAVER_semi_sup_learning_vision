# Team13-PIRL-KAIST_NAVER_semi_sup_vision
[Team13][PIRL]Final report code of CS492 KAIST_Naver Semi_sup_learning vision task

Max-MixMatch: Approach to Maximize MixMatch for Semi-Supervised Learning

## Usage

### Train
```
nsml run -d fashion_eval -e main.py
```

### The path to our pre-trained model in NSML
```
#nsml: jysung710/nsmlvisdom:0.3
```

## References
```
[1] David Berthelot, Nicholas Carlini, Ian Goodfellow,
Nicolas Papernot, Avital Oliver, and Colin A Raffel.
Mixmatch: A holistic approach to semi-supervised
learning. In Advances in Neural Information Processing
Systems 32. 2019. 1, 2, 3, 5, 6, 7
[2] Kihyuk Sohn, David Berthelot, Chun-Liang Li, Zizhao
Zhang, Nicholas Carlini, Ekin D. Cubuk, Alex Kurakin,
Han Zhang, Colin Raffel. FixMatch: Simplifying
Semi-Supervised Learning with Consistency and
Confidence.
[3] Dong-Hyun Lee. Pseudo-label: The simple and efficient
semi-supervised learning method for deep neural
networks. In ICML Workshop on Challenges in
Representation Learning, 2013. 1, 3, 4, 5, 6
[4] Ekin D. Cubuk, Barret Zoph, Jonathon Shlens, and Quoc
V. Le. Randaugment: Practical automated data
augmentation with a reduced search space. arXiv preprint
arXiv:1909.13719, 2019. 1, 3, 6, 7, 12, 13, 14
```
