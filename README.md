# Deep Learning SAMPLE

* DeepLearningのサンプルコード集です
* 参考にしたサイトのリンクを貼っているので、そちらを見た方が良いかも

## 必要環境

* Python 2.7
 * 3系は動作未確認
* Anaconda 2.2+
 * NumPy, Six, Pandasがあればいいけど
* NVIDIA CUDA Technology GPU and drivers
 * あればbetter. 強くお勧め.

## SAMPLE1 : MNIST手書き文字認識 : mnist_chainer

* MNISTの手書き文字データベースの文字を使って文字認識をやってみる
* 画像分類のベンチマークとしてどのミドルでもだいたいexampleが備わっている
* ということで、chainerのexampleの内容をほぼそのままトレースしたもの
 * CUDA無し環境で実行できるように一部回収箇所あり


## SAMPLE2 : MNIST手書き文字認識(TensorFlow版) : mnist_tensorflow

* Googleが公開したDeepLearningパッケージ、TensorFlowを使ってMNISTの手書き文字認識をやってみる
 * TensorFlowが必要

