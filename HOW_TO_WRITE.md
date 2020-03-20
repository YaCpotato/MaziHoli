# このドキュメントの書き方

```
# タイトル
## 見出しレベル1
### 見出しレベル2

```
## 項目カラーリスト
<div class="color-area">
    <h3>メイン解説以外の解説はレベルによってタイトルの背景色を変える(h4(項)を想定)</h3>
    <ol>
        <h4 class="level-ten">.level-ten -大学数学レベル3-</h4>
        <h4 class="level-nine">.level-nine -大学数学レベル2-</h4>	
        <h4 class="level-eight">.level-eight　↑</h4>
        <h4 class="level-seven">.level-seven　↑</h4>
        <h4 class="level-six">.level-six -理系大学入試レベル-</h4>
        <h4 class="level-five">.level-five　↑</h4>
        <h4 class="level-four">.level-four　↑</h4>
        <h4 class="level-three">.level-three -高校数学レベル-</h4>
        <h4 class="level-two">.level-two　↑</h4>
        <h4 class="level-one">.level-one　↑</h4>
        <h4 class="level-zero">.level-zero -中学数学レベル-</h4>
    </ol>
</div>

## 数式の記述法  
```
{% math %}
\LARGE y(x,w) = w_0+w_1x_1+...+w_Dx_D
{% endmath %}
<div class="align-center">
    <p>{% math %}y:x{% endmath %}における目標値</p>
    <p>{% math %}D:{% endmath %}入力の次元数</p>
    <p>{% math %}x:{% endmath %}入力変数</p>
    <p>{% math %}w:{% endmath %}パラメータ</p>
</div>
```

## 画像
* ベクター形式を使用する

```
<div class="align-center">
    <img src='~~.svg' class="full-width-img">
    <p class="figure-disc">図1：適当な散布図</p>
</div>
```

<div class="align-center">
    <img src='~~.svg' class="full-width-img">
    <p class="figure-disc">図1：適当な散布図</p>
</div>