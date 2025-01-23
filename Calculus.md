# CALCULUS

## Function:

### Function of single variable:

A real valued function $y = f(x)$ of a real variable x is a mapping whose domain $S$ and codomain $R$ are sets of real numbers. The range of the function is the set ${y = f(x) : x \in R}$ which is a subset of $R$.

A relation f from a set $A$ to a set $B$ is said to be a function if every element of set $A$ has one and only one image in set $B$. In other words, a function $f$ is a relation such that no two pairs in the relation have the same first element.

The notation $f : X \rightarrow Y$ means that $f$ is a function from $X$ to $Y$ . $X$ is called the domain of $f$, and $Y$ is called the co-domain of $f$.

Given an element $x \in X$, there is a unique element $y$ in $Y$ that is related to $x$. The unique element $y$ to which $f$ relates $x$ is denoted by $f(x)$ and is called $f$ of $x$, or the value of $f$ at $x$, or the image of $x$ under $f$.

The set of all values of $f(x)$ taken together is called the range of $f$ or the image of $X$ under $f$. Symbolically:

range of $f = \{y \in Y | y = f(x)$, for some $x ∈ X\}$

| Function      | Domain         | Range               |
| ------------- | -------------- | ------------------- |
| $y = x + 2$   | $\mathbb{R}$   | $\mathbb{R}$        |
| $y = 3x² - 7$ | $\mathbb{R}$   | $\{y: y ≥ -7\}$     |
| $y = sin x$   | $\mathbb{R}$   | $\{y: -1 ≤ y ≤ 1\}$ |
| $y = 2^x$     | $\mathbb{R}$   | $\{y: y > 0\}$      |
| $y = 1/x$     | $\{x: x ≠ 0\}$ | $\{y: y ≠ 0\}$      |
| $y = log₂ x$  | $\{x: x > 0\}$ | $\mathbb{R}$        |

### Domain and Range (Types of Functions)

1. **One-One (Injective) Function**<br>
   A function $f : X \rightarrow Y$ is defined to be one-one (or injective) if the images of distinct elements of $X$ under $f$ are distinct, i.e., for any $x1, x2 \in X$, if $f(x1) = f(x2)$, then it implies that $x1 = x2$.

2. **Onto (Surjective) Function**<br>
   A function $f : X \rightarrow Y$ is said to be onto (or surjective) if every element of $Y$ is the image of some element of $X$ under $f$, i.e., for every $y \in Y$ , there exists an element $x \in X$ such that $f(x) = y$.

3. **One-One and Onto (Bijective) Function**<br>
   A function $f : X \rightarrow Y$ is said to be one-one and onto (or bijective) if it is both one-one and onto.

### Special functions

- <u>**Explicit Functions**</u> <br>
  Explicit functions are functions where the dependent variable (usually denoted as $y$) is expressed explicitly in terms of the independent variable (usually denoted as $x$), such as $y = f(x)$. <br>
  _**Example**_ :$y = f(x) = 2x + 3$

- <u>**Implicit Functions**</u> <br>
  Implicit functions are functions where the relationship between the dependent and independent variables is defined implicitly, often by an equation involving both variables, like $x^2 + y^2 = 1$.

- <u>**Composite Functions**</u> <br>
  Composite functions are formed by combining two or more functions, creating a new function. For example, if $f(x)$ and $g(x)$ are functions, the composite function $h(x) = f(g(x))$ or $h(x) = g(f(x))$ <br>
  Let $f(x) = 2x$ and $g(x) = x^2$. Then the composite function is $h(x) = f(g(x)) = 2x^2$.

- <u>**Polynomial Functions**</u> <br>
  Polynomial functions are algebraic functions of the form <br>
  $f(x) = a_nx^n + a_{n−1}x_{n−1} + . . . + a_1x + a0$, where ai are constants, and n is a non-negative integer.<br>
  _**Example**_: $f(x) = 3x^3 − 2x^2 + 5x − 1$ is a polynomial function in `x` with degree 3.<br>

      Note: A polynomial function of degree ’0’ is called a constant polynomial function (or) simply constant function.

