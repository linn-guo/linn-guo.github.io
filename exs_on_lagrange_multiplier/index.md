# One Exercise about Lagrange Multiplier


Three different solutions to one problem.

## Question
The temperature at a point $(x,y)$ on a metallic floor is $T(x,y)=4x^2-4xy+y^2$.
Wearing thermocouples shoes that measures temperature, you walk along a circle of radius $5$ centered at the origin on the metallic floor.
What are the highest and lowest temperatures measured by your shoes?

<!--more-->

## Solution
### Lagrange Multiplier
The target: $T(x,y)=4x^2-4xy+y^2\Rightarrow T_x=8x-4y, T_y=-4x+2y$.

The constraint: $g(x,y)=x^2+y^2-25=0\Rightarrow g_x=2x, g_y=2y$.

By the method of Lagrange Multiplier,
$$
\begin{cases}
    8x-4y=\lambda\cdot 2x\\\
    -4x+2y=\lambda\cdot 2y\\\
    x^2+y^2=25
\end{cases}
\Rightarrow
\begin{cases}
    4x-2y=\lambda\cdot x\quad (1)\\\
    4x-2y=\lambda\cdot (-2y)\quad (2)\\\
    x^2+y^2=25 \quad (3)
\end{cases}
$$
Then,
$$
    (1)+(2)\Rightarrow \lambda\cdot x=\lambda\cdot (-2y)\Rightarrow \lambda\cdot (x-2y)=0\Rightarrow \lambda=0\text{ or } x=-2y.
$$
Sub $\lambda=0$ into (1), $4x-2y=0 \Rightarrow y=2x$.

Putting them together, $x=-2y$ or $y=2x$.

#### Method 1
Case 1.
Sub $x=-2y$ into $(3) \Rightarrow (-2y)^2+y^2=25 \Rightarrow 5y^2=25\Rightarrow y^2=5$.
$$
\begin{cases}
    x=-2\sqrt{5}\\\
    y=\sqrt{5}
\end{cases}
\quad \text{or} \quad
\begin{cases}
    x=2\sqrt{5}\\\
    y=-\sqrt{5}
\end{cases}
$$

case 2.
Sub $y=2x$ into $(3) \Rightarrow x^{2}+(2 x)^{2}=25 \Rightarrow 5 x^{2}=25 \Rightarrow x^{2}=5$.
$$
\begin{cases}
    x=\sqrt{5}\\\
    y=2\sqrt{5}
\end{cases}
\quad \text{or} \quad
\begin{cases}
    x=-\sqrt{5}\\\
    y=-2\sqrt{5}
\end{cases}
$$
(1) Sub $x=-2 \sqrt{5}, y=\sqrt{5}$ into $T(x, y)$,
$$
T(x, y)=4 x^{2}-4 x y+y^{2}=(2 x-y)^{2}=(-4 \sqrt{5}-\sqrt{5})^{2}=(-5 \sqrt{5})^{2}=25 \times 5=125.
$$
(2) Sub $x=2 \sqrt{5}, y=-\sqrt{5}$ into $T(x, y)$,
$$
T(x, y)=(2 x-y)^{2}=(4 \sqrt{5}+\sqrt{5})^{2}=(5 \sqrt{5})^{2}=125.
$$
(3) Sub $x=\sqrt{5}, y=2 \sqrt{5}$ into $T(x, y)$,
$$
T(x, y)=(2 x-y)^{2}=0.
$$
(4) Sub $x=\sqrt{5}, y=-2 \sqrt{5}$ into $T(x, y)$
$$
T(x, y)=(2 x-y)^{2}=0.
$$
Hence, the highest temperature is $125$, and the lowest one is $0$.

#### Method 2. Shortcut
Recall:
from the equation $(1)$ and $(2)$, we get $x=-2 y$ or $y=2 x$.

Case 1.
Sub $x=-2 y$ into (3), $(-2 y)^{2}+y^{2}=25 \Rightarrow y^{2}=5$

$$
\begin{aligned}
T(x, y) &=4 x^{2}-4 x y+y^{2} \\\
&=(2 x-y)^{2} \\\
&=(2 \cdot(-2 y)-y)^{2} \\\
&=25 y^{2}=25 \times 5=125 .
\end{aligned}
$$

Case2.
Sub $y=2 x$ into (3), $x^{2}+(2 x)^{2}=25 \Rightarrow x^{2}=5$

$$
\begin{aligned}
T(x, y) &=4 x^{2}-4 x y+y^{2} \\\
&=(2 x-y)^{2} \\\
&=(y-y)^{2} \\\
&=0.
\end{aligned}
$$

Hence, the highest temperature is $125$,
and the lowest one is $0$.

#### Remark
**Result 1.8A**

The maximum/minimum value of $f(x, y)$ subject to the constraint $g(x, y)=0$ occurs at a point $(x, y)$ that satisfies the following three equations
$$
\begin{aligned}
f_{x}&=\lambda g_{x} \\\
f_{y}&=\lambda g_{y} \\\
g(x, y)&=0
\end{aligned}
$$
for some constant $\lambda$, called a Lagrange multiplier.

### Parametric equations

The target: $T(x, y)=4 x^{2}-4 x y+y^{2} \quad (1)$.

The constraint: $g(x, y)=x^{2}+y^{2}-25=0 \quad (2)$.

The parametric equation for (2) is
$$
\begin{cases}
x=5 \cos \theta\\\
y=5 \sin \theta
\end{cases}
$$
and then sub into $(1)$,
$$
\begin{aligned}
    T(x, y)=(2 x-y)^{2} &=(10 \cos \theta-5 \sin \theta)^{2} \\\
    &=(5 \cdot(2 \cos \theta-\sin \theta))^{2}\\\
    &=25 \cdot(2 \cos \theta-\sin \theta)^{2} \\\
    &=25 \cdot(\sqrt{5} \cdot \cos (\theta+\alpha))^{2} \\\
    &=25 \cdot 5 \cdot \cos ^{2}(\theta+\alpha)\\\
    &=125 \cdot \cos ^{2}(\theta+\alpha).
\end{aligned}
$$

Note that $A\cos\theta-B\sin\theta=\sqrt{A^2+B^2}\cdot \cos (\theta+\alpha)$,
where $\alpha=\tan^{-1}\left(\frac{B}{A}\right)$.
Hence $2\cos\theta-\sin\theta=\sqrt{5}\cdot\cos(\theta+\alpha)$, $\alpha=\tan^{-1}(\frac{1}{2})$ in line $4$.

Note also $-1 \leqslant \cos (\theta+\alpha) \leqslant 1 \Rightarrow 0 \leqslant \cos ^{2}(\theta+\alpha) \leqslant 1 \Rightarrow 0 \leqslant T(x, y) \leqslant 125$.

Hence, the highest temperature is $125$,
and the lowest one is $0$.

<!-- <iframe src="/pdf/one_exercise_about_Lagrange_Multiplier.pdf" height="1000px" width="700px"></iframe> -->
