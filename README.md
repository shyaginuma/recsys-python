{% include header.html %}

# recsys-python

## 概要
recsys-pythonはPythonによる推薦システムの演習問題集です。推薦システムの基本である、評価履歴や評価値行列の扱いから、内容ベース推薦システム、近傍ベース協調フィルタリング、推薦システムの評価などに関する問題を取り揃えています。現時点では、**13章構成**で**全163問**用意しています。今後、内容を変更したり、問題を追加、削除したりすることもあります。

## 動機
[言語処理100本ノック](https://nlp100.github.io/ja/)を参考にさせて頂き、推薦システム版の演習問題集を開発したいと思ったのがきっかけです。個人での学修に加え、大学での授業や研究室等でご活用いただければ幸いです。

## 到達目標

- Pythonを学修しながら推薦システムの基本を修得できる。
- 評価履歴や評価値行列を扱いながらNumPyによる行列演算やベクトル演算を修得できる。
- 数式をPythonでコーディングする方法を修得できる。

## 取り組み方
下記の目次から各章の問題に取り組んでください。

1. 各問題に書かれている指示文にしたがってコードを記述してください。
2. 各問題には**コード**と**結果**が記載されています。大問にまとめて記載されている場合もあります。
3. **コード**中には`【    問01    】`のように空欄があります。**結果**に記載のとおりの内容が出力されるように、この空欄に入る適切なコードを記述してください。

###### 要件について

- 各問題には要件が記載されています。この要件をすべて満たすようにコードを記述してください。
- 要件の難易度が★の数で示されています。
- この要件はヒントにもなります。考えたり調べたりする際の手がかりにしてください。
- 問題によっては複数の要件パターンが記載されいるものもあります。この場合はいずれかの要件パターンを満たすので十分です。
- Pythonは自由度が高い言語で、コードの書き方は幾通りもあります。そのため、要件を設定することで、ある程度の縛りを課しています。ただし、Pythonに慣れている方は、要件に縛られず独自の書き方で書かれるのも良いでしょう。作成者が想定しているよりももっと良い書き方があるかもしれません。

## 目次

### 評価履歴と評価値行列

- [第1章 評価履歴](ja/chap01.md)
- [第2章 評価値行列](ja/chap02.md)

### 内容ベース推薦システム（近傍ベース方式）

- [第3章 類似度に基づく推薦](ja/chap03.md)
- [第4章 k近傍法](ja/chap04.md)

### 近傍ベース協調フィルタリング

- [第5章 ユーザベース協調フィルタリング](ja/chap05.md)
- [第6章 アイテムベース協調フィルタリング](ja/chap06.md)

### 次元削減
- [第7章 評価履歴の次元削減](ja/chap07.md)
- [第8章 評価値行列の次元削減](ja/chap08.md)

### 内容ベース推薦システム（モデルベース方式）

- [第9章 単純ベイズ分類器](ja/chap09.md)
- [第10章 決定木](ja/chap10.md)

### 推薦システムの評価

- [第11章 嗜好予測の正確性](ja/chap11.md)
- [第12章 好き嫌い分類に基づく評価指標](ja/chap12.md)
- [第13章 推薦順位に基づく正確性](ja/chap13.md)

## 参考

PythonおよびNumPyについては、下記の公式チュートリアルが参考になります。
- [Python チュートリアル](https://docs.python.org/ja/3.9/tutorial/)
- [Quickstart tutorial — NumPy Manual](https://docs.scipy.org/doc/numpy/user/quickstart.html)

演習問題に含まれる数式等については、下記出版予定の書籍にて解説しています。
- 奥健太，『基礎から学ぶ推薦システム ～情報技術で嗜好を予測する～』，コロナ社，2022．（2022年6月下旬出版予定）
- ※Pythonコードは本書には含まれておりません。

## 作成者

推薦システム研究室 奥 健太