- <u>**Rational Functions**</u> <br>
  Rational functions are functions of the form $f(x) = \frac{p(x)}{q(x)}$ , where $p(x)$ and $q(x)$ are both
  polynomial functions. <br> _**Example**_: $f(x) = \frac{2x^2−3x+1}{x^2+4x+4}$

- <u>**Algebraic Functions**</u> <br>
  Algebraic functions are functions that can be defined by algebraic equations involving polynomial, rational, and root functions.<br>
  _**Example**_: $f(x) = \sqrt{3x^3 − 2x^2 + 5x − 1}$ <br>
  If a relation arises due to performing a finite number of fundamental operations additions, subtraction, multiplication, division, root extraction etc. on polynomial functions then such a relation is also called an Algebraic function.

  1.  All polynomial functions are algebraic but not the converse.
  2.  A function that is not algebraic is called transcendental function.

- <u>**Logarithmic Functions**</u><br>
  Logarithmic functions are functions of the form $f(x) = logb(x)$, where $b$ is the base of the logarithm.<br>
  _**Example**_: $f(x) = log_{10}(x)$

- <u>**Even and Odd Functions**</u><br>
  Even functions are symmetric about the y-axis, and odd functions are symmetric aboutthe origin. For even functions, $f(−x) = f(x)$, and for odd functions, $f(−x) = −f(x)$. <br>
  _**Example**_: Even Function: $f(x) = x^2$ (Symmetric about the y-axis)

- <u>**Odd Function:**</u><br>
  $f(x) = x^3$ (Symmetric about the origin)

- <u>**Exponential Functions**</u><br>
  Exponential functions are functions of the form $f(x) = a^x$, where $a$ is a positive constant.
  _**Example**_: $f(x) = 2x$

- <u>**Modulus Functions**</u><br>
  Modulus functions, often denoted as $f(x) = |x|$, return the absolute value of $x$, making it always non-negative.
  _**Example**_: $f(x) = |x|$

- <u>**Signum (Sign) Functions**</u><br>
  The signum (sign) function is defined as $f(x) = \text{sgn}(x)$, where: <br>
  Example:

  $$
  \text{sgn}(x) =
  \begin{cases}
  -1 & \text{if } x < 0 \\
  0 & \text{if } x = 0 \\
  1 & \text{if } x > 0
  \end{cases}
  $$

### Composition of Functions

- Let $f : A \rightarrow B$ and $g : B \rightarrow C$ be two functions. Then, the composition of $f$ and $g$, denoted by $g \circ f$, is defined as the function $g \circ f : A \rightarrow C$ given by
  $$
  (g \circ f)(x) = g(f(x))\text{, for all }x \in A
  $$
- If $f : A \rightarrow B$ and $g : B \rightarrow C$ are one-one, then $g \circ f : A \rightarrow C$ is also one-one.
- If $f : A \rightarrow B$ and $g : B \rightarrow C$ are onto, then $g \circ f : A \rightarrow C$ is also onto.
- Let $f : A \rightarrow B$ and $g : B \rightarrow C$ be the given functions such that $g \circ f$ is one-one. Then $f$ is one-one.
- Let $f : A \rightarrow B$ and $g : B \rightarrow C$ be the given functions such that $g \circ f$ is onto. Then $g$ is onto.

### Invertible Function

- A function $f : X \rightarrow Y$ is defined to be invertible if there exists a function $g : Y \rightarrow X$ such that $g \circ f = I_X$ and $f \circ g = I_Y$ . The function $g$ is called the inverse of f and is denoted by $f^{−1}$.
- A function $f : X \rightarrow Y$ is invertible if and only if f is a bijective function.
- If $f : X \rightarrow Y$ , $g : Y \rightarrow Z$, and $h : Z \rightarrow S$ are functions, then $h \circ (g \circ f) = (h \circ g) \circ f$.
- Let $f : X \rightarrow Y$ and $g : Y \rightarrow Z$ be two invertible functions. Then $g \circ f$ is also invertible with $(g \circ f)^{−1} = f^{−1} \circ g^{−1}$.

## Limits

