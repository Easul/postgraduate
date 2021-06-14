# 参考文档
* [官方](https://katex.org/docs/supported.html)进入  
* [简单](https://pandao.github.io/editor.md/examples/katex.html)文档  

# markdown引用方式
````markdown
```tex
{+}\lim\limits_{x \to \infty} f(x) = A  \\
```
````
```tex
{+}\lim\limits_{x \to \infty} f(x) = A  \\
```

# 常用语法
## 符号转义
行开头符号使用`{}`进行包裹, 则不会直接将特殊符号解析成markdown语法
````markdown
{+}
````
```tex
{+}
```
## 复杂公式嵌套
````markdown
(\sqrt{a^2 + b^2} - (1 + x)^2)
````
```tex
(\sqrt{a^2 + b^2} - (1 + x)^2)
```

## 右上标
````markdown
a^2
````
```tex
a^2
```

## 多个右上标
````markdown
a^{b^{2\pi}}
````
```tex
a^{b^{2\pi}}
```

## 右下标
````markdown
a_3
````
```tex
a_3
```

## 二维下角标
````markdown
a_{i, j}
````
```tex
a_{i, j}
```

## 右上右下标
````markdown
a_{i=3}^{5}
````
```tex
a_{i=3}^{5}
```

## 上下标
* displaystyle
  * 让公式显得更饱满
  * 让上下标生效
  
````markdown
\displaystyle \left (\sum_{i=0}^{\infty} \right)
````
```tex
\displaystyle \left (\sum_{i=0}^{\infty} \right)
```

## 极限
````markdown
\displaystyle \left (\lim_{x->-\infty}^{}\frac{\sin x}{x} = ? \right)  
````
```tex
\displaystyle \left (\lim_{x->-\infty}^{}\frac{\sin x}{x} = ? \right)  
```

## 正负号
````markdown
\pm
````
```tex
\pm
```

## 小于等于
````markdown
\leqslant
````
```tex
\leqslant
```

## 大于等于
````markdown
\geqslant
````
```tex
\geqslant
```

## 根号
````markdown
\sqrt{a^2 + b^2}
````
```tex
\sqrt{a^2 + b^2}
```

## 三角符号
````markdown
\sin(x)  \\
\cos(x)  \\
\tan(x)  \\
\arctan(x)  \\
````
```tex
\sin(x)  \\
\cos(x)  \\
\tan(x)  \\
\arctan(x)  \\
```

## 希腊字母
````markdown
\alpha  \\
\theta  \\
\xi  \\
\pi  \\
\phi  \\
\oint  \\
\Omega  \\
````
```tex
\alpha  \\
\theta  \\
\xi  \\
\pi  \\
\phi  \\
\oint  \\
\Omega  \\
```

## 求和符号
````markdown
\sum 
````
```tex
\sum 
```

## 连乘符号
````markdown
\prod
````
```tex
\prod
```

## 分数线
````markdown
\frac{-b \pm \sqrt{b^2 - 4ac}}{2a}  \\
\frac{b}{a}  \\
````
```tex
\frac{-b \pm \sqrt{b^2 - 4ac}}{2a}  \\
\frac{b}{a}  \\
```

## 积分
````markdown
\int 
````
```tex
\int 
```

## 无穷
````markdown
{-}\infty 
````
```tex
{-}\infty 
```

## 上尖号
````markdown
\hat f(x_i) 
````
```tex
\hat f(x_i) 
```

## 将公式写大
````markdown
\Bigl (\alpha \Bigr)
````
```tex
\Bigl (\alpha \Bigr)
```

## 省略号
````markdown
\cdots
````
```tex
\cdots
```

## 矩阵
````markdown
\begin{pmatrix}
   a & b \\
   c & d
\end{pmatrix}
````
```tex
\begin{pmatrix}
   a & b \\
   c & d
\end{pmatrix}
```

## 行列式
````markdown
\begin{vmatrix}
   a & b \\
   c & d
\end{vmatrix}
````
```tex
\begin{vmatrix}
   a & b \\
   c & d
\end{vmatrix}
```

## 交并符号
````markdown
\bigcap  \\
\bigcup  \\
````
```tex
\bigcap  \\
\bigcup  \\
```

## ~,等价
````markdown
\enspace\text{\textasciitilde}\enspace
````
```tex
\enspace\text{\textasciitilde}\enspace
```
## 不等于
````markdown
\mathrlap{\,/}{=}
````
```tex
\mathrlap{\,/}{=}
```

# 属于
````markdown
\in 
````
```tex
\in 
```

# 包含于
````markdown
\owns 
````
```tex
\owns 
```

## 突出颜色
````markdown
\color{red}{x^2}
````
```tex
\color{red}{x^2}
```

# 在线绘制曲线svg图形
[脚本之家工具](http://tools.jb51.net/aideddesign/fooplot)  
[绘图时常用函数参考](http://www.fooplot.com/faq)