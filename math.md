* $log_ab\times log_ba=1$

	换底公式 $log_ab=\dfrac{log_cb}{log_ca}$，当 $c=b$ 时得出结论。

* $e^x\ge x+1> x> x-1\ge lnx$

	求导可证。

	推广：

	$e^{x+k}\ge x+k+1>x+k>x+k-1\ge ln(x+k)$

* $\sqrt a-\sqrt b=\frac{a-b}{\sqrt a+\sqrt b}$

	左式看作分母为 $1$ 的分数，分子有理化：

	$\sqrt a-\sqrt b=\frac{\sqrt a-\sqrt b}{1}=\frac{(\sqrt a-\sqrt b)(\sqrt a+\sqrt b)}{\sqrt a+\sqrt b}=\frac{a-b}{\sqrt a+\sqrt b}$

* $|AB|=\sqrt{1+k^2}|x_1-x_2|=\sqrt{1+\frac{1}{k^2}}|y_1-y_2|$（弦长公式）

	$|AB|=\sqrt{(x_1-x_2)^2+(y_1-y_2)^2}$，直线方程 $y=kx+b$ 代入即有结论。

* 点到直线距离公式

	$d=\dfrac{|Ax_0+Bx_0+C|}{\sqrt{A^2+B^2}}$（点到直线距离公式）

	推导好烦，背下来直接用得了。~~反正现在考不到圆锥曲线~~

* 求 $sin\alpha+\mu cos\alpha$ 的值域

	设 $tan\beta=\mu$ 且 $\beta\in(0,\frac{\pi}{2})$，画直角三角形得 $sin\beta=\frac{\mu}{\sqrt{1+\mu^2}}$，$cos\beta=\frac{1}{\sqrt{1+\mu^2}}$

	$sin\alpha+\mu cos\alpha=\dfrac{sin\alpha cos\beta+cos\alpha sin\beta}{cos\beta}$

	$=\frac{sin(\alpha+\beta)}{cos\beta}=\sqrt{1+\mu^2}sin(\alpha+\beta)\in[-\sqrt{1+\mu^2},\sqrt{1+\mu^2}]$

	能否将 $\mu$ 设为 $cos\beta$ 或 $sin\beta$ 呢？不能，因为 $\mu$ 可能大于 $1$。

* 作差法比较实数大小

	大题要求证明单调性、不等式时，用作差法比较严谨。

* $f(x)=ax^2+bx+c=a(x-x_1)(x-x_2)$（二次函数的交点式）

	注意做的时候不要忘了二次函数还有交点式这种写法。

	例：

	$f(x)=ax^2+bx+c$，$a>0$。$f(x)-x=0$ 的解为 $x_1,x_2$ 且 $0<x_1<x_2<\frac1a$

	求证：

	1. 当 $x\in(0,x_1)$ 时，$x<f(x)<x_1$

	2. $x_0<\frac{x_1}{2}$

* $a^3\pm b^3=(a\pm b)(a^2\mp ab+b^2)$

* 二分法求单调函数零点所在区间

	可用，不建议。

* $z\cdot\overline z=|z|^2$

	显然成立。

* $\overline{z_1\pm z_2}=\overline {z_1}\pm\overline {z_2},\overline{z_1\cdot z_2}=\overline {z_1}\cdot\overline {z_2},\overline{z_1\div z_2}=\overline {z_1}\div \overline{z_2}$

	最简单的证明方法就是将 $z_1,z_2$ 设出来，然后代入运算。

* 复数的三角形式

	做乘法、除法、乘方较快。

	$z=r(cos\theta+isin\theta),r=|z|$

	$z_1z_2=r_1r_2[cos(\theta_1+\theta_2)+isin(\theta_1+\theta_2)]$，模相乘，辐角相加。

	$\dfrac{z_1}{z_2}=\dfrac{r_1}{r_2}[cos(\theta_1-\theta_2)+isin(\theta_1-\theta_2)]$，模相除，辐角相减。

* $(a+bi)i=b-ai$，复数旋转 $90^\circ$

	易证成立。

