# 線形回帰
## 線形回帰モデル
### 線形規程関数モデル(線形回帰)
回帰問題の目標は{% math %}N{% endmath %}個の観測値{% math %}\{x_n\}(n=1,...,N){% endmath %}と， それに対応する目標値{% math %}\{t_n\}{% endmath %}(つまり{% math %}y{% endmath %})からなるデータ集合が与えられた時， 目標値が未知である{% math %}x{% endmath %}が与えられた時の目標値(tの値)を予測する  
<div class="color-area">
    <h3>解説のレベルによって背景色を変える</h3>
    <ol>
        <li class="level-ten">.level-ten -大学数学レベル3-</li>
        <li class="level-nine">.level-nine -大学数学レベル2-</li>	
        <li class="level-eight">.level-eight　↑</li>
        <li class="level-seven">.level-seven　↑</li>
        <li class="level-six">.level-six -理系大学入試レベル-</li>
        <li class="level-five">.level-five　↑</li>
        <li class="level-four">.level-four　↑</li>
        <li class="level-three">.level-three -高校数学レベル-</li>
        <li class="level-two">.level-two　↑</li>
        <li class="level-one">.level-one　↑</li>
        <li class="level-zero">.level-zero -中学数学レベル-</li>
    </ol>
</div>
数式の記述法  
{% math %}
\LARGE y(x,w) = w_0+w_1x_1+...+w_Dx_D
{% endmath %}
<div class="align-center">
    <p>{% math %}y:x{% endmath %}における目標値</p>
    <p>{% math %}D:{% endmath %}入力の次元数</p>
    <p>{% math %}x:{% endmath %}入力変数</p>
    <p>{% math %}w:{% endmath %}パラメータ</p>
</div>

<div class="align-center">
    <img src='../assets/algorithm/linear_regression_00.svg' class="full-width-img">
    <p class="figure-disc">図1：適当な散布図</p>
</div>

### 参考文献
- C.M.ビショップ, パターン認識と機械学習　上, 2016, 丸善出版
