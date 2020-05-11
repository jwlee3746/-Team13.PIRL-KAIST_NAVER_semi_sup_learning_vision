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
kaist_13/fashion_eval/371

Checkpoint        Last Modified    Elapsed    Summary                                                                                           Size
----------------  ---------------  ---------  ------------------------------------------------------------------------------------------------  --------
efficientb2_e49   2 days ago       0.259      train/loss/acc=69.04549319727889, train/loss/avg=3.925367023773536, step=49, number_of_files=1    34.44 MB
efficientb2_e99   2 days ago       2241.378   train/loss/acc=71.34566326530614, train/loss/avg=5.89149148414235, step=99, number_of_files=1     34.44 MB
efficientb2_e149  a day ago        7839.958   train/loss/acc=71.96570294784578, train/loss/avg=8.146901028955767, step=149, number_of_files=1   34.44 MB
efficientb2_best  a day ago        1121.407   train/loss/acc=72.26332199546485, train/loss/avg=10.321768882745754, step=188, number_of_files=1  34.44 MB
efficientb2_e199  a day ago        6161.602   train/loss/acc=72.06490929705217, train/loss/avg=10.902730095172357, step=199, number_of_files=1  34.44 MB

```

## Code Completed Part
```
ImageDataLoader.py : class TransformFix / class TransformMore

main.py : SemiLoss(object) / train(opts, train_loader, ...)

efficientnet_pytorch
```
