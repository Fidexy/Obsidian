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
y
\end{pmatrix}=\begin{pmatrix} x\cos \theta-y\sin \theta \\
x\sin \theta +y\cos \theta
\end{pmatrix}
\end{align}$$
**Givens Rotation**