# Euler Formula
$$\begin{align} \\
e^{i\theta}&=\cos \theta+i\sin \theta \\
e^x&=1+x+\frac{x^2}{2!}+\frac{x^3}{3!}+\frac{x^4}{4!}\dots \\
e^{i\theta}&=1+i\theta+\frac{(i\theta)^2}{2!}+\frac{(i\theta)^3}{3!}+\frac{(i\theta)^4}{4!}\dots \\
&=(1-\frac{\theta^2}{2!}+\frac{\theta^4}{4!}-\dots)+i(\theta-\frac{\theta^3}{3!}+\frac{\theta^5}{5!}-\dots) \\
&=\cos \theta+i\sin \theta
\end{align}
$$
# De Moivre’s Theorem
$$\begin{align} \\
(e^{i\theta})^n&=e^{i n \theta}+i\sin \theta \\
\cos \theta&=\frac{e^{i\theta}+e^{-i\theta}}{2} \\
\cos^{4} \theta &=\left( \frac{e^{i\theta}+e^{-i\theta}}{2} \right)^4 \\
&=\frac{1}{16}(e^{i 4 \theta}+4e^{i 2 \theta}+6+4e^{-i 2 \theta}+e^{-i 4 \theta}) \\
&=\frac{1}{16}(2\cos 4 \theta+8\cos 2 \theta+6)
\end{align}
$$
# Weierstrauss’ Substitution
$$\begin{align} \\
t=\tan \frac{\theta}{2}, &\sin \theta=2\sin \frac{\theta}{2}\cos \frac{\theta}{2}=2\tan \frac{\theta}{2}\cos^2\frac{\theta}{2}=\frac{2t}{t^2+1} \\
&\cos \theta=\cos^2\frac{\theta}{2}-\sin^2\frac{\theta}{2}=\cos^2\frac{\theta}{2}\left( 1-\tan^2\frac{\theta}{2} \right)=\frac{1-t^2}{1+t^2} \\
&\tan \theta=\frac{2t}{1-t^2}, dt=\frac{1}{2}\sec^2 \frac{\theta}{2}d\theta \implies d\theta=\frac{2dt}{1+t^2}
\end{align}$$