* $|a|-|b|\le|a\pm b|\le|a|+|b|$(绝对值不等式）

	显然成立。前半式至今没用过，后半式常与放缩一起用。

* 三角换元

	1. 求 $\sqrt x+\sqrt{16-x}$ 的值域。

		$(\sqrt x)^2+(\sqrt{16-x})^2=16$

		$\Rightarrow (\frac{\sqrt x}{4})^2+(\frac{\sqrt{16-x}}{4})^2=1=sin^2\theta+cos^2\theta$

		设 $\sqrt x=4sin\theta,\sqrt{16-x}=4cos\theta$

		$\sqrt x+\sqrt{16-x}=4sin\theta+4cos\theta$

		$=4\sqrt{2}sin(\theta+\frac{\pi}{4})\in[-4\sqrt2,4\sqrt2]$

		$\because\sqrt x\ge0\Rightarrow sin\theta\ge0,\sqrt{16-x}\ge0\Rightarrow cos\theta\ge0$

		$\therefore\theta\in[0,\frac{\pi}{2}]\Rightarrow \theta+\frac{\pi}{4}\in[\frac{\pi}{4},\frac{3\pi}{4}]\Rightarrow sin(\theta+\frac{\pi}{4})\in[\frac{\sqrt2}{2},1]$

		$\therefore\sqrt x+\sqrt{16-x}\in[4,4\sqrt2]$

	2. 求 $\sqrt x-\sqrt{x-16}$ 的值域。

		$(\sqrt x)^2-(\sqrt {x-16})^2=16$

		$\Rightarrow(\frac{\sqrt x}{4})^2-(\frac{\sqrt{x-16}}{4})^2=1=\frac{cos^2\theta}{cos^2\theta}=\frac{1}{cos^2\theta}-\frac{sin^2\theta}{cos^2\theta}=\frac{1}{cos^2\theta}-tan^2\theta$

		设 $\sqrt x=\frac{4}{cos\theta},\sqrt{x-16}=4tan\theta$

		设 $y=\sqrt x-\sqrt{x-16}$

		$=\frac{4}{cos\theta}-4tan\theta=\frac{4-4sin\theta}{cos\theta}$

		$\Rightarrow4sin\theta+ycos\theta=4\Rightarrow\sqrt{16+y^2}=\dfrac{4}{sin(\theta+arctan\frac{y}{4})}$

		以上全是吓唬人的，写完发现这TM是个单调函数。

	推广：$x,y\in R$ 且 $x^2+y^2=k$，求 $x+y$ 的值域

	设 $x=\sqrt ksin\theta,y=\sqrt kcos\theta$

	$x+y=\sqrt k(sin\theta+cos\theta)=\sqrt{2k}sin(\theta+\frac{\pi}{4})\in[-\sqrt{2k},\sqrt{2k}]$

* 错位相减

	求 $S_n=\sum\limits_{i=1}^nA_iB_i$

	$A_n$ 为等差数列，公差为 $d$；$B_n$ 为等比数列，公比为 $q$

	$A_n=A_1+(n-1)\cdot d$

	$B_n=B_1\cdot q^{n-1}$

	$S_n=\sum\limits_{i=1}^n A_n\cdot B_n$

	$=A_1B_1+A_2B_2+A_3B_3+...+A_{n-1}B_{n-1}+A_nB_n$

	$=A_2B_2+A_3B_3+A_4B_4+...+A_nB_n+A_1B_1$

	$qS_n=qA_1B_1+qA_2B_2+qA_3B_3+...+qA_{n-1}B_{n-1}+qA_nB_n$

	$=A_1B_2+A_2B_3+A_3B_4+...+A_{n-1}B_n+A_nB_{n+1}$

	$qS_n-S_n=(q-1)S_n$

	$=(A_1B_2-A_2B_2)+(A_2B_3-A_3B_3)+...+(A_{n-1}B_n-A_nB_n)+A_1B_1+A_nB_{n+1}$

	$=B_2(A_1-A_2)+B_3(A_2-A_3)+...+B_n(A_{n-1}-A_n)+A_1B_1+A_nB_{n+1}$

	$=A_1B_1+A_nB_{n+1}-d\sum\limits_{i=2}^nB_i$

	最后两式同除以 $q-1$，注意 $q=1$ 的情况。
