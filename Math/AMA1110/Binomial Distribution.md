## Definition
The binomial distribution is a discrete probability distribution of the number of successes in a sequence of independent experiments, each asking a yes/no question.

## Characteristics
- **Trials (n):** Number of independent experiments.
- **Probability of Success (p):** Probability of a success on an individual trial.
- **Random Variable (X):** Number of successes in n trials.

## Probability Mass Function (PMF)
$$ P(X = k) = \binom{n}{k} p^k (1-p)^{n-k} $$

Where $\binom{n}{k}$ is the binomial coefficient: $$\frac{n!}{k!(n-k)!}$$
k is the number of successes 0 ≤ k ≤ n.

## Properties
- **Mean (Expected Value):** $E(X) = np$
- **Variance:** $Var(X) = np(1-p)$
- **Standard Deviation:** $\sqrt{np(1-p)}$

## Assumptions
- Fixed number of trials (n).
- Each trial is independent.
- Only two possible outcomes: success or failure.
- Constant probability of success (p) in each trial.

## Examples
1. **Coin Toss:** Flipping a fair coin 10 times.
   - Trials (n) = 10
   - Probability of heads (p) = 0.5

2. **Quality Control:** Inspecting 20 products for defects.
   - Trials (n) = 20
   - Probability of a defect (p)

## Applications
- Quality control in manufacturing.
- Survey analysis.
- Clinical trials.

## Related Distributions
- **Bernoulli Distribution:** Special case of the binomial distribution with n = 1.
- **Normal Approximation:** For large n, the binomial distribution can be approximated by a normal distribution if \(np\) and \(n(1-p)\) are both > 5.

## Example Calculation
For a binomial distribution with \(n = 5\) and \(p = 0.4\), calculate \(P(X = 3)\):

$$ P(X = 3) = \binom{5}{3} (0.4)^3 (0.6)^2 $$

$$ = 10 \times 0.064 \times 0.36 $$

$$ = 0.2304 $$

This gives the probability of getting exactly 3 successes in 5 trials.