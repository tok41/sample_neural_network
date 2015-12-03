# Example : MNIST Classification (with TensorFlow)

## 1, 概要

* MNISTの手書き文字認識をする
  * 0~9までの10個のカテゴリを認識する
  * TensorFlowを使うので、インストール必須(下記必要要件に注意)


## 2, 必要要件

* ipython 3.1+
 * 今回はipythonで作業します
* TensorFlow 0.5.0+
 * http://www.tensorflow.org/get_started/os_setup.html#ubuntu-linux-64-bit
 * 公式ドキュメントを読んで確認まで済ませておくこと
* Cuda Toolkit 7.0
 * 上位互換は無いので注意
 * GPU無しの環境に導入する場合には不要かも(試してない)


## 3, 構成

```
- README.md : このファイル
- MNIST_data/ : MNISTのデータが入る
- mnist_beginner.ipynb : 手書き文字学習プログラム。超単純なモデル。ipython使用
- mnist_experts.ipynb : 畳込みニューラルネット(CNN)を使って手書き文字認識。ipython使用
- input_data.py : MNISTのデータを取得するためのクラスファイル
```


## 4, 実行手順

* ipythonを利用するので、iPythonを立ち上げておく

### 4-1 単純なモデル(For ML Beginner)

* mnist_beginner.ipynbを開く
* 上から実行していく

### 4-2 CNN(Deep MNIST for Experts)

* mnist_experts.ipynbを開く
* 上から実行していく
 * CUDA環境利用を前提に作ってます