In calculus, the concept of a limit is fundamental to understanding the behavior of functions as they approach specific points. A limit represents the value that a function approaches as its input (independent variable) gets arbitrarily close to a certain value. We denote the limit of a function f(x) as x approaches a limit point c as follows:

$$
\lim_{x \rightarrow c} f(x) = L
$$

This means that as x gets very close to c, the values of f(x) get arbitrarily close to L.

The function $f$ is said to tend to the limit $\ell$ as $x \rightarrow a$, if for a given positive real number $\epsilon > 0$ we can find a real number $\delta > 0$ such that

$$
|f(x) - \ell| < \epsilon \quad \text{whenever} \quad 0 < |x - a| < \delta
$$

Symbolically we write

$$
\lim\_{x \to a} f(x) = \ell
$$

$\textbf{Left Hand and Right Hand Limits}$

Let $x < a$ and $x \rightarrow a$ from the left hand side.

If

$$
|f(x) - \ell_1| < \epsilon, \quad a - \delta < x < a \quad \text{or} \quad \lim_{x \to a^-} f(x) = \ell_1
$$

then $\ell_1$ is called the left hand limit.

Let $x > a$ and $x \rightarrow a$ from the right hand side.

If

$$
|f(x) - \ell_2| < \epsilon, \quad a < x < a + \delta \quad \text{or} \quad \lim_{x \to a^+} f(x) = \ell_2
$$

then $\ell_2$ is called the right hand limit.

<b>If $\ell_1 = \ell_2$ then $\lim_{x \to a} f(x)$ exists. If the limit exists then it is unique.</b>

### Basic Limit Rules

There are several basic rules that help us evaluate limits:

1. The Limit of a Constant:
   $$
   \lim_{x \rightarrow c} k = k
   $$
   where k is a constant.
2. The Limit of a Sum or Difference:

   $$
   \lim_{x\rightarrow c} [f(x) ± g(x)] = \lim_{x \rightarrow c}    f(x) \pm \lim_{x \rightarrow c} g(x)
   $$

3. The Limit of a Product:

   $$
   \lim_{x \to c} [f(x) . g(x)] = \lim_{x \to c}f(x) · \lim_{x \to c}  g(x)
   $$

4. The Limit of a Quotient:

   $$
   \lim_{{x \to c}} \frac{f(x)}{g(x)} = \frac{\lim_{{x \to c}} f(x)}{\lim_{{x \to c}} g(x)}, \text{ if } \lim_{{x \to c}} g(x) \neq 0
   $$

### Limits of Trigonometry Functions:

1. $\quad \lim_{{x \to 0}} \sin x = 0$

2. $\quad \lim_{{x \to 0}} \cos x = 1$

3. $\quad \lim_{{x \to 0}} \frac{\tan x}{x} = 1$

4. $\quad \lim_{{x \to 0}} \frac{\sin x}{x} = 1$

5. $\quad \lim_{{x \to 0}} \frac{\sin^{-1} x}{x} = 1$

6. $\quad \lim_{{x \to 0}} \frac{\tan^{-1} x}{x} = 1$

7. $\quad \lim_{{x \to \infty}} \frac{\sin x}{x} = 0$

8. $\quad \lim_{{x \to 0}} \left(\cos x + a \sin b x\right)^{\frac{1}{x}} = e^{ab}$

9. $\quad \lim_{{x \to 0}} \left(\frac{1 - \cos (ax)}{x}\right) = \frac{a^2}{2}$

### Limit to form $1^{\infty}$

1. $\quad \lim_{{x \to 0}} \left(1 + x\right)^{\frac{1}{x}} = e$

2. $\quad \lim_{{x \to 0}} \left(1 + ax\right)^{\frac{1}{x}} = e^a$

3. $\quad \lim_{{x \to \infty}} \left(1 + \frac{1}{x}\right)^x = e$

4. $\quad \lim_{{x \to \infty}} \left(1 + \frac{a}{x}\right)^x = e^a$

### Limits of Log and Exponential Functions

1. $\quad \lim_{{x \to 0}} e^x = 1$

2. $\quad \lim_{{x \to 0}} \frac{e^x - 1}{x} = 1$

