# Q9a.
Ten workplaces are inspected. It is known that accidents occur at a mean rate of 0.1
cases per day in each place. What is the probability that in the next week (7 days),
exactly 3 out of the 10 workplaces will have at least 2 accidents?

$$ P(X>2) = 1-P(X\leq{1}) = 1-e^{-a_{7}} (1+0.7)= 0.155805$$
Let Y be the # of workplaces inspected having at least 2 accidents $Y\sim bin(10, 0.155805)$
$$ P(Y=3) = {10 \choose 3}(0.155805)^3 (1-0.155805)^7$$
$n = 1000, p = 0.1558, np = 155.8>5$
$n(1-p) = 855.2>5$
Normal approximation can be used

$\mu := np = 155.8, \sigma^2 := np(1-p) = 131.52635$
Let $V\sim N(155.8, 131.52636)$
$$ P(Y\geq 160) \approx P(V\geq 159.25)$$$$ \approx P(Z\geq 0.32), where Z \sim N(0.1)$$
$$\approx 0.3745$$