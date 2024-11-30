# 大阪電気通信大学 情報学科 卒業論文テンプレート

## 概要

[latex-template-ja](https://github.com/being24/latex-template-ja) と一連の docker イメージをベースに
作成された大阪電気通信大学 情報学科の卒業論文のテンプレート。

VS Code の devcontainer を用いており、VS Code と Docker Desktop がインストールされている環境を前提としている。

## まず最初にやること

 1. [github の hisa-lab](https://github.com/hisa-lab) にリポジトリ **bachelor-thesis-yyyy-ht99a999** (yyyy は西暦、ht99a999 は自分の学生番号に、それぞれ置き換え) を作成
 2. [このリポジトリ](https://github.com/hisa-lab/template-bachelor-thesis)を clone し、push 先を先程作成したリポジトリに変更(以下参照。リポジトリは各自のものに変更すること）して、push。
```
git remote rm origin
git remote add origin git@github.com:hisa-lab/bachelor-thesis-yyyy-ht99a999
git push -u origin main
```


 ## 論文の PDF 作成方法

 0. VS Code を起動 & コンテナでリポジトリを開く
 1. 論文執筆
 2. LaTeX のソースコード(例えば hoge.tex)を VS Code で表示
 2. VS Code のアクティビティバー（拡張機能等が表示されているところ）のTEXを選択
 3. コマンドから LaTeX プロジェクトをビルド
 4. LaTeX の記述内容に問題がなければ PDF の生成を確認
 5. コミット && push


## 参考URL

<https://zenn.dev/being/articles/how-to-use-my-latex>
