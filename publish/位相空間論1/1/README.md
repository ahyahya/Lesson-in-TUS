## 連続性に関する概念の抽象化

距離空間 →(抽象化) 位相空間

### 定理
- X, Yを位相空間
- X×Yを　X, Yの直積空間
- <img src="https://latex.codecogs.com/gif.latex?%5Cdpi%7B120%7D%20%5Cphi%20%5Cnot%5Cin%20A%20%5Csubseteq%20X%2C%20%5Cphi%20%5Cnot%5Cin%20B%20%5Csubseteq%20Y">

とすると、

**A×BがX×Yの閉集合⇔AがXの閉集合かつBがYの閉集合**

X, Yを集合とし、

f: X->Yとするとき、

<img src="https://latex.codecogs.com/gif.latex?%5Cdpi%7B120%7D%20A%20%5Csubseteq%20X"> に対し、<img src="https://latex.codecogs.com/gif.latex?%5Cdpi%7B120%7D%20f%28A%29%20%3D%20%5C%7Bf%28x%29%7Cx%20%5Cin%20A%7D">

と定義し、

<img src="https://latex.codecogs.com/gif.latex?%5Cdpi%7B120%7D%20B%20%5Csubseteq%20Y"> に対し、<img src="https://latex.codecogs.com/gif.latex?%5Cdpi%7B120%7D%20f%5E%7B-1%7D%28A%29%20%3D%20%5C%7Bx%7Cf%28x%29%20%5Cin%20Y%2C%20f%28Y%29%20%5Cin%20B%7D">

と定義する

Xを集合とする

Xにおける数列<img src="https://latex.codecogs.com/gif.latex?%5Cdpi%7B120%7D%20%28a_1%2C%20...%29">を<img src="https://latex.codecogs.com/gif.latex?%5Cdpi%7B120%7D%20%28a_n%29_%7Bn%5Cin%7BN%7D%7D">のように表す

一般に、<img src="https://latex.codecogs.com/gif.latex?%5Cdpi%7B120%7D%20%5CLambda">を集合とし、各<img src="https://latex.codecogs.com/gif.latex?%5Cdpi%7B120%7D%20%5Clambda%20%5Cin%20%5CLambda">に対して

<img src="https://latex.codecogs.com/gif.latex?%5Cdpi%7B120%7D%20a_%5Clambda%20%5Cin%20X">　が与えられてるとするとき

<img src="https://latex.codecogs.com/gif.latex?%5Cdpi%7B120%7D%20%5CLambda"> を添数集合とするXにおける元の族

<img src="https://latex.codecogs.com/gif.latex?%5Cdpi%7B120%7D%20%28a_%5Clambda%7B%7D%29%5C_%7B%5Clambda%20%5Cin%20%5Clambda%7D">

を考えることができる

集合族<img src="https://latex.codecogs.com/gif.latex?%5Cdpi%7B120%7D%20%28A_%5Clambda%29%5C_%7B%5Clambda%20%5Cin%20%5CLambda%7D"> に対し、

<img src="https://latex.codecogs.com/gif.latex?%5Cdpi%7B120%7D%20%5Cprod_%7B%5Clambda%5Cin%5CLambda%7D%20%3D%20%7B%28a%5C_%5Clambda%29%7C%5Cforall%20%5Clambda%20%5Cin%20%5CLambda%2C%20a%5C_%5Clambda%20%5Cin%20%5CLambda%7D">

と定義し、これを

<img src="https://latex.codecogs.com/gif.latex?%5Cdpi%7B120%7D%20%28A_%5Clambda%29%5C_%7B%5Clambda%20%5Cin%20%5CLambda%7D"> の連続集合という。

Λ={1, ..., n}のとき、

<img src="https://latex.codecogs.com/gif.latex?%5Cdpi%7B120%7D%20%5Cprod_%7B%5Clambda%5Cin%5CLambda%7D">を<img src="https://latex.codecogs.com/gif.latex?%5Cdpi%7B120%7D%20%5CLambda_1%5Ctimes...%5Ctimes%5CLambda%5C_n">とも書く

Xを集合、d: X*X->Rとし、次の３条件を満足するとする

1. <img src="https://latex.codecogs.com/gif.latex?%5Cdpi%7B120%7D%20%5Cforall%20x%2C%20y%20%5Cin%20Y%2C%20d%28x%2C%20y%29%20%5Cgeq%200"> であって、
    d(x, y) = 0 <=> x = y
2. <img src="https://latex.codecogs.com/gif.latex?%5Cdpi%7B120%7D%20%5Cforall%20x%2C%20y%20%5Cin%20X%2C%20d%28x%2C%20y%29%20%3D%20d%28y%2C%20x%29">
3. <img src="https://latex.codecogs.com/gif.latex?%5Cdpi%7B120%7D%20%5Cforall%20x%2C%20y%2C%20z%20%5Cin%20X%2C%20d%28x%2C%20y%29%20+%20d%28y%2C%20z%29%20%5Cgeq%20d%28x%2C%20z%29">

このとき、

dはX上の距離(関数)である

Xはdに関して距離空間をなす

(X, d)は(Xを集合とする)距離空間である

Xは距離空間である

などという

d'(x, y) = d|(X'*X')

今後、距離空間(X, d)に対し、Xの部分集合X'を距離空間とみなすときは

特に断らなければ上述のd'を距離空間として考える

一般に、A', B'を集合、y: A' -> B, A in A'としf: A->Bを

f(a)=g(a)(a in A)により定めるとき、fをgへの制限といい、

f = g | A と表す




