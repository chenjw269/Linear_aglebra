  
  
- [向量 vector](#向量-vector)
  - [向量的概念](#向量的概念)
  - [向量的特性](#向量的特性)
  - [线性系统的本质](#线性系统的本质)
  
[返回目录](Readme.md )
  
##  向量 vector
  
###  向量的概念
  
  
粗体字母表示一组数字 __V__
向量中的每个数字就是向量的一个元素 component
向量中的元素可以用下标表示 <img src="https://latex.codecogs.com/gif.latex?V_{i}"/>
低于四维的向量可以绘图表示出来
向量可以组成集合，集合中可以有无穷多个向量 <img src="https://latex.codecogs.com/gif.latex?R^{n}"/>
向量的相加、数乘
  
###  向量的特性
  
满足 8 个特征即为向量，而非向量具有这 8 个特征
  
- __U__ + __V__ = __V__ + __U__
- (__U__ + __V__) + __W__ =__U__ + (__V__ + __W__)
- <img src="https://latex.codecogs.com/gif.latex?R^{n}"/> 中有零向量 __0__ 使得 __0__ + __U__ = __U__
- <img src="https://latex.codecogs.com/gif.latex?R^{n}"/> 中有向量 __U'__ 使得 __U'__ + __U__ = __0__
- 1 __U__ = __U__
- (ab) __U__ = a(b __U__)
- a(__U__ + __V__) = a __U__ + a __V__
- (a+b)__U__ = a __U__ + b __U__
  
###  线性系统的本质
  
  
Linear System = System of Linear Equations，也就是多元一次联立方程式
m 个 等式 equations，n 个 变量 variables，m × n 个系数 coefficient
  
- System of Linear Equations → Linear System  
  将 n 个变量视为输入，m 个常数项视为输出，满足线性系统的两个特征
- Linear System → System of Linear Equations  
  线性系统输出一定可以写成输入的 weight sum  
  证明过程： standard (unit) vector  e1 [1,0,0,...], e2 [0,1,0,...]
  