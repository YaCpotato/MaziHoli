# 線形回帰
## 線形回帰モデル
### 線形規程関数モデル(線形回帰)
回帰問題の目標は{% math %}N{% endmath %}個の観測値{% math %}\{x_n\}(n=1,...,N){% endmath %}と， それに対応する目標値{% math %}\{t_n\}{% endmath %}(つまり{% math %}f(x){% endmath %})からなるデータ集合が与えられた時， 目標値が未知である{% math %}x{% endmath %}が与えられた時の目標値(tの値)を予測する

{% math %}
\LARGE f(x) = w_0+w_1x_1+...+w_Dx_D
{% endmath %}
<div class="align-center">
    <p>式１：線形回帰モデル</p>
    <p>{% math %}f(x):x{% endmath %}における目標値</p>
    <p>{% math %}D:{% endmath %}入力の次元数</p>
    <p>{% math %}x:{% endmath %}入力変数</p>
    <p>{% math %}w:{% endmath %}パラメータ</p>
</div>

#### 例題：単回帰
適当なデータを回帰してみましょう。この目では単回帰(変数が１つの問題)を扱います。求めるべき変数が、直線の傾きになりますね。  
変数が１つというのは上の式の{% math %}D{% endmath %}が1ということなので

{% math %}
\LARGE f(x) = w_1x + w_0
{% endmath %}
<div class="align-center">
    <p>式２：単回帰モデル</p>
    <p>{% math %}f(x):x{% endmath %}における目標値</p>
    <p>{% math %}x:{% endmath %}入力変数</p>
    <p>{% math %}w_1:{% endmath %}直線f(x)の傾き</p>
    <p>{% math %}w_0:{% endmath %}直線f(x)の切片</p>
</div>

ということになります。  

データは以下のようになっています。
図１に散布図を示します。
```python
X = [15.5641825  22.09007012  4.60613421 12.14309801  8.7090281   6.67849749
  9.30477682 13.07566065 14.63185098 18.34526291 14.84967711 22.17390462
 10.08178346 26.80368421  5.65494661 21.2565694 ]
Y = [2.88360466 2.17708598 1.13066378 2.08154464 2.20449103 1.26892566
 1.87879944 2.00739501 2.39586485 2.78421595 2.06779237 3.14233324
 2.28120739 3.13928765 1.70278745 2.55154764]
```

<div class="align-center">
    <img src='../assets/algorithm/linear_regression_00.svg' class="full-width-img">
    <p class="figure-disc">図１：データ散布図</p>
</div>
見ての通り、データは直線では表しにくいものですので、新しいデータ{% math %}x{% endmath %}に対して確実にコレ！という{% math %}f(x){% endmath %}を求めることは難しいです(ある点にはかなり近いが違う点からは遠い　など)。ですので、ある程度の誤差は仕方ありません。できる限り誤差を減らし、図２のようなそれらしい直線を引くことが単回帰分析となります。
<div class="align-center">
    <img src='../assets/algorithm/linear_regression_01.svg' class="full-width-img">
    <p class="figure-disc">図２：単回帰分析後のイメージ</p>
</div>

### 参考文献
- C.M.ビショップ, パターン認識と機械学習　上, 2016, 丸善出版
