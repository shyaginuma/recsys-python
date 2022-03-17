{% include header.html %}

# recsys-python

- recsys-python
- https://recsyslab.github.io/recsys-python/

## 概要
recsys-pythonはPythonによる推薦システムの演習問題集です。推薦システムの基本である、評価履歴や評価値行列の扱いから、内容ベース推薦システム、近傍ベース協調フィルタリング、推薦システムの評価などに関する問題を取り揃えています。現時点では、13章構成で全163問用意しています（2022-03-17現在）。内容や問題数は今後変更や追加、削除する可能性もあります。

## 動機
[言語処理100本ノック](https://nlp100.github.io/ja/)を参考にさせて頂き、推薦システム版の演習問題集を開発したいと思ったのがきっかけです。個人での学修に加え、大学での授業や研究室等で活用いただければ幸いです。

## 到達目標

- Pythonを学修しながら推薦システムの基本を修得できる。
- 評価履歴や評価値行列を扱いながらNumPyによる行列演算やベクトル演算を修得できる。
- 数式をPythonでコーディングする方法を修得できる。

## 取り組み方
下記の目次から各章の問題に取り組んでください。

1. 各問題に書かれている指示文にしたがってコードを記述してください。
2. 各問題には**コード**と**結果**が記載されています。大問にまとめて記載されている場合もあります。
3. **コード**中には`【    問01    】`のように空欄があります。**結果**に記載のとおりの結果が出力されるように、この空欄に入る適切なコードを記述してください。

###### 要件について

- 各問題には要件が記載されています。この要件をすべて満たすようにコードを記述してください。
- 要件の難易度が★の数で示されています。
- この要件はヒントにもなります。
- 問題によっては複数の要件パターンが記載されいるものもあります。この場合はいずれかの要件パターンを満たすので十分です。

## 目次

##### [第1章 評価履歴](chap01.md)

##### [第2章 評価値行列](chap02.md)

##### [第3章 内容ベース推薦システム：類似度に基づく推薦](chap03.md)

##### [第4章 内容ベース推薦システム：k近傍法](chap04.md)

##### [第5章 ユーザベース協調フィルタリング](chap05.md)

##### [第6章 アイテムベース協調フィルタリング](chap06.md)

##### [第7章 評価履歴の次元削減](chap07.md)

##### [第8章 評価値行列の次元削減](chap08.md)

##### [第9章 内容ベース推薦システム：単純ベイズ分類器](chap09.md)

##### [第10章 内容ベース推薦システム：決定木](chap10.md)

##### [第11章 推薦システムの評価：嗜好予測の正確性](chap11.md)

##### [第12章 推薦システムの評価：好き嫌い分類に基づく評価指標](chap12.md)

##### [第13章 推薦システムの評価：推薦順位に基づく正確性](chap13.md)

## 参考

PythonおよびNumPyについては、下記の公式チュートリアルが参考になります。
- [Python チュートリアル](https://docs.python.org/ja/3.9/tutorial/)
- [Quickstart tutorial — NumPy Manual](https://docs.scipy.org/doc/numpy/user/quickstart.html)



