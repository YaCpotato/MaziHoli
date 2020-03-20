# 線形回帰
## 線形回帰モデル
### 線形規程関数モデル(線形回帰)
回帰問題の目標は{% math %}N{% endmath %}個の観測値{% math %}\{x_n\}(n=1,...,N){% endmath %}と， それに対応する目標値{% math %}\{t_n\}{% endmath %}(つまり{% math %}y{% endmath %})からなるデータ集合が与えられた時， 目標値が未知である{% math %}x{% endmath %}が与えられた時の目標値(tの値)を予測する  
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
数式の記述法  
{% math %}
\LARGE y(x,w) = w_0+w_1x_1+...+w_Dx_D
{% endmath %}
<div style="text-align:center">
    <p>{% math %}y:x{% endmath %}における目標値</p>
    <p>{% math %}D:{% endmath %}入力の次元数</p>
    <p>{% math %}x:{% endmath %}入力変数</p>
    <p>{% math %}w:{% endmath %}パラメータ</p>
</div>

<div style="text-align:center">
    <img src='../assets/algorithm/linear_regression_00.svg' style="width:100%">
    <p style="font-size:18px;">図1：適当な散布図</p>
</div>

### 参考文献
- C.M.ビショップ, パターン認識と機械学習　上, 2016, 丸善出版
