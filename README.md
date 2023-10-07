
# 科研費Markdown

科研費などの書類を`Markdown`で記述し、出力します。

[リリース](https://ankys.github.io/kaken.md/)
[GitHub](https://github.com/ankys/kaken.md)

## 使い方

### 基本

1. [科研費Markdownのページ](https://ankys.github.io/kaken.md/)に行く。
2. プリセットのところで雛形を選択する（直接書いてもOK）。
3. 適宜編集する。
4. 出力ボタンを押して出力する。
5. 印刷ボタンを押すと印刷画面が開くので、印刷またはPDFなどに保存する。
6. テキストボックスの内容は保存されるので、前回の内容から再開できる。

### 記述方法

- [VFM (Vivliostyle Flavored Markdown)](https://vivliostyle.github.io/vfm/)記法で記述する。
- フロントマターの`template`にURLを設定するとテンプレートを指定できる。
- フロントマターの`base`にURLを設定すると外部ファイルの基底URLを指定できる。
- 本文の`{{! input(path) }}`や`{{ input(path) }}`の部分は`path`が示す外部ファイルの内容に置換される。

### 発展

- ローカルのファイルを読み込ませたいときにはフォルダをドラッグアンドドロップしてプロジェクトで選択する。
- この場合は基底URLは無視されてプロジェクトフォルダ内のファイルが参照される。
