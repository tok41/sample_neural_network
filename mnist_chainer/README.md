# Example : MNIST Classification

## 1, 概要

* 普通の3層パーセプトロンを使ってMNISTの手書き文字認識をする(deepでは無い)
  * 0~9までの10個のカテゴリを認識する
* 画像分類のベンチマークとしてどのミドルでもだいたいexampleが備わっている
* ということで、chainerのexampleの内容をほぼそのままトレースしたもの
 * CUDA無し環境で実行できるように一部回収箇所あり


## 2, 必要要件

* Chainer
 * 1.3.2で動作確認
* ipython 3.1+
 * ipythonで作業します


## 3, 構成

```
- README.md : このファイル
- mnist_training.ipynb : モデル学習用のipythonファイル
- mnist_character_recognition.ipynb : 学習済みモデルを使って文字認識テストする
- data.py : chainer付属のexample, MNISTのデータを取得する
```


## 4, 実行手順

* ipythonを利用するので、iPythonを立ち上げておくこと

### 4-1 モデルのトレーニング

* 訓練用のファイルを開き、上から順に実行させる
 * mnist_training.ipynb
 * 学習時間が結構かかるので注意


### 4-2 文字認識の実験

* 以下のファイルを開き、上から実行する
 * mnist_character_recognition.ipynb
 * MNISTの文字画像データを使うように書いているが、この部分を任意の文字画像にすれば応用アプリが作れる
