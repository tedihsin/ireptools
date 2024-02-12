# IReptools

## 目的

IR（Institutional Research）を効率的に進めるためのRStudioで使えるテンプレートおよび関数を提供する。

現時点では標準的なPDF出力用のテンプレートのみ収録。

## インストール
devtoolsをインストールし、install_github()関数でインストールする。

```r
> install.packages("devtools")
> devtools::install_github("https://github.com/tedihsin/ireptools.git")
```

## テンプレート
RStudioで"R Markdown"の新規ファイルを作成する際に、"From Template"にリストされるテンプレート。

- PDF Report (LuaLaTeX+jlreq)
  - 標準的なA4サイズのPDFを出力するテンプレート。
  - LuaLaTexでjlreq文書クラスを用いて日本語文書を生成する。
    - jlreq: https://www.google.com/search?client=firefox-b-d&q=jlreq
  - LaTex関係の設定はすべてYAML内に含み単一ファイルで利用できる。

