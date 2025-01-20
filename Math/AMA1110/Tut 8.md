# Sampling
$X_{1}, X_{2}, \dots, X_{n} \approx (\text{mean }  \mu, \text{variance } \sigma^2 )$
$\bar{X} = \frac{X_{1}+ X_{2}+ \dots{}+X_{n}}{n}$
$S^2=\frac{1}{n-1} \sum^n_{i=1} (X_{i}-\bar{X})$

# #11
**a.**
Since $n = 50>5$ , y CLT, $\bar{X}\sim N\left(5, \frac{5^2}{50} \right)$ approx.
$$P(\bar{X}>5.5)=P\left( Z\frac{5.5-5}{\frac{5}{\sqrt{ 50 }}} \right)\approx P(Z>0.71)$$
Where $Z\sim N(0.1)$
**b.**
Suppose $n>30$, by CLT, $\bar{X} \sim N(5,\frac{5^2}{n})$ approx.
$$P(\bar{X}>5.1)\leq0.158$$
$$P\left(Z> \frac{5.1-5}{\frac{5}{\sqrt{ n }}} \right)\leq{0.157} \approx P(Z>1)$$
$$\frac{\sqrt{ n }}{\sqrt{ 0 }}\geq{1}$$
$$\therefore n\geq 2500$$