  
  
- [矩阵 matrix](#矩阵-matrix )
  - [矩阵的概念](#矩阵的概念 )
  - [矩阵的特性](#矩阵的特性 )
  - [特殊的矩阵](#特殊的矩阵 )
  
[返回目录](Readme.md )
  
##  矩阵 matrix
  
###  矩阵的概念
  
  
- 大写字母表示矩阵  
    <img src="https://latex.codecogs.com/gif.latex?A%20=%20&#x5C;begin{bmatrix}a_{11},%20a_{12}&#x5C;cdots%20a_{1n}%20&#x5C;&#x5C;%20a_{21},%20a_{22}%20&#x5C;cdots%20a_{2n}%20&#x5C;&#x5C;%20&#x5C;vdots%20&#x5C;&#x5C;%20a_{n1},%20a_{n2}%20&#x5C;cdots%20a_{nn}%20&#x5C;end{bmatrix}"/>  
  
- 矩阵有 row 和 column，矩阵的形状为 m by n / m × n
    <img src="https://latex.codecogs.com/gif.latex?M_{m&#x5C;times%20n}%20表示所有%20m%20×%20n%20矩阵的集合"/>  
  
- 矩阵中每个元素 component 的位置要用两个 index 来描述  
    <img src="https://latex.codecogs.com/gif.latex?A_{m,n}%20=%20A%20中第%20m%20行%20n%20列的元素"/>  
  
- 向量也是一种矩阵，矩阵也可以表示为向量的集合  
  
- 相同形状的矩阵可以相加减  
    <img src="https://latex.codecogs.com/gif.latex?&#x5C;begin{bmatrix}a_{11},%20a_{12}&#x5C;cdots%20a_{1n}%20&#x5C;&#x5C;%20a_{21},%20a_{22}%20&#x5C;cdots%20a_{2n}%20&#x5C;&#x5C;%20&#x5C;vdots%20&#x5C;&#x5C;%20a_{n1},%20a_{n2}%20&#x5C;cdots%20a_{nn}%20&#x5C;end{bmatrix}%20+%20&#x5C;begin{bmatrix}b_{11},%20b_{12}&#x5C;cdots%20b_{1n}%20&#x5C;&#x5C;%20b_{21},%20b_{22}%20&#x5C;cdots%20b_{2n}%20&#x5C;&#x5C;%20&#x5C;vdots%20&#x5C;&#x5C;%20b_{n1},%20b_{n2}%20&#x5C;cdots%20b_{nn}%20&#x5C;end{bmatrix}%20=%20&#x5C;begin{bmatrix}a_{11}+b_{11},%20a_{12}+b_{12}&#x5C;cdots%20a_{1n}+b_{1n}%20&#x5C;&#x5C;%20a_{21}+b_{21},%20a_{22}+b_{22}%20&#x5C;cdots%20a_{2n}+b_{2n}%20&#x5C;&#x5C;%20&#x5C;vdots%20&#x5C;&#x5C;%20a_{n1}+b_{n1},%20a_{n2}+b_{n2}%20&#x5C;cdots%20a_{nn}+b_{nn}%20&#x5C;end{bmatrix}"/>  
  
###  矩阵的特性
  
  
- <img src="https://latex.codecogs.com/gif.latex?A%20+%20B%20=%20B%20+%20A"/>
- <img src="https://latex.codecogs.com/gif.latex?(A%20+%20B)%20+%20C%20=%20A%20+%20(B%20+%20C)"/>
- <img src="https://latex.codecogs.com/gif.latex?(st)A%20=%20s(tA)"/>
- <img src="https://latex.codecogs.com/gif.latex?s(A%20+%20B)%20=%20sA%20+%20sB"/>
- <img src="https://latex.codecogs.com/gif.latex?(s%20+%20t)A%20=%20sA%20+%20tA"/>
  
###  特殊的矩阵
  
  
- 方阵 square matrix  m = n  
  
- 方阵的对角线 diagonal（仅方阵有 diagonal）  
  
- 上三角矩阵 upper triangular matrix （diagonal 以下为 0）  
  
- 下三角矩阵 lower triangulat matrix （diagonal 以上为 0）  
  
- 对角线矩阵 diagonal matrix （diagonal 以外为 0）  
  
- 单位矩阵 identity matrix （diagonal 全为 1 且以外为 0）<img src="https://latex.codecogs.com/gif.latex?I_{n}"/>  
  
- 零矩阵 zero matrix <img src="https://latex.codecogs.com/gif.latex?O_{m&#x5C;times%20n}"/>  
  