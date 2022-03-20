[toc]

[返回目录](Readme.md)

## 矩阵 matrix
### 矩阵的概念

大写字母表示矩阵 A
矩阵有 row 和 column，矩阵的形状为 m by n / m × n
所有 m × n 矩阵的集合 $M_{m\times n}$
矩阵中每个元素 component 的位置要用两个 index 来描述
向量也是一种矩阵，矩阵也可以表示为向量的集合
相同形状的矩阵可以相加减

### 矩阵的特性

- A + B = B + A
- (A + B) + C = A + (B + C)
- (st)A = s(tA)
- s(A + B) = sA + sB
- (s + t)A = sA + tA

### 特殊的矩阵

方阵 square matrix：m = n
方阵的对角线 diagonal（仅方阵有 diagonal）
上三角矩阵 upper triangular matrix （diagonal 以下为 0）
下三角矩阵 lower triangulat matrix （diagonal 以上为 0）
对角线矩阵 diagonal matrix （diagonal 以外为 0）
单位矩阵 identity matrix （diagonal 全为 1 且以外为 0）$I_{n}$
零矩阵 zero matrix $O_{m\times n}$