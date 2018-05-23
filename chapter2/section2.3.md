# 2.3 矩阵


矩阵是二维数组，其中的每一个元素被两个索引而非一个所确定。我们通常会赋予矩阵粗体的大写变量名称，比如A。 如果一个实数矩阵高度为m，宽度为n，那么我们说\\(A\epsilon R^{m\times n}\\) 。
$$\mathbf{A} =
\left( \begin{array}{ccc}
a\_{11} & a\_{12} & \ldots \\\\
a\_{21} & a\_{22} & \ldots \\\\
\vdots & \vdots & \ddots
\end{array} \right)$$
矩阵这东西在机器学习中就不要太重要了！实际上，如果我们现在有N个用户的数据，每条数据含有M个特征，那其实它对应的就是一个N*M的矩阵呀；再比如，一张图由16*16的像素点组成，那这就是一个16*16的矩阵了。现在才发现，我们大一学的矩阵原理原来这么的有用！要是当时老师讲课的时候先普及一下，也不至于很多同学学矩阵的时候觉得莫名其妙了。

<script type="text/javascript" src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=default"></script>