3. $\quad \lim_{{x \to 0}} \frac{e^{mx} - 1}{mx} = m$

4. $\quad \lim_{{x \to 0}} \frac{a^x - 1}{x} = \log_e a$

5. $\quad \lim_{{x \to 0}} \frac{\log(1 + x)}{x} = 1$

6. $\quad \lim_{{x \to a}} \frac{x^n - a^n}{x - a} = na^{n-1}$

7. $\quad \lim\_{{x \to a}} \left( \frac{a^x + b^x}{2} \right)^{\frac{1}{x}} = \sqrt{ab}$

### L'Hospital's Rule:

We apply L'Hospital's Rule to the limit if we get the limit in the following forms (Indeterminate forms):

$$
\frac{0}{0}, \frac{\infty}{\infty}, 0 \cdot \infty, \infty - \infty, 0^0, 1^{\infty}, \infty^0
$$

Try to convert all indeterminate forms into $\frac{0}{0}$ or $\frac{\infty}{\infty}$, then only you can apply L'Hospital's Rule.

If $\lim_{x \to a} \frac{f(x)}{g(x)}$ is of the form $\frac{0}{0}$ or $\frac{\infty}{\infty}$, then:

$$
\lim_{{x \to a}} \frac{f(x)}{g(x)} = \frac{f'(x)}{g'(x)}
$$

Note:

If $\lim_{{x \to a}} f(x)$ exists, then it is unique.
If $f(x)$ is a polynomial function, then $\lim_{{x \to a}} f(x) = f(a)$.

## Continuity

1. **Continuity of a function at a point:** <br>
   A function $f(x)$ is said to be continuous at `a` if it satisfies the following conditions

   - $f(a)$ is defined
   - $\lim_{x \to a} f(x)$ exists i.e $\lim_{x \to a^{−}} f(x) = lim_{x \to a^{+}} f(x)$
   - $\lim_{x \to a^{+}} f(x) = f(a)$

2. **Left continuous (or) continuity from the left at a point:** <br>
   A function $f(x)$ is said to be continuous from the left (or) left continuous at $x = a$ if

   - $f(a)$ is defined
   - $\lim\_{x \to a^{-}} f(x) = f(a)$

3. **Right continuous (or) continuity from the right at a point:** <br>
   A function $f(x)$ is said to be continuous from the right (or) right continuous at $x = a$ if

   - $f(a)$ is defined
   - $\lim_{x \to a^{+}} f(x) = f(a)$

4. **Continuity of a function in an open interval:** <br>
   A function $f(x)$ is said to be continuous in an open interval $(a, b)$ if $f(x)$ is continuous $\forall x \in (a, b)$ (or) $\lim_{x \to c} f(x) = f(c) \forall c \in (a, b)$
5. **Continuity of a function on closed interval:** <br>
   A function $f(x)$ is said to be continuous on closed interval $[a, b]$if

   - $f(x)$ is continuous $\forall x ∈ (a, b)$
   - $\lim_{x \to a^{+}} f(x) = f(a)$
   - $\lim_{x \to b^{-}} f(x) = f(b)$

### Important Points:

1. If $f(x)$ and $g(x)$ are two continuous functions then $\quad f(x) + g(x),\quad f(x) − g(x),\quad f(x).g(x)$ and $\quad \frac{f(x)}{g(x)} (:: g(x) \neq 0)$ are also continuous.
2. Polynomial function, exponential function, sine and cosine functions, and modulus function are continuous everywhere.
3. Logarithmic functions are continuous in $(0, \infty)$
4. Let the functions f and g be continuous at a point $x = x_0$ then,
   - $cf$, $f \pm g$ and $f.g$ are continuous at $x = x_0$, where $c$ is any constant.
   - $\frac{f}{g}$ is continuous at $x = x_0$, if $g(x_0) \neq 0$
