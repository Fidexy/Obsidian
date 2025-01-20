## Definition

Bayes' Theorem provides a way to update the probability of a hypothesis AA given new evidence BB. It relates conditional probabilities and allows us to calculate the reverse conditional probability P(A∣B)P(A∣B) from P(B∣A)P(B∣A).

## Formula

P(A∣B)=P(B∣A)⋅P(A)P(B)P(A∣B)=P(B)P(B∣A)⋅P(A)​
$$P(A|B) = \frac{P(B|A)\times P(A)}{P(B)}$$
Where:

- P(A∣B)P(A∣B) is the **posterior probability**: The probability of AA given BB (updated belief after seeing evidence).
- P(B∣A)P(B∣A) is the **likelihood**: The probability of BB given AA (how likely the evidence BB is under AA).
- P(A)P(A) is the **prior probability**: The initial probability of AA before observing BB.
- P(B)P(B) is the **marginal probability**: The total probability of BB occurring.

## Total Probability Rule for P(B)P(B)

If A1,A2,…,AnA1​,A2​,…,An​ are mutually exclusive and exhaustive events, then:

P(B)=∑i=1nP(B∣Ai)⋅P(Ai)P(B)=i=1∑n​P(B∣Ai​)⋅P(Ai​)

This is used to calculate the denominator P(B)P(B) when BB depends on multiple events AiAi​.

---

## Intuition

Bayes' Theorem allows us to revise our beliefs (prior probabilities) in light of new evidence (posterior probabilities). It is particularly useful in situations where we need to infer causes from observed effects.

---

## Example

### Problem:

A clinic tests for a rare disease that affects 1 in 1000 people (P(D)=0.001P(D)=0.001). The test is 99% accurate:

- If someone has the disease, the test is positive 99% of the time (P(T∣D)=0.99P(T∣D)=0.99).
- If someone does not have the disease, the test is negative 99% of the time (P(T∣D′)=0.01P(T∣D′)=0.01).

What is the probability that a person has the disease if they test positive (P(D∣T)P(D∣T))?

---

### Solution:

1. **Given:**
    
    - P(D)=0.001P(D)=0.001 (prior probability of disease).
    - P(D′)=1−P(D)=0.999P(D′)=1−P(D)=0.999 (prior probability of no disease).
    - P(T∣D)=0.99P(T∣D)=0.99 (likelihood of a positive test given the disease).
    - P(T∣D′)=0.01P(T∣D′)=0.01 (likelihood of a positive test given no disease).
2. **Step 1: Calculate P(T)P(T) (marginal probability of testing positive):**  
    Using the total probability rule:
    
    P(T)=P(T∣D)⋅P(D)+P(T∣D′)⋅P(D′)P(T)=P(T∣D)⋅P(D)+P(T∣D′)⋅P(D′)
    
    Substituting values:
    
    P(T)=(0.99⋅0.001)+(0.01⋅0.999)P(T)=(0.99⋅0.001)+(0.01⋅0.999)
    
    P(T)=0.00099+0.00999=0.01098P(T)=0.00099+0.00999=0.01098
    
3. **Step 2: Apply Bayes' Theorem:**
    
    P(D∣T)=P(T∣D)⋅P(D)P(T)P(D∣T)=P(T)P(T∣D)⋅P(D)​
    
    Substituting values:
    
    P(D∣T)=0.99⋅0.0010.01098P(D∣T)=0.010980.99⋅0.001​
    
    P(D∣T)≈0.0901P(D∣T)≈0.0901
    
4. **Result:**  
    The probability that a person has the disease given a positive test result is approximately **9.01%**.