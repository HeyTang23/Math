# 函数

## 1. 函数的定义

![函数的定义](.\src\img\1.1.png)

- 万有引力公式：

$$
S = \frac{1}{2}gt^2
$$

- 可以写成

$$
S= 5t^2 \longrightarrow y=f(x)
$$

$$
x\longrightarrow 自变量\\
y\longrightarrow 因变量\\
f\longrightarrow 对应法则(表达式)
$$

### 两函数相同的条件

$$
f(x)=
\begin{cases}
定义域& (不化简)\\
对应法则& (化简)
\end{cases}
$$

![Screenshot_20210522-170016_哔哩哔哩](.\src\img\1.1.1.png)

## 2. 函数的表达形式

![函数的表现形式](.\src\img\1.2.1.png)

1. **显函数**
   $$
   y = x,y=x^2
   $$

2. **隐函数**
   $$
   f(x,y)=0
   $$

3. **参数函数(方程)**
   $$
   f(x)=
   \begin{cases}
   x = \sin t\\
   y = \cos t
   \end{cases}
   $$

4. **分段函数(求导)**

$$
y=|x|=\begin{cases}
x, &x = x>0\\
0, &x = 0&分段点\\
-x, &x<0
\end{cases}\\
x\in R
$$

![分段函数](.\src\img\1.2.2.png)
$$
f(x)=\begin{cases}
\sin x, &0<x<1\\
x^2+1, &x \geq 1& x=1为分段点\\
\end{cases}\\
考点：求分段函数在分段点的极限、连续、可导性
$$

## 3. 基本初等函数

### 常函数

$$
y=f(x)=C\\
y=2，定义域:x \in R，y\in R
图像
$$

![save (1)](.\src\svg\3.1.svg)

### 幂函数

$$
y=x^{-1},\frac{1}{x},(x\neq 0)
$$

![1](.\src\svg\3.2.1.svg)

$$
x^{\frac{1}{2}},(x\geq 0)
$$
![x^{\frac{1}{2}}](.\src\svg\3.2.2.svg)

$$
y=x
$$
![x](.\src\svg\3.2.3.svg)

$$
y=x^2
$$
![x](.\src\svg\3.2.4.svg)
$$
y=x^3
$$
![x^3](.\src\svg\3.2.5.svg)

### 指数函数

$$
y=a^x,(a>0且a\neq 1.x\in R)
$$

![image-20210524133132961](.\src\img\image-20210524133132961.png)

### 指数函数的关系试

1. $$
   e^m \cdot e^n = e^{m+e}
   $$

2. $$
   \frac{e^{m}}{e^{n}}=e^{m-n}
   $$

3. $$
   (e^m) = e^{m}\cdot n
   $$

4. $$
   (ab)^m = a^m \cdot a^m
   $$

5. $$
   (\frac{a}{b})^m = \frac{a^m}{b^m}
   $$

### 对数函数的关系试

1. $$
   \ln a\cdot b = \ln a + \ln b
   $$

2. $$
   \ln \frac{a}{b} = \ln a - \ln b
   $$

3. $$
   lnx^k = k\cdot\ln x(只有对数函数可以做到)
   $$

4. $$
   e^{\ln x} =x\\
   \ln e^x = x
   $$

5. $$
   \ln e = 1
   $$

$$
\log _{a}x(a>0且a\neq1,真数x恒大于0,a是底数)\\
\log _{e}x=\ln x\\
\begin{cases}
\ln 1 =0\\
\ln e =1
\end{cases}
$$

![desmos-graph (9)](.\src\svg\desmos-graph9.svg)
$$
\log _{a}x(a>1)
$$
![desmos-graph (10)](.\src\svg\desmos-graph10.svg)

$$
\log _{e}x=\ln x\\
\begin{cases}
\ln +\infty & \to +\infty\\
\ln 0 & \to -\infty
\end{cases}
$$
![desmos-graph (11)](.\src\svg\desmos-graph11.svg)
$$
\lg x = \log_{10}x
$$

### 三角函数

#### sin正弦

![sin](.\src\img\sin.png)

![save (2)](src\svg\sin.svg)

#### cos余弦

![cos](.\src\img\cos.png)

![cos](.\src\svg\cos.svg)

#### tan正切

![image-20210524144310104](.\src\img\tan.png)

![save (4)](.\src\svg\tan.svg)

#### cot余切

$$
y=\cot x = \frac{1}{\tan x}\\
\cot 30^{\circ} = \cot \frac{\pi}{6} = \frac{1}{\tan\frac{\pi}{6}}= \frac{3}{\sqrt{3}} = \frac{3\sqrt{3}}{3} = \sqrt{3}
$$

#### sec正割

$$
y=\sec x\\
secx = \frac{1}{\cos x}\\
$$

#### csc余割

$$
y=\csc x\\
cscx = \frac{1}{\sin x}\\
$$

### 倍角公式

$$
\sin2x=2\sin x \cdot\cos x\\
\cos 2x = \cos^2x - \sin^2x\\
降幂公式\\
=1-2\sin^2x \to \sin^2 = \frac{1-\cos2x}{2}\\
=2cos^2x-1 \to cos^2x = \frac{1+\cos2x}{2}
$$

### 反三角函数

$$
\left.\begin{matrix}
y=\arcsin x\\
y=\arccos x
\end{matrix}\right\}
定义域-1\leqslant x \leqslant 1
$$

![image-20210524153153855](.\src\img\arc.png)
$$
y=\arctan x\\
\left\{\begin{matrix}
\arctan+\infty \to \frac{\pi}{2}\\
\arctan-\infty \to -\frac{\pi}{2}
\end{matrix}\right.
$$
![arctan_x](.\src\img\arctan_x.svg)
$$
<Empty \space Math \space Block>
$$