5. If $f$ is continuous at $x = x_0$ and $g$ is continuous at $f(x_0)$ then the composite function $g(f(g))$ is continuous at $x = x_0$.
6. If f is continuous at an interior point $c$ of a closed interval $[a, b]$ and $f(c) ̸= 0$, then there exists a neighbourhood of $c$, throughout which $f(x)$ has the same sign as $f(c)$.
7. If $f$ is continuous in a closed interval $[a, b]$ then it is bounded there and attains its bounds at least once in $[a, b]$.
8. If $f$ is continuous in a closed interval $[a, b]$, and if $f(a)$ and $f(b)$ are of opposite signs, then there exists at least one point $c \in [a, b]$ such that $f(c) = 0$.
9. If $f$ is continuous in a closed interval $[a, b]$ and $f(a) \neq f(b)$ then it assumes every value between $f(a)$ and $f(b)$.

## Differentiability

$f(x)$ is said to be differentiable at the point $x = a$ if the derivative $f‘(a)$ exists at every point in its domain. It is given by

$$
\lim_{h \to 0} \frac{f(a+h)−f(a)}{h}
$$

### Important Note:

1. If the derivative of $f(x)$ exists at $x = a$ then the function $f(x)$ is said to be differentiable function at $x = a$.
2. $f^l(a)$ exists at $x = a \iff Lf^l(a) = Rf^l(a)$.
3. If $f(x)$ and $g(x)$ are two differentiable functions then $f(x)+g(x)$, $f(x)−g(x)$, $f(x).g(x)$, $\frac{f(x)}{g(x)}$ .. $g(x) \neq 0$ are also differentiable.
4. Polynomial functions, exponential functions, sine and cosine functions are differentiable every where.
5. Every differentiable function is continuous but a continuous function need not be differentiable.

**Derivability of a function in an open interval:**<br>
A function $f(x)$ is said to be derivable (or) differentiable in an open interval $(a, b)$ if $f^l(c)$ exists $\forall c \in (a, b)$.

**Derivability of a function on closed interval:**<br>
A function $f(x)$ is said to be derivable (or) differentiable on closed interval $[a, b]$ i. if $f^l(c)$ exists $\forall c \in (a, b)$

1. $Rf^l(a)$ exists
2. $Lf^l(b)$ exists.

## Taylor Series

Let $f(x)$ be a function which is analytic at $x = a$. Then we can write $f(x)$ as the following power series, called the Taylor series of $f(x)$ at $x = a$:

$$
f(x) = f(a) + f'(a) \frac{(x - a)}{1!} + f''(a) \frac{(x - a)^2}{2!} + f'''(a) \frac{(x - a)^3}{3!} + \cdots
$$

### Maclaurin Series

If the Taylor Series is centred at 0, then the series is known as the Maclaurin series. It means that, if $a = 0$ in the Taylor series, then we get:

$$
f(x) = f(0) + f'(0) \frac{x}{1!} + f''(0) \frac{x^2}{2!} + f'''(0) \frac{x^3}{3!} + \cdots
$$

This is known as the Maclaurin series.

### Some Standard Series Expansions

1. $(1 - x)^{-1} = 1 + x + x^2 + x^3 + \cdots \quad \text{for } |x| < 1$

2. $(1 + x)^{-1} = 1 - x + x^2 - x^3 + \cdots \quad \text{for } |x| < 1$

3. $(1 - x)^{-2} = 1 + 2x + 3x^2 + 4x^3 + \cdots \quad \text{for } |x| < 1$

4. $(1 + x)^{-2} = 1 - 2x + 3x^2 - 4x^3 + \cdots \quad \text{for } |x| < 1$

5. $(1 - x)^{-3} = 1 + 3x + 6x^2 + 10x^3 + \cdots \quad \text{for } |x| < 1$

6. $\quad (1 + x)^{-3} = 1 - 3x + 6x^2 - 10x^3 + \ldots \quad [-1 < x < 1]$

7. $\quad (1 + x)^n = 1 + nx + \frac{n(n-1)}{2!}x^2 + \frac{n(n-1)(n-2)}{3!}x^3 + \ldots \quad [-1 < x < 1]$

8. $\quad (1 - x)^{-n} = 1 + nx + \frac{n(n+1)}{2!}x^2 + \frac{n(n+1)(n+2)}{3!}x^3 + \ldots \quad [-1 < x < 1]$

