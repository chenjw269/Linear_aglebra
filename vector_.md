  
  
- [向量 vector](#向量-vector )
  - [向量的概念](#向量的概念 )
  - [向量的特性](#向量的特性 )
  - [线性系统的表示方式一](#线性系统的表示方式一 )
  
[返回目录](Readme.md )
  
##  向量 vector
  
###  向量的概念
  
  
- 粗体字母表示一组数字  
  <img src="https://latex.codecogs.com/gif.latex?&#x5C;pmb{V}%20%20=%20[v_{1},%20v_{2},%20&#x5C;cdots%20v_{n}]"/>  
  
- 向量中的每个数字就是向量的一个元素  
  <img src="https://latex.codecogs.com/gif.latex?component%20%20=%20v_{i},%20i%20&#x5C;in%20[1,n]"/>   
  
- 向量中的元素可以用下标表示  
  <img src="https://latex.codecogs.com/gif.latex?v_{i}=&#x5C;pmb{V}%20中的第i个元素"/>  
  
- 低于四维的向量可以绘图表示出来  
  
- 向量可以组成集合，集合中可以有无穷多个向量  
  <img src="https://latex.codecogs.com/gif.latex?R^{n}%20表示由%20n%20个向量组成的所有集合"/>  
  
- 向量的相加  
  <img src="https://latex.codecogs.com/gif.latex?[v_{1},%20v_{2},%20&#x5C;cdots%20v_{n}]+[w_{1},%20w_{2},%20&#x5C;cdots%20w_{n}]%20=%20[v_{1}+w_{1},%20v_{2}+w_{2},%20&#x5C;cdots%20v_{n}+w_{n}]"/>  
  
- 向量的数乘  
  <img src="https://latex.codecogs.com/gif.latex?k[v_{1},%20v_{2},%20&#x5C;cdots%20v_{n}]%20=%20[kv_{1},%20kv_{2},%20&#x5C;cdots%20kv_{n}]"/>  
  
###  向量的特性
  
满足 8 个特征即为向量，而非向量具有这 8 个特征
  
- <img src="https://latex.codecogs.com/gif.latex?&#x5C;pmb{U}+&#x5C;pmb{V}=&#x5C;pmb{V}+&#x5C;pmb{U}"/>  
- <img src="https://latex.codecogs.com/gif.latex?(&#x5C;pmb{U}%20+%20&#x5C;pmb{V})%20+%20&#x5C;pmb{W}%20=&#x5C;pmb{U}%20+%20(&#x5C;pmb{V}%20+%20&#x5C;pmb{W})"/>  
- <img src="https://latex.codecogs.com/gif.latex?R^{n}%20中有零向量%20&#x5C;pmb{0}%20使得%20&#x5C;pmb{0}%20+%20&#x5C;pmb{U}%20=%20&#x5C;pmb{U}"/>  
- <img src="https://latex.codecogs.com/gif.latex?R^{n}%20中有向量%20&#x5C;pmb{U&#x27;}%20使得%20&#x5C;pmb{U&#x27;}%20+%20&#x5C;pmb{U}%20=%20&#x5C;pmb{0}"/>  
- <img src="https://latex.codecogs.com/gif.latex?1%20&#x5C;times%20&#x5C;pmb{U}%20=%20&#x5C;pmb{U}"/>  
- <img src="https://latex.codecogs.com/gif.latex?(ab)%20&#x5C;pmb{U}%20=%20a(b%20&#x5C;pmb{U})"/>  
- <img src="https://latex.codecogs.com/gif.latex?a(&#x5C;pmb{U}%20+%20&#x5C;pmb{V})%20=%20a%20&#x5C;pmb{U}%20+%20a%20&#x5C;pmb{V}"/>  
- <img src="https://latex.codecogs.com/gif.latex?(a+b)&#x5C;pmb{U}%20=%20a%20&#x5C;pmb{U}%20+%20b%20&#x5C;pmb{U}"/>  
  
###  线性系统的表示方式一
  
  
线性系统都可以表示为多元一次联立方程式  
Linear System = System of Linear Equations  
m 个 等式 equations，n 个 变量 variables，m × n 个系数 coefficient
  
<p align="center"><img src="https://latex.codecogs.com/gif.latex?&#x5C;begin{cases}a_{11}x_{1}+a_{12}x_{2}+&#x5C;cdots%20=%20m_{1}%20&#x5C;&#x5C;a_{21}x_{1}+a_{22}x_{2}+&#x5C;cdots%20=%20m_{2}%20&#x5C;&#x5C;&#x5C;quad%20&#x5C;vdots%20&#x5C;quad%20&#x5C;vdots%20&#x5C;&#x5C;a_{n1}x_{1}%20+%20a_{n2}x_{2}+&#x5C;cdots%20=%20m_{n}&#x5C;end{cases}"/></p>  
  
  
证明过程  
- System of Linear Equations → Linear System  
  将 n 个变量视为输入，m 个常数项视为输出，满足线性系统的两个特征  
- Linear System → System of Linear Equations  
  也就是证明，线性系统输出一定可以写成输入的 weight sum  
  standard (unit) vector  e1 [1,0,0,...], e2 [0,1,0,...]  
  所有的输入，都可以表示成 standard (unit) vector 的线性组合
  由线性系统的特点可知，所有输入的输出，也可以表示成 standard (unit) vector 的线性组合的输出
  