  
  
- [转置 transpose](#转置-transpose )
  - [转置的概念](#转置的概念 )
  - [转置的特性](#转置的特性 )
  
[返回目录](Readme.md )
  
##  转置 transpose
  
###  转置的概念
  
  
A 原本是 m × n，transpose 后变成 n × m
A 原来的 (i,j)-entry，transpose 后变成 (j,i)-entry
  
<p align="center"><img src="https://latex.codecogs.com/gif.latex?&#x5C;begin{bmatrix}a_{11},%20a_{12}&#x5C;cdots%20a_{1n}%20&#x5C;&#x5C;%20a_{21},%20a_{22}%20&#x5C;cdots%20a_{2n}%20&#x5C;&#x5C;%20&#x5C;vdots%20&#x5C;&#x5C;%20a_{n1},%20a_{n2}%20&#x5C;cdots%20a_{nn}%20&#x5C;end{bmatrix}&#x27;%20=%20&#x5C;begin{bmatrix}a_{11},%20a_{21}&#x5C;cdots%20a_{n1}%20&#x5C;&#x5C;%20a_{12},%20a_{22}%20&#x5C;cdots%20a_{n2}%20&#x5C;&#x5C;%20&#x5C;vdots%20&#x5C;&#x5C;%20a_{1n},%20a_{2n}%20&#x5C;cdots%20a_{nn}%20&#x5C;end{bmatrix}"/></p>  
  
  
###  转置的特性
  
  
- <img src="https://latex.codecogs.com/gif.latex?(%20A^{T}%20)^{T}%20=%20A"/>
- <img src="https://latex.codecogs.com/gif.latex?(sA)^{T}%20=%20sA^{T}"/>
- <img src="https://latex.codecogs.com/gif.latex?(A%20+%20B)^{T}%20=%20A^{T}%20+%20B^{T}"/>
- 转置也是线性系统
- 对称矩阵 symmetric matrix <img src="https://latex.codecogs.com/gif.latex?A^{T}%20=%20A"/>
- 对称矩阵一定是方阵
  