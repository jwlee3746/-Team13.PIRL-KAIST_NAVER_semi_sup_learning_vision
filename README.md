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
@article{berthelot2019mixmatch,
  title={MixMatch: A Holistic Approach to Semi-Supervised Learning},
  author={Berthelot, David and Carlini, Nicholas and Goodfellow, Ian and Papernot, Nicolas and Oliver, Avital and Raffel, Colin},
  journal={arXiv preprint arXiv:1905.02249},
  year={2019}
}
