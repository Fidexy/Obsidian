## Basic Probability Principles

### 1. **Addition Rule**
- For mutually exclusive events A and B:
  $$
  P(A \cup B) = P(A) + P(B)
  $$

- For any events A and B:
  $$
  P(A \cup B) = P(A) + P(B) - P(A \cap B)
  $$

### 2. **Multiplication Rule**
- For independent events A and B:
  $$
  P(A \cap B) = P(A) \times P(B)
  $$

- For any events A and B:
 $$
  P(A \cap B) = P(A) \times P(B | A)
  $$

### 3. **Complementary Rule**
- For any event A:
  $$
  P(A') = 1 - P(A)
  $$

## Important Concepts

### 1. **Conditional Probability**
- Probability of A given B:
  $$
  P(A | B) = \frac{P(A \cap B)}{P(B)}
  $$

### 2. **Bayes' Theorem**
- Relates the conditional and marginal probabilities of random events:
  $$
  P(A | B) = \frac{P(B | A) \cdot P(A)}{P(B)}
  $$

### 3. **Total Probability Theorem**
- If $(B_1, B_2, \ldots, B_n)$ are mutually exclusive and exhaustive events:
  $$
  P(A) = \sum_{i=1}^{n} P(A | B_i) \cdot P(B_i)
  $$

## Example Applications
- **Risk Assessment:** Calculating the probability of events in finance.
- **Medical Testing:** Determining the probability of a disease given a positive test result.

These laws form the foundation of probability theory and are essential for analyzing random events.****