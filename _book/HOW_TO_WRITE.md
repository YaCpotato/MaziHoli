# このドキュメントの書き方

```
# タイトル
## 見出しレベル1
### 見出しレベル2

```
## 項目カラーリスト
<div class="color-area">
    <ol>
        <li style="background-color:#ffbcbc">#ffbcbc</li>
        <li style="background-color:#ffbcdd">#ffbcdd</li>	
        <li style="background-color:#ffbcff">#ffbcff</li>
        <li style="background-color:#ddbcff">#ddbcff</li>
        <li style="background-color:#bcbcff">#bcbcff</li>
        <li style="background-color:#bcddff">#bcddff</li>
        <li style="background-color:#bcffff">#bcffff</li>
        <li style="background-color:#bcffdd">#bcffdd</li>
        <li style="background-color:#bcffbc">#bcffbc</li>
        <li style="background-color:#ddffbc">#ddffbc</li>
        <li style="background-color:#ffffbc">#ffffbc</li>
        <li style="background-color:#ffddbc">#ffddbc</li>
    </ol>
</div>

## 数式の記述法  
{% math %}
\LARGE y(x,w) = w_0+w_1x_1+...+w_Dx_D
{% endmath %}
<div style="text-align:center">
    <p>{% math %}y:x{% endmath %}における目標値</p>
    <p>{% math %}D:{% endmath %}入力の次元数</p>
    <p>{% math %}x:{% endmath %}入力変数</p>
    <p>{% math %}w:{% endmath %}パラメータ</p>
</div>

## 画像
* ベクター形式を使用する

```
<div style="display:flex;">
    <img src='../assets/algorithm/linear_regression_00.svg' style="width:100%">
    <span>ddd</span>
</div>
```

<div style="display:flex;">
    <img src='../assets/algorithm/linear_regression_00.svg' style="width:100%">
    <span>ddd</span>
</div>