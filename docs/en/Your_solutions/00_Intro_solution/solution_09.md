# Physics Problem: Optimization Problem

## 1. Key Definitions and Formulas

*   **Area of a Rectangle:** $A = w \cdot h$, where $w$ is width and $h$ is height.
*   **Curve Restriction:** The height is limited by the function curve $y = 3 - x^2$.
*   **Optimization:** To find the maximum of a function $A(x)$, we calculate its first derivative $A'(x)$ and set it to zero to find the critical points.

## 2. Solving the Problem

**Task:** Find the dimensions of the rectangle with maximum area under the curve $y = 3 - x^2$ in the first quadrant.

### Step-by-Step Derivation:

1.  **Define the Area Function:**
    Let the bottom-right corner of the rectangle on the x-axis be at position $x$. The width of the rectangle is $x$.
    The height is determined by the curve, so $h = 3 - x^2$.
    The area is:
    $$A(x) = x \cdot (3 - x^2) = 3x - x^3$$

2.  **Differentiate the Area function:**
    $$A'(x) = \frac{d}{dx}(3x - x^3)$$
    $$A'(x) = 3 - 3x^2$$

3.  **Find the critical points by setting the derivative to zero:**
    $$3 - 3x^2 = 0$$
    $$3x^2 = 3 \implies x^2 = 1$$
    Since the rectangle is in the first quadrant, the width must be positive, so $x = 1$.

4.  **Calculate the corresponding height:**
    Substitute $x = 1$ back into the height equation:
    $$y = 3 - (1)^2 = 3 - 1 = 2$$

### Final Answer:
The dimensions of the rectangle with the maximum area are:
$$Width = 1, \qquad Height = 2$$
