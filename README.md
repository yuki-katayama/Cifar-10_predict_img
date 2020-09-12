# Cifar-10_predict_img

# Japanese
## 初めに
kerasのデータセットに備わっているCifar10を使用して、モデルを作成する。

cifar10_CNNはcifar10_MLPと比較する為に作成した。
なので、cifar10_cnnは実行しなくても良い

## 工程
0. cifar10_CNNを実行すると学習率がグラフとなる。一応cifar10-cnn-weight.h5モデルが作成される。
(二時間ぐらいかかった..)

1. cifar10_MLPを実行していく
    1. モデル作成
    2. グラフ化
    3. 未知のデータに対して予測を行っている

#English
## Overview
Create a model using Cifar10 included in the keras dataset.

cifar10_CNN was created for comparison with cifar10_MLP.
So you don't need to run cifar10_cnn

## Process
0. When cifar10_CNN is executed, the learning rate becomes a graph. For the time being, a cifar10-cnn-weight.h5 model will be created.
(It took about 2 hours.)

1. Run cifar10_MLP
    1. Modeling
    2. Graph
    3. Predict unknown data
