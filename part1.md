<script type="text/javascript" src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=default"></script>



# 集合
## 常用符号
符号|释义
---|:--:
$\in$|属于
$\notin$|不属于
$\subseteq$|包含于
$\subset$|真包含于
$\varnothing$|空集符号
$=$|集合相等符号
$\cap$|交集符号
$\cup$|并集符号
$U$|全集符号
$C_{U}$|补集符号
$N$|自然数集
$Z$|整数集
$N_{+}(N^{*})$|正整数集
$Q$|有理数集
$R$|实数集
$C_{R}Q$|无理数集

## 常用公式 ##
* $A\cap A=A$  
* $A\cap \varnothing=\varnothing$ 
* $A \cap U=A$
* $A\cup A=A$
* $A\cup \varnothing=A$
* $A\cup U=U$
* $A\cap C_{U}A=\varnothing$
* $A\cup C_{U}A=U$
* $C_{U}(C_{U}A)=A$
* $C_{U}(A\cap B)=(C_{U}A)\cup (C_{U}B)$
* $C_{U}(A\cup B)=(C_{U}A)\cap (C_{U}B)$
* $A\cap B=\{x|x\in A, 且x\in B\}$
* $A\cup B=\{x|x\in A, 或x\in B\}$

# 基本初等函数

## 1. 指数函数
(1) $a^r·a^s=a^{r+s}$, $(a^r)^s=a^{rs}$, $(ab)^{r}=a^rb^r$.$(a>0,r,s\in Q)$

(2) 当$n$为奇数时，$\sqrt[n]{a^n}=a$;

当$n$为偶数时，
$$
\sqrt[n]{a^n}=|a|=
\begin{cases}
a, a\geq 0,\\
-a, a < 0.\\

\end{cases}
$$
(3) $a^{\frac{m}{n}}=\sqrt[n]{a^m}(a>0,m,n\in N^*,且n>1)$;

$a^{-\frac{m}{n}}=\frac{1}{a^{\frac{m}{n}}}(a>0,m,n\in N^*,且n>1)$;

$a^0=1(a\ne 0)$.
## 2. 对数函数
(1)对数恒等式

$a^{\log_{a}{N}}=N$，$\log_aa=1$，$\log_a1=0$.(其中$N>0$，$a>0$，且$a\ne 1$)

(2)对数运算法则


设$a>0$，且$a\ne 1$，$M>0$，$N>0$，则：

$\log_{a}{(MN)}=\log_aM +\log_aN$，

$\log_{a}{(\frac{M}{N})}=\log_aM -\log_aN$，

$\log_{a}{N^n}=n\log_aN(n\in R)$，

$\log_{a^n}{M}=\frac{1}{n}\log_aM$

(3)对数换底公式

$\log_ab=\frac{\log_cb}{\log_ca}(a>0且a\ne 1；c>0且c\ne 1；b>0)$

## 3. 二次函数
### * 二次函数的三种表示形式
(1)一般式：$f(x)=ax^2+bx+c(a\ne 0)$；

(2)顶点式：$f(x)=a(x-m)^2+n(a\ne 0，m=-\frac{b}{2a}，k=\frac{4ac-b^2}{4a})$；

(3)两根式：$f(x)=a(x-x_1)(x-x_2)$.

### * 二次函数图像在$x$轴上两点间距离：
$|x_1-x_2|=\sqrt{(x_1+x_2)^2-4x_1x_2}=\frac{\sqrt{b^2-4ac}}{|a|}$.

### * 求解一元二次方程：
对于方程$ax^2+bx+c=0$：

(1)判别式：$\bigtriangleup=b^2-4ac$；

(2)求根公式$x_{1,2}=\frac{-b\pm\sqrt{\bigtriangleup}}{2a}$

(3)根与系数关系
$$
\begin{cases}
x_1+x_2=-\frac{b}{a}，\\
x_1x_2=\frac{c}{a}.\\
\end{cases}
$$