# README

kaggle/getting started/spaceship-titanic に対する私の取り組みです．

手順の説明があります．

## 開発

クローンして最初に開くときのみ，必要な訓練データを Kaggle からダウンロードしてください．

Dev Containers 拡張機能を入れたVSCodeで開いてください．自動的にコンテナが立ち上がります．

プレビューを見るには，

```bash
jupyter-book build book
```

を実行して，生成された `index.html` ファイルをブラウザで開いてください．

## デプロイ

jupyter-book と GitHub Action を用いて github pages にデプロイしています．

デプロイは

* `book` ディレクトリや workflow を変更して，
* `main` ブランチに push したときに

自動で行われます．
