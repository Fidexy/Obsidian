## Definition
The Poisson distribution is a discrete probability distribution that expresses the probability of a given number of events occurring in a fixed interval of time or space.
## Probability Mass Function (PMF)
$$ P(X = k) = \frac{\lambda^k e^{-\lambda}}{k!} $$

Where:
- $k$ is the number of events (k = 0, 1, 2, ...).
- $e$ is Euler's number, approximately 2.71828.
- **Rate $\lambda$:** Average number of events in the interval.
- **Random Variable (X):** Number of events in the interval.


## Properties
- **Mean (Expected Value):**  $$E(X) = \lambda $$
- **Variance:** $$ Var(X) = \lambda\ $$
- **Standard Deviation:** $$ \sqrt{\lambda}\ $$

## Assumptions
- Events occur independently.
- The average rate $\lambda$ is constant.
- Two events cannot occur at exactly the same instant.

## Examples
1. **Call Center:** Number of calls received per hour.
   - Average rate $$\lambda = 10 calls/hour $$

2. **Traffic Flow:** Number of cars passing through a checkpoint.
   - Average rate $$\lambda$$

## Applications
- Queuing theory.
- Risk management.
- Telecommunications.

## Related Distributions
- **Exponential Distribution:** Time between events in a Poisson process.
- **Binomial Approximation:** For large n and small p, a binomial distribution can be approximated by a Poisson distribution with \(\lambda = np\).

## Example Calculation
For a Poisson distribution with $\lambda = 3$, calculate $P(X = 2)$:

$$P(X = 2) = \frac{3^2 e^{-3}}{2!}$$

$$= \frac{9 \times 0.0498}{2}$$

$$= 0.224$$

This gives the probability of observing exactly 2 events in the interval.