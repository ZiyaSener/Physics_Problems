# Physics Problem: Function Analysis

## 1. Key Definitions and Formulas

To find the local maxima or minima of a function $f(x)$, we use calculus:

*   **Quadratic Function:** The given function is a parabola $f(x) = 3x^2 - 12x + 7$.
*   **First Derivative ($f'(x)$):** Represents the slope of the tangent. Setting it to zero finds the critical points.
*   **Second Derivative ($f''(x)$):** Determines the concavity. 
    *   If $f''(x) > 0$, the critical point is a local minimum.
    *   If $f''(x) < 0$, it is a local maximum.

## 2. Solving the Problem

**Task:** Identify any local maxima or minima for the function $f(x) = 3x^2 - 12x + 7$.

### Step-by-Step Derivation:

1.  **Find the first derivative:**
    Using the power rule:
    $$f'(x) = \frac{d}{dx}(3x^2 - 12x + 7)$$
    $$f'(x) = 6x - 12$$

2.  **Set the first derivative to zero to find the critical point:**
    $$6x - 12 = 0$$
    $$6x = 12 \implies x = 2$$

3.  **Find the second derivative to test the critical point:**
    $$f''(x) = \frac{d}{dx}(6x - 12) = 6$$
    Since $f''(2) = 6 > 0$, the function is concave up, meaning the point is a **local minimum**.

4.  **Calculate the y-coordinate of the minimum:**
    Substitute $x = 2$ back into the original function:
    $$f(2) = 3(2)^2 - 12(2) + 7$$
    $$f(2) = 3(4) - 24 + 7$$
    $$f(2) = 12 - 24 + 7 = -5$$

### Final Answer:
The function has a local minimum at the coordinates:
$$(2, -5)$$
