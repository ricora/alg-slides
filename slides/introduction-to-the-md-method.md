---
marp: true
theme: custom
header: 2022/05/18
footer: © 2022 RICORA Programming Team
paginate: true
size: 16:9
---

<!--_class: top-->

# Markdown の使い方
## RICORA Programming Team

---

<!--_class: normal-->

# Markdown について
Markdown は[マークアップ言語](https://ja.wikipedia.org/wiki/%E8%BB%BD%E9%87%8F%E3%83%9E%E3%83%BC%E3%82%AF%E3%82%A2%E3%83%83%E3%83%97%E8%A8%80%E8%AA%9E)の 1 つであり、変換ツールを噛ますことにより、HTML や $\LaTeX$ などの別のマークアップ言語に変換をすることができる。

また、Pandoc や Marp, SATySFi などを用いれば高品質な PDF を生成することも可能である。すなわち、ツール次第であらゆることが可能である。

最近の技術系プラットフォームでは Markdown 記法をサポートしているものが多い。（GitHub, Discord, Qiita など）そのため、Markdown はプログラミングを学ぶ上では知っておいて損はない。

---

<!--_class: normal-->

# Markdown のメリットについて
- HTMLなどと比べ、とても簡潔に書くことができる。
-  覚えやすい記述方式である。
- 数式や表などを入力できる。

などが挙げられる。

---

<!--_class: normal-->

# Markdown の記述方法

実際の表示を上に、記法を下に示している。

---

<!--_class: normal-->

## 見出し
# h1

```
# h1
```

## h2

```
## h2
```

### h3

```
### h3
```

---

<!--_class: normal-->

## 段落
空の行で間を開けるか、または半角スペースを 2 つ開ければ良い。

東京理科大学

電子計算機  
研究会

```
東京理科大学
[空]
電子計算機__
研究会
```

---

<!--_class: normal-->

## 区切り線


```
---
あああ
___
あああ
***
あああ
```

---

<!--_class: normal-->

## 箇条書き
半角ハイフン ( - )  + スペース
- RICORA

```
- RICORA
```

---

<!--_class: normal-->

## 引用
半角大なり ( > ) を記述する。途中で ( > ) を増やすことにより 2 段引用が可能だ。
> Markdown（マークダウン）は、文書を記述するための軽量マークアップ言語のひとつである。本来はプレーンテキスト形式で手軽に書いた文書からHTMLを生成するために開発されたものである。
>  > Wikipediaより

```
> Markdown（マークダウン）は、文書を記述するための軽量マークアップ言語のひとつである。本来はプレーンテキスト形式で手軽に書いた文書からHTMLを生成するために開発されたものである。
>  > Wikipediaより
```

---

<!--_class: normal-->

##  画像

```
![説明](URL)
```
![RICORA](https://avatars.githubusercontent.com/u/33452053?s=200&v=4)
```
![RICORA](https://avatars.githubusercontent.com/u/33452053)
```

---

<!--_class: normal-->


## 数式

```$$```で囲った間に $\TeX$ 記述をすれば表示される。

$\left(\bigcap_{i=1}^\infty\bigcup_{j=i}^\infty A_j\right)=0$

```
$\left(\bigcap_{i=1}^\infty\bigcup_{j=i}^\infty A_j\right)=0$
```

---

<!--_class: normal-->

## 表
|普通|中央揃え|右揃え|
| - | :-: | -: |
|あ|い|う|

```
|普通|中央揃え|右揃え|
| - | :-: | -: |
|あ|い|う|
```

---

<!--_class: normal-->

## ソースコード

\```で文字を囲うことによりコード記述になる。

```C++
#include <iostream>
int main() {
    std::cout << "Hello, World!" << std::endl;
    return 0;
}
```

    ``` C++
    #include <iostream>
    int main() {
      std::cout << "Hello、 World!" << std::endl;
      return 0;
    }
    ```
---

インテンドでも代用ができる。
```
    aaa
    aaa
```
            aaa
            aaa

例えば、`print('Hello, world!')`というように埋め込むことも可能である。

```
例えば、`print('Hello, world!')`というように埋め込むことも可能である。
```

---

<!--_class: normal-->

## リンク
[RICORA アルゴリズム班](https://alg.tus-ricora.com/)

```
[RICORA アルゴリズム班](https://alg.tus-ricora.com/)
```
---

<!--_class: final-->

# ご清聴ありがとうございました