9. $\quad e^x = 1 + x + \frac{x^2}{2!} + \frac{x^3}{3!} + \ldots \quad [-\infty < x < \infty]$

10. $\quad e^{-x} = 1 - x + \frac{x^2}{2!} - \frac{x^3}{3!} + \ldots \quad [-\infty < x < \infty]$

11. $\quad \sin x = x - \frac{x^3}{3!} + \frac{x^5}{5!} - \frac{x^7}{7!} + \ldots \quad [-\infty < x < \infty]$

12. $\quad \sinh x = x + \frac{x^3}{3!} + \frac{x^5}{5!} + \frac{x^7}{7!} + \ldots \quad [-\infty < x < \infty]$

13. $\quad \sin^{-1} x = x + \frac{1}{2} \frac{x^3}{3} + \frac{1 \cdot 3}{2 \cdot 4} \frac{x^5}{5} + \frac{1 \cdot 3 \cdot 5}{2 \cdot 4 \cdot 6} \frac{x^7}{7} + \ldots \quad [-1 < x < 1]$

14. $\quad \cos x = 1 - \frac{x^2}{2!} + \frac{x^4}{4!} - \frac{x^6}{6!} + \ldots \quad [-\infty < x < \infty]$

15. $\quad \cosh x = 1 + \frac{x^2}{2!} + \frac{x^4}{4!} + \frac{x^6}{6!} + \ldots \quad [-\infty < x < \infty]$

16. $\quad \cos^{-1} x = \frac{\pi}{2} - \sin^{-1} x = \frac{\pi}{2} - \left( x + \frac{1}{2} \frac{x^3}{3} + \frac{1 \cdot 3}{2 \cdot 4} \frac{x^5}{5} + \ldots \right) \quad [-1 < x < 1]$

17. $\quad \tan x = x + \frac{x^3}{3} + \frac{2x^5}{15} + \ldots \quad \left[ -\frac{\pi}{2} < x < \frac{\pi}{2} \right]$

18. $\quad \tanh x = x - \frac{x^3}{3} + \frac{2x^5}{15} - \ldots \quad \left[ -\frac{\pi}{2} < x < \frac{\pi}{2} \right]$

19. $$
        \quad \tan^{-1} x =
            \begin{cases}
            x - \frac{x^3}{3} + \frac{x^5}{5} - \frac{x^7}{7} + \ldots & \text{for } -1 < x < 1 \\
            \frac{\pi}{2} - \frac{1}{x} + \frac{1}{3x^3} - \frac{1}{5x^5} + \ldots & \text{for } x \geq 1 \\
            -\frac{\pi}{2} + \frac{1}{x} - \frac{1}{3x^3} + \frac{1}{5x^5} - \ldots & \text{for } x < -1 \\
            \end{cases}
            \quad \left[-1 < x < 1\right]
    $$

20. $\quad \cot x = \frac{1}{x} - \frac{x}{3} - \frac{x^3}{45} + \ldots \quad \left[0 < x < \pi\right]$

21. $\quad \coth x = \frac{1}{x} + \frac{x}{3} - \frac{x^3}{45} + \ldots \quad \left[0 < |x| < \pi\right]$

22. $$
    \quad \cot^{-1} x = \frac{\pi}{2} - \tan^{-1} x =
        \begin{cases}
        \frac{\pi}{2} - \left(x - \frac{x^3}{3} + \frac{x^5}{5} - \frac{x^7}{7} + \ldots\right) & \text{for } -1 < x < 1 \\
        \frac{1}{x} - \frac{1}{3x^3} + \frac{1}{5x^5} - \ldots & \text{for } x \geq 1 \\
        \pi + \frac{1}{x} - \frac{1}{3x^3} + \frac{1}{5x^5} - \ldots & \text{for } x < -1 \\
        \end{cases}
        \quad \left[-1 < x < 1\right]
    $$

23. $\quad \sec x = 1 + \frac{x^2}{2} + \frac{5x^4}{24} + \ldots \quad \left[-\frac{\pi}{2} < x < \frac{\pi}{2}\right]$

