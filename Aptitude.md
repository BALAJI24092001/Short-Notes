### Arithmetic Progression (AP)

An arithmetic progression is a sequence of numbers in which the difference between consecutive terms is constant. If $a$ is the first term and $d$ is the common difference, the sum of the first $n$ terms is given by:

$$
 S_n = \frac{n}{2} [2a + (n - 1)d]
$$

In an arithmetic progression, if the common difference $d$ is positive or negative, the sum $S_n$ will approach infinity (or negative infinity) as $n$ approaches infinity. This is because each term increases (or decreases) linearly without bound.

### Geometric Progression (GP)

A geometric progression is a sequence of numbers in which the ratio between consecutive terms is constant. If $a$ is the first term and $r$ is the common ratio, the sum of the first $n$ terms is given by:

For $r \neq 1$:

$$
 S_n = a \frac{(1 - r^n)}{1 - r}
$$

For $r = 1$:

$$
 S_n = na
$$

For a geometric progression, we need to consider the common ratio $r$:

- **If $|r| < 1$**: The sum of the infinite geometric series converges to:

$$
 S_\infty = \frac{a}{1 - r}
$$

This is because the terms get smaller and smaller, approaching zero.

- **If $|r| \geq 1$**: The sum of the series diverges to infinity (or does not converge).

### Harmonic Progression (HP)

A harmonic progression is a sequence of numbers derived from the reciprocal of an arithmetic progression. If the terms of the HP are reciprocals of the terms of an AP, finding the sum of an HP is more complex and involves advanced calculus. There's no simple formula like AP or GP.

However, for small values of $n$, you can sum the reciprocals of the terms in the corresponding AP.

For a harmonic progression, the sum diverges to infinity as $n$ approaches infinity. This is because the harmonic series is known to diverge, meaning it grows without bound.

For example, the sum of the harmonic series:

$$
 1 + \frac{1}{2} + \frac{1}{3} + \frac{1}{4} + \cdots
$$

diverges as more terms are added.

### Sum of `n` natural numbers

$$
\frac{n(n+1)}{2}
$$

### Sum of square of `n` natural numbers

$$
\frac{n(n+1)(2n+1)}{6}
$$

### Sum of cube of `n` natural numbers

$$
\left[ \frac{n(n+1))}{2} \right]^2
$$
