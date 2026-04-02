# Physics Problem: Definite Integrals

## 1. Key Definitions and Formulas

*   **Definite Integral:** Represents the signed area under a curve between two points, $a$ and $b$.
    $$A = \int_{a}^{b} f(x) \, dx$$
*   **Fundamental Theorem of Calculus:** If $F(x)$ is the antiderivative of $f(x)$, then:
    $$\int_{a}^{b} f(x) \, dx = F(b) - F(a)$$
*   **Integral of Sine:** 
    $$\int \sin(x) \, dx = -\cos(x) + C$$

## 2. Solving the Problem

**Task:** Calculate the area under the curve of $f(x) = \sin(x)$ from $x=0$ to $x=\pi$.

### Step-by-Step Derivation:

1.  **Set up the definite integral:**
    $$A = \int_{0}^{\pi} \sin(x) \, dx$$

2.  **Find the antiderivative:**
    The antiderivative of $\sin(x)$ is $-\cos(x)$. Apply the boundaries $0$ to $\pi$:
    $$A = \Big[ -\cos(x) \Big]_{0}^{\pi}$$

3.  **Evaluate at the upper and lower limits:**
    $$A = \left( -\cos(\pi) \right) - \left( -\cos(0) \right)$$

4.  **Substitute the trigonometric values:**
    We know that $\cos(\pi) = -1$ and $\cos(0) = 1$.
    $$A = \left( -(-1) \right) - \left( -(1) \right)$$
    $$A = (1) - (-1)$$
    $$A = 1 + 1 = 2$$

### Final Answer:
The area under the curve is:
$$Area = 2$$
