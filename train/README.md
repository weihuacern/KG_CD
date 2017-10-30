# model

## sumary

1. training_levelID-Demo_res18.ipynb: Demo of model details.
2. train_seq_res50: sequence of model training.

## structure

input --> resnet50 --> [2048 -> 49: loss1; 2048 -> 483: loss2; 2048 -> 5270: loss3] --> total loss = loss1 + loss2 + loss3

