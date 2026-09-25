# 知能情報基礎演習

立命館大学 情報理工学部「知能情報基礎演習」の演習用 Jupyter Notebook を配布するリポジトリです。

## ダウンロードのしかた

### すべてまとめて取得する

このページ右上の緑色の **Code** ボタン → **Download ZIP** を選ぶと、全ファイルが1つの zip で手に入ります。

git が使える人は次のコマンドでも取得できます。

```bash
git clone https://github.com/kawanishi-lab/kiso-enshu.git
```

一度 clone したあとで最新版に更新するには、そのフォルダの中で次を実行します。

```bash
git pull
```

### 1ファイルだけ取得する

課題ごとのフォルダから欲しいファイルを開き、表示されたページ右上の **Download raw file** ボタンを押してください。
ファイルの中身が表示されている画面でそのまま「保存」すると HTML が保存されてしまうので、必ずこのボタンを使ってください。

## Google Colab で開く

ノートブックをローカル環境に用意せずに動かしたい場合は、Colab で直接開けます。
GitHub 上のファイルの URL の `github.com` を `colab.research.google.com/github` に置き換えるだけです。

```
https://github.com/kawanishi-lab/kiso-enshu/blob/main/human-foundation-model/Sapiens_enshu.ipynb
↓
https://colab.research.google.com/github/kawanishi-lab/kiso-enshu/blob/main/human-foundation-model/Sapiens_enshu.ipynb
```

Colab で開いたあとは **ファイル → ドライブにコピーを保存** をしてから作業してください。
コピーを作らずに編集した内容は保存されません。

## 構成

```
human-foundation-model/    人物画像の基盤モデル（Sapiens）
open-vocab_recognition/    オープン語彙物体認識（YOLOE）
README.md                  このファイル
```

## 注意

- ノートブックは適宜追加・修正されることがあります。作業前に最新版かどうか確認してください。
- 内容についての質問は講義担当教員もしくは、講義担当教員を通して課題作成者に聞いてください。
