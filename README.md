# GitHub Markdown Memo 📝
  GitHubで使用できるマークダウンやフォーマットの構文を自分なりにまとめとく備忘録。  
  「あのマークダウンなんだっけ...」「これ表現できるのかな...」と毎度調べるのも面倒なので随時書き足していきます。  
  <br>
  
  ▼いつも参考にしてる記事・文献
  - [基本的な書き方とフォーマットの構文 - GitHub Docs](https://docs.github.com/ja/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#quoting-text)
<br>

## 見出し - Heading -
  １つ～６つの`#`シンボルを先頭に配置する。
  ```
  # h1
  ## h2
  ### h3
  #### h4
  ##### h5
  ###### h6
  ```
  <img src="/images/heading.jpg" alt="heading" height="100px">
  <br>
  
  HTMLの`<h1>`～`<h6>`タグでも同様に"見出し"を生成できる。  
  ```
  <h1>h1</h1>
  <h2>h2</h2>
  <h3>h3</h3>
  <h4>h4</h4>
  <h5>h5</h5>
  <h6>h6</h6>
  ```
  <img src="/images/heading.jpg" alt="heading" height="100px">
  <br>
  
  `<h1>`～`<h6>`タグはAlign要素を指定できるので、左揃え・中央揃え・右揃えさせることが可能。
  ```
  <h1 align="left">h1</h1>
  <h2 align="center">h2</h2>
  <h3 align="right">h3</h3>
  ```
  ![heading-align](/images/heading-aling.jpg)  
  <br>

## テキスト書式　- Text Style -
  |スタイル|構文|入力例|出力|
  :-:|:-:|:-:|:-:
  |太字|`** **` or `__ __`|`**Maybe515**`|**Maybe515**|
  |斜体|`* *` or `_ _`|`_Maybe515_`|_Maybe515_|
  |取り消し線|`~~ ~~`|`~~Maybe515~~`|~~Maybe515~~|
  |太字内の斜体|`** **` or `__ __` 内で<br>`* *` or `_ _`|`**May*be*515**`<br>`__May*be*515__`|**May*be*515**<br> __May*be*515__|
  |太字かつ斜体|`*** ***`|`***Maybe515***`|***Maybe515***|
  <br>
  
## テキスト引用　- Text Quote-
