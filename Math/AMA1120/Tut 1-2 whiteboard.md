$$
\begin{align} \\
A. \\
f(x)&=x^4-6x^2+8x+10 \\
f’(x)&=4x^3-12+8 \\
f’’(x)&=12x^2-12 \\
f’(x)&=\frac{\beta-x}{x^{1-\beta}(1-x)^\beta} \\ \\
\\
\ln f’(x)&=\ln(\beta-x)-(1-\beta)\ln x-\beta \ln(1-x) \\
\frac{f’(x)}{f’’(x)}&=\frac{-1}{\beta-x}-\frac{1-\beta}{x}+\frac{\beta}{1-x} \\
&=\frac{-x(1-x)-(1-\beta)(\beta-x)(1-x)+\beta(\beta-x)x)}{(\beta-x)x(1-x)}\times \frac{\beta-x}{x^{1-\beta}(1-x)^\beta}\\
&=\frac{-\beta(1-\beta)}{x^{2-\beta}(1-x)^{1-\beta}} \\
\\
B. \\
f(x)&=x^{2/3}(1-x)^{1/3} \\
f’(x)&=\frac{\frac{2}{3}-x}{x^{1/3}(1-x)^{2/3}} \\
f’’(x)&=\frac{-\frac{2}{9}}{x^{4/3}(1-x)^{5/3}} \\
m &= \lim_{ x \to \infty } \frac{x^{2/3}(1-x)^{1/3}}{x}=\lim_{ x \to \infty } \left( \frac{1}{x}-1 \right)^{1/3}=-1 \\ \\
b&=\lim_{ x \to \infty } (f(x)+x)=\lim_{ x \to \infty } x^{2/3}(1-x)^{1/3}+x=\lim_{ x \to \infty } \left[ \left( \frac{1}{x}-1 \right)^{1/3}+1 \right] \\ 
=\lim_{ u \to -1 } \frac{u+1}{u^3+1}=\lim_{ u \to -1 } \frac{1}{3u^3}=\frac{1}{3} \\
\therefore y=-x+\frac{1}{3}
\\
C. \\ 
f(x)&=\frac{(x+1)^2}{x-1} \\
&=\frac{x^2+2x+1}{x-1} \\
&=x+3+\frac{4}{x-1} \\
&f’(x)=1-\frac{4}{(x-1)^2} \\
&f’’(x)=\frac{8}{(x-1)^3} \\
\\
D. \\ 
f(x)&=\frac{x^2}{x^2-3x+2} \\
&=x+3+\frac{7x-6}{(x-1)(x-2)} \\
&=x+\frac{-1}{x-1}+\frac{8}{x-2} \\
&f’(x)=1+\frac{1}{(x-1)^2}-\frac{8}{(x-2)^2} \\
&f’’(x)=-\frac{2}{(x-1)^3}+\frac{16}{(x-2)^3} \\
&\implies 8(x-1)^3=(x-2)^3 \\
&\implies2x-2=x-2 \\
&\implies x=0 \\
\\
E. \\
f(x)&=e^{-x^2} \\
f’(x)&=-2xe^{-x^2} \\
f’’(x)&=-2e^{-x^2}+4x^2e^{-x^2} \\
\\
\text{horizontal/oblique asymptotes:} \\
\lim_{ x \to \infty }[f(x)-(mx+b)]=0, y=mx+b  \\
\text{vertical asymptotes:} \\
\lim_{ x \to \pm c} f(x) = \pm \infty, x = c
\end{align}
$$