24. $\quad \csc x = \frac{1}{x} + \frac{x}{6} + \frac{7x^3}{360} + \ldots \quad \left[0 < x < \pi\right]$

25. $\quad \ln(1 + x) = x - \frac{x^2}{2} + \frac{x^3}{3} - \frac{x^4}{4} + \ldots \quad \left[-1 < x < 1\right]$

## Maxima and Minima

### Maxima and minima for functions of one variable:-

**Local or relative maximum** <br>
A function $f(x)$ is said to have a Maximum at $x = c$ if there exists $\delta > 0$ such that $|x − c| <  \delta \Rightarrow f(x) \leq f(c)$.

**Local or relative minimum** <br>
A function $f(x)$ is said to have a minimum at $x = c$ if there exists $\delta > 0$ such that $|x − c| < \delta \Rightarrow f(x) \geq f(c)$.

**Stationary points** <br>
The values of $x$ for which $f(x) = 0$ are called stationary points or turning points.

**Stationary values** <br>
A function $f(x)$ is said to be stationary at $x = a$ if $f′(a) = 0$ and $f(a)$ is a stationary value.

**Extreme point** <br>
The point at which the function has a maximum or a minimum is called an extreme point.

**Extreme values** <br>
The values of the function at extreme points are called extreme values (Extrema).

**Point of inflection:**
The point at which a curve crosses its tangents is called the point of inflection.
The function $f(x)$ has neither maximum nor minimum at the point of inflection.

**Note:**

1. A necessary condition for a function to have an extreme value at $x = a$ is $f'(a) = 0$.
2. $f'(a) = 0$ is only a necessary condition but not a sufficient condition for $f(a)$ to be an extreme value of $f(x)$.
3. Every extreme point is a stationary point but every stationary point need not be an extreme point.

#### Absolute or Global maximum/minimum:

The absolute maximum/minimum values of the function $f(x)$ in the closed interval $[a, b]$ are given by

1. **Absolute maximum value**

   - $\max (f(a), f(b), \text{all local maximum values of } f)$
   - greatest value of $f(x)$ in $[a, b]$.

2. **Absolute minimum value**
   - $\min (f(a), f(b), \text{all local minimum values of } f)$
   - least value of $f(x)$ in $[a, b]$.

#### Working Rule to find maxima and minima:

Let $f(x)$ be the given function
**Step 1:** Find $f'(x)$
**Step 2:** Equate $f'(x)$ to zero to obtain the stationary points.
**Step 3:** Find $f''(x)$ at each stationary point.

- If $f''(x_0) > 0$ then $f(x)$ has a minimum at $x = x_0$
- If $f''(x_0) < 0$ then $f(x)$ has a maximum at $x = x_0$
- If $f''(x_0) = 0$ then $f(x)$ may (or) may not have extremum.

In this case, check for maxima and minima using the changes in sign of $f(x)$ as given below.

1. For $x < x_0$ if $f'(x) < 0$ and $x > x_0$ if $f'(x) > 0$ then $f(x_0)$ is a minimum value of $f(x)$.
2. For $x < x_0$ if $f'(x) > 0$ and $x > x_0$ if $f'(x) < 0$ then $f(x_0)$ is a maximum value of $f(x)$.
3. For $x < x_0$ and $x > x_0$ if $f'(x) > 0$ (or) $f'(x) < 0$ then $f(x_0)$ is not an extremum.

### Maxima and minima for functions of two variables:

Let $z = f(x, y)$ be the function of two variables for which maxima or minima is to be obtained.

**Working Rule:**

**Step 1:** Find $p, q, r, s$ and $t$

**Step 2:** Equate $p$ and $q$ to zero for obtaining stationary points.

**Step 3:** Find $r, s$ and $t$ at each stationary point.

1. If $rt - s^2 > 0$ and $r > 0$ then $f(x, y)$ has a minimum at that stationary point.
2. If $rt - s^2 > 0$ and $r < 0$ then $f(x, y)$ has a maximum at that stationary point.
3. If $rt - s^2 < 0$ then $f(x, y)$ has no extremum at that stationary point and such points are called saddle points.
4. If $rt - s^2 = 0$ then the case is undecided.
