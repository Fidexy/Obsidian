$$\begin{align} \\
&\frac{d}{dx}(\ln x) = \frac{1}{x} \text{ For x>0} \\
&\frac{d}{dx}(\ln(-x))=\frac{1}{x}\text{ For x<0} \\
&\frac{d}{dx}(\ln |x|) = \frac{1}{x} \text{ For x neq 0} \\
&\frac{d}{dx}(absx) = \sqrt{ x }\text{= 1 if x>0, -1 if x<0}  \
\end{align}$$

$$\begin{align} \\
f(x)&=x^\frac{2}{3}(1-x)^\frac{1}{3} \\
f’(x)&=\frac{\frac{2}{3}-x}{x^{1/3}(1-x)^{2/3}} \text{ for } x \neq; f’(x) = 0 \iff x=\frac{2}{3} \\
f’‘(x)&=\frac{-\frac{2}{4}}{x^{4/3}(1-x)^{5/x}}, \text{ for } x \neq 0 \text{ and } x \neq 1\\
\text{with ln f(x):} \\
f(x)&=x^{2/3}(1-x)^{1/3} \\
\ln |f(x)|&=\frac{2}{3}\ln|x|+\frac{1}{3}\ln|1-x| \\
\frac{f’(x)}{f(x)}&=\frac{\frac{2}{3}}{x}+\frac{-\frac{1}{3}}{1-x} \\
&=\frac{\frac{2}{3}}{\text{somethingiforgot}}
\end{align}
$$

$$\begin{align}\\
&\text{y-intercept: }f(0)=0 \\
&\text{x-intercept: }f(x)=0 \iff x=0, 1
\end{align}$$
$$\begin{align} \\
m&=\lim_{ x \to \infty } \frac{f(x)}{x}=\lim_{ x \to \infty } \left( \frac{1}{x}-1 \right)^{1/3}=-1 \\
b&=\lim_{ x \to \infty } (f(x)+x)=\lim_{ x \to \infty } x\left[ \left( \frac{1}{x}-1 \right)^{1/3}+1 \right] \\
&=\lim_{ x \to -1 } \frac{u+1}{u^3+1}=\lim_{ u \to -1 } \frac{1}{3u^2}=\frac{1}{3} \\
&\therefore g=-x+\frac{1}{3} \text{ is an inclined asymptotote}  \\
&\text{No vertical asymptotes}
\end{align}
$$
$$\begin{align} \\
x+y=(x-y)e^{-1/2(x-y)^2} \\
\text{Consider change of variables:} \\
&u=\frac{x-y}{\sqrt{ 2 }}=x\cos \frac{\pi}{4}-y\sin \frac{\pi}{4} \\
&v=\frac{x+y}{\sqrt{ 2 }}=x\sin \frac{\pi}{4}+y\cos \frac{\pi}{4} \\
&\begin{pmatrix}
\cos \theta &-\sin \theta \\
\sin \theta &\cos \theta
\end{pmatrix} \begin{pmatrix}
x \\
y \\
\end{pmatrix}=\begin{pmatrix} x\cos \theta-y\sin \theta \\
x\sin \theta +y\cos \theta \\
\end{pmatrix} \\
\end{align}$$
# Global Optimization
**Theoretical Guarantee**
- $f$ is continuous on $[a, b]$\
	$\implies$ global maximum/minimum exists in $[a, b]$\
decision variable: $x$\
objective function: $f(x)$\
**Q12.**
Let $x$ and $30-x$ be two positive numbers, $x \exists (0,30)$\
Let $f(x)=x^2+2(30-x)^2$, which we minimize\
$f’(x)=2x-4(30-x)=0 \implies x=20$\
Q12e\
$$\begin{align}\\
T(x)&=x+\frac{5}{4}\sqrt{ 20^2+(x-30)^2 } \\
T’(x)&=1+\frac{5}{4}\frac{x-30}{\sqrt{ 20^2+(x-30)^2 }}=0 \\
&\therefore \frac{\sqrt{ 20^2+(x-30)^2 }}{5}=\frac{30-x}{4}=\frac{20}{3} \\
&\implies x=\frac{10}{3}
\end{align}$$