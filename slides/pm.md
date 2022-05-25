---
marp: true
theme: custom
header: 2022/05/25
footer: © 2022 RICORA Programming Team
paginate: true
size: 16:9
---

<!--_class: top-->

# パッケージマネージャーを使おう
## RICORA Programming Team

---

<!--_class: normal-->

# はじめに

- 挨拶文がうだうだ
- 宗教上の理由で強い拘りがある人は好きにやってください

---

<!--_class: normal-->

# パッケージマネージャーとは

- 説明

---

<!--_class: normal-->

# パッケージマネージャーの利点

- 説明
- コマンド1つでアプリがインストールできてうれしいね

---

<!--_class: top-->

# パッケージマネージャーの紹介
## OS別に紹介します

---

<!--_class: normal-->

# Windows
- **Chocolatey**
  - **今回はこれを使うよ**
- Scoop
  - Chocolateyのライバル
- Windows Package Manager(winget)
  - 最近出たWindows公式パッケージマネージャー
  - まだパッケージの充実度がいまいちなので今回は保留

---
<!--_class: normal-->

# Chocolatey

- https://chocolatey.org/install を見てね
- **4. Get Your Scripts**の**3. Install/Deploy Chocolatey internally**にある`Set-ExecutionPolicy なんたらかんたら…`のコマンドをコピー
- Windows+Xを押して、なんかメニューが出てくるのでWindows PowerShell (管理者)を選ぶ
- さっきコピーしたやつをペーストして実行(Enter)
- 終わったっぽいメッセージが出てきたら、一旦閉じてもう一度PowerShellを管理者で起動
- `choco install git -y`を実行してGitを入れる

---
<!--_class: normal-->

# MacOS

- **Homebrew**
  - **今回はこれを使うよ**
  - というかこれ以外聞いたことがない
  - GUI appもCUI appも両方管理できる
  - AppStore以外から入手したappをCUIで管理できる
  - 各appは/usr/local/Cellerにインストールされ、/usr/local/binにシンボリックリンクが貼られる
    - **環境が汚れない**
---
<!--_class: normal-->

# Xcode-Command-line-Tools

gitやgccなどのコマンドラインツールを使えるようにするためのツール

Homebrewをインストールする前に導入する必要がある

- ⌘ + SpaceでSpotlight検索を呼び出し、`terminal`と打ち込む(Return)
- `xcode-select --install`と打ち込む(Return)
- 入力が求められたらすべて`Y`(Yes)を入力

---

<!--=_class: normal-->

# Homebrew

- https://brew.sh/index_ja を見てね
- **インストール** の下にある`/bin/bash -c "$(curl -うんたらかんたら_`のコマンドをコピー
- ⌘ + SpaceでSpotlight検索を呼び出し、`terminal`と打ち込む(Return)
- さっきコピーしたやつをペーストして実行(Return)
- 入力が求められたらすべて`Y`(Yes)を入力
- `brew install python`を実行してPythonをインストールする

(※ Apple版のgitはxcode-comannd-line-toolsのインストール時に導入されています)

---

<!--_class: normal-->

# パッケージマネージャーの導入
- Wikiに詳しく書いてあるのでこっちを参考にして導入してね
  - Windows
    - [https://alg-wiki.tus-ricora.com/あとで](https://alg-wiki.tus-ricora.com/)
  - MacOS
    - [https://alg-wiki.tus-ricora.com/書かれる](https://alg-wiki.tus-ricora.com/)

---

<!--_class: normal-->

# さっそく使ってみよう
- 以下のパッケージ(アプリケーション)を入れてみよう
  - Git
  - Python
  - Node.js
  - Hugo
  - VS Code(まだ入れてなければ)

---

<!--_class: final-->

# ご清聴ありがとうございました