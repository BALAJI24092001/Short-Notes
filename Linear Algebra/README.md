<span style="font-family: 'Times New Roman'; font-size: 1.15em;">

<h1 align = 'center'>LINEAR ALGEBRA</h1>

## Special Matrices

### Symmetric Matrix

A **symmetric matrix** is a square matrix $A$ that satisfies the condition:

$$
A^T = A
$$

This means that the matrix is equal to its transpose. In other words, the elements satisfy:

$$
a_{ij} = a_{ji} \quad \forall i, j
$$

#### Properties

1. **Diagonal Elements**:  
   The diagonal elements of a symmetric matrix can be any real number.

2. **Eigenvalues**:

   - All eigenvalues of a symmetric matrix are real.
   - The matrix can be diagonalized using an orthogonal matrix.

3. **Orthogonality**:  
   The eigenvectors of a symmetric matrix corresponding to distinct eigenvalues are orthogonal.

   - Mathematically, if $A$ is a symmetric matrix, and $\lambda_1, \lambda_2$ are distinct eigenvalues with eigenvectors $v_1$ and $v_2$, then:
     $$
     v_1^T v_2 = 0
     $$

4. **Orthogonal Basis**:  
   The eigenvectors of a symmetric matrix form an orthogonal basis for the vector space $\mathbb{R}^n$. If normalized, they form an **orthonormal basis**.

5. **Real Eigenvectors**:  
   Just like the eigenvalues, the eigenvectors of a symmetric matrix are real.

6. **Diagonalization**:  
   A symmetric matrix $A$ can be diagonalized using its eigenvectors:

   $$
   A = Q \Lambda Q^T
   $$

   where:

   - $Q$ is an orthogonal matrix containing the eigenvectors of $A$ as columns ($Q^T Q = I$).
   - $\Lambda$ is a diagonal matrix containing the eigenvalues of $A$.

7. **Multiplicative Properties**:  
   If $A$ is symmetric and $v$ is an eigenvector, then for any integer $k$:

   $$
   A^k v = \lambda^k v
   $$

   where $\lambda$ is the eigenvalue corresponding to $v$.

8. **Spectral Theorem**:  
   For any symmetric matrix $A$, we can decompose it as:

   $$
   A = \sum\_{i=1}^n \lambda_i v_i v_i^T
   $$

   where:

   - $\lambda_i$ are the eigenvalues.
   - $v_i$ are the normalized eigenvectors.

9. **Orthogonal Diagonalization**:  
   A symmetric matrix can be written as:

   $$
   A = Q \Lambda Q^T
   $$

   where:

   - $Q$ is an orthogonal matrix ($Q^T Q = I$).
   - $\Lambda$ is a diagonal matrix with eigenvalues of $A$ on the diagonal.

10. **Positive Definiteness**:  
    A symmetric matrix $A$ is:

    - **Positive definite** if $x^T A x > 0$ for all $x \neq 0$.
    - **Positive semi-definite** if $x^T A x \geq 0$ for all $x$.
    - **Negative definite** if $x^T A x < 0$ for all $x \neq 0$.

11. **Symmetry and Determinant**:  
    The determinant of a symmetric matrix can be calculated using its eigenvalues:

    $$
    \det(A) = \prod_{i=1}^n \lambda_i
    $$

    where $\lambda_i$ are the eigenvalues.

12. **Rank**:  
    The rank of a symmetric matrix equals the number of nonzero eigenvalues.

13. **Additive and Multiplicative Symmetry**:

    - The sum of two symmetric matrices is symmetric:
      $$
      A + B \quad \text{is symmetric if } A^T = A \text{ and } B^T = B.
      $$
    - The product of two symmetric matrices is symmetric **if and only if they commute**:
      $$
      AB = BA \implies AB \text{ is symmetric.}
      $$

14. **Block Symmetry**:  
    If $A$ is a symmetric matrix, any block matrix partitioned as:
    $$
    A = \begin{bmatrix}
    B & C \\
    C^T & D
    \end{bmatrix}
    $$
    satisfies $C = C^T$ (i.e., the off-diagonal blocks must also be symmetric).

#### Example

Consider the symmetric matrix:

$$
A = \begin{bmatrix}
4 & 1 \\
1 & 3
\end{bmatrix}
$$

1. **Find Eigenvalues**: Solve $\det(A - \lambda I) = 0$:

   $$
   \begin{vmatrix}
   4 - \lambda & 1 \\
   1 & 3 - \lambda
   \end{vmatrix}
   = 0
   $$

   $$
   (4 - \lambda)(3 - \lambda) - 1 = 0 \implies \lambda^2 - 7\lambda + 11 = 0
   $$

2. **Eigenvalues**:

   $$
   \lambda_1 = 5, \quad \lambda_2 = 2
   $$

3. **Eigenvectors**:  
   For $\lambda_1 = 5$:

   $$
   (A - 5I)v = 0 \implies \begin{bmatrix}
   -1 & 1 \\
   1 & -2
   \end{bmatrix}
   v = 0
   $$

   Eigenvector: $v_1 = \begin{bmatrix} 1 \\ 1 \end{bmatrix}$

   For $\lambda_2 = 2$:

   $$
   (A - 2I)v = 0 \implies \begin{bmatrix}
   2 & 1 \\
   1 & 1
   \end{bmatrix}
   v = 0
   $$

   Eigenvector: $v_2 = \begin{bmatrix} -1 \\ 2 \end{bmatrix}$

4. **Orthonormalize**: Normalize eigenvectors to form $Q$:

   $$
   Q = \begin{bmatrix}
   \frac{1}{\sqrt{2}} & -\frac{1}{\sqrt{5}} \\
   \frac{1}{\sqrt{2}} & \frac{2}{\sqrt{5}}
   \end{bmatrix}
   $$

5. **Diagonalization**:
   $$
   A = Q \Lambda Q^T
   $$

#### Applications

1. **Identify Symmetry Quickly**:  
   In a square matrix $A$, check $a_{ij} = a_{ji}$. This visual inspection often reveals symmetry.

2. **Use Eigenvalues for Determinants and Inverses**:  
   If eigenvalues are given:

   - Compute the determinant as the product of eigenvalues.
   - Compute the inverse using eigenvalues:
     $$
     A^{-1} = Q \Lambda^{-1} Q^T, \quad \text{where } \Lambda^{-1} = \text{diag}(\frac{1}{\lambda_1}, \dots, \frac{1}{\lambda_n}).
     $$

3. **Diagonalization**:  
   Use orthogonal diagonalization to simplify matrix operations like powers and exponentials:

   $$
   A^k = Q \Lambda^k Q^T, \quad \text{where } \Lambda^k \text{ is } \text{diag}(\lambda_1^k, \dots, \lambda_n^k).
   $$

4. **Focus on Quadratic Forms**:  
   Symmetric matrices often appear in quadratic forms $x^T A x$. To determine the definiteness of $A$:

   - Check the eigenvalues:  
     $\lambda > 0$ for positive definite, $\lambda \geq 0$ for semi-definite.

5. **Trace and Norms**:

   - The trace of a symmetric matrix equals the sum of its eigenvalues:
     $$
     \text{trace}(A) = \sum_{i=1}^n \lambda_i.
     $$
   - The Frobenius norm is:
     $$
     \|A\|_F = \sqrt{\sum_{i,j} a_{ij}^2}.
     $$

6. **Special Case: Identity Matrix**:  
   The identity matrix $I$ is symmetric, and its eigenvalues are all $1$. Use this property to simplify symmetric matrix equations.

7. **Projection and Symmetry**:  
   If $P$ is symmetric and $P^2 = P$, it’s a projection matrix. Use this property to simplify problems in linear regression or geometry.

#### Tips and Tricks for Competitive Exams

1. **Orthogonality Check**:  
   Use the orthogonality property to verify eigenvectors. If $v_1$ and $v_2$ are eigenvectors of a symmetric matrix, check:

   $$
   v_1^T v_2 = 0
   $$

2. **Simplify with Diagonalization**:  
   For powers of $A$, use the diagonalization formula:

   $$
   A^k = Q \Lambda^k Q^T
   $$

   This reduces the computational effort significantly.

3. **Test Real Eigenvalues**:  
   In multiple-choice questions, if the matrix is symmetric, reject any option with complex eigenvalues.

4. **Spectral Decomposition**:  
   For quadratic forms $x^T A x$, decompose $A$ using eigenvalues and eigenvectors:

   $$
   x^T A x = \sum\_{i=1}^n \lambda_i (x^T v_i)^2
   $$

5. **Eigenvector Matrix $Q$**:  
   If eigenvectors are normalized and form an orthogonal matrix $Q$, verify:

   $$
   Q^T Q = I
   $$

6. **Quick Eigenvalue-Eigenvector Pairing**:  
   When $A v = \lambda v$:
   - Test eigenvectors by substitution into the equation $A v - \lambda v = 0$.

<hr>

### Idempotent Matrix

An **idempotent matrix** is a square matrix $A$ that satisfies the equation:

$$
A^2 = A
$$

This means that when the matrix is multiplied by itself, the result is the same as the original matrix.

#### Properties

1. **Eigenvalues**:  
   The eigenvalues of an idempotent matrix are either $0$ or $1$.

   - If $A$ is an $n \times n$ idempotent matrix, the eigenvalue equation is:
     $$
     Av = \lambda v, \quad \text{and } A^2v = Av \implies \lambda^2 = \lambda \implies \lambda = 0 \text{ or } \lambda = 1
     $$

2. **Trace**:  
   The trace of an idempotent matrix equals the rank of the matrix:

   $$
   \text{trace}(A) = \text{rank}(A)
   $$

3. **Determinant**:  
   The determinant of an idempotent matrix is either $0$ or $1$:

   $$
   \det(A) = 0 \quad \text{or} \quad \det(A) = 1
   $$

4. **Symmetry**:

   - If $A$ is symmetric and idempotent, it represents an orthogonal projection matrix.

5. **Rank**:

   - The rank of $A$ equals the trace of $A$. If $A$ is $n \times n$, then:
     $$
     0 \leq \text{rank}(A) \leq n
     $$

6. **Nilpotency**:
   - If $A$ is idempotent and $A \neq I$, $A$ is not invertible unless $A = I$.

> Idempotent matrices $A$ and $B$, have the following properties:
>
> 1. $A^n = A$, for n = 1, 2, 3, ...
> 2. $I - A$ is idempotent
> 3. $A^H$ is idempotent
> 4. $I - A^H$ is idempotent
> 5. If $AB = BA$ ⇒ $AB$ is idempotent
> 6. $rank(A) = Tr(A)$
> 7. $A(I - A) = 0$
> 8. $(I - A)A = 0$
> 9. $A^+ = A$
> 10. $f(sI + tA) = (I - A)f(s) + Af(s + t)$ <br>
>     Note that $A - I$ is not necessarily idempotent.

#### Examples

1. A trivial idempotent matrix:

   $$
   A = \begin{bmatrix}
   1 & 0 \\
   0 & 1
   \end{bmatrix}, \quad A^2 = A
   $$

2. A non-identity idempotent matrix:
   $$
   A = \begin{bmatrix}
   1 & 0 \\
   0 & 0
   \end{bmatrix}, \quad A^2 = A
   $$

#### Applications

1. **Squaring the matrix**:  
   Check if $A^2 = A$.

2. **Eigenvalues**:  
   If the eigenvalues are only $0$ and $1$, $A$ might be idempotent.

3. **Rank and trace**:  
   Verify if the rank equals the trace.

4. **Projection matrices**:  
   In some contexts, idempotent matrices arise naturally as projection operators. If $A^2 = A$ and $A$ is symmetric, it represents a projection.

**Tricks to Identify an Idempotent Matrix**

1. **Spectral decomposition**:  
   For a symmetric idempotent matrix, $A$, we can write:

   $$
   A = Q \Lambda Q^T
   $$

   where $\Lambda$ contains $0$ and $1$ on its diagonal, and $Q$ is an orthogonal matrix.

2. **Addition and subtraction**:

   - If $A$ and $B$ are idempotent and commute ($AB = BA$), then:
     $$
     (A + B)^2 = A + B \quad \text{and} \quad (A - B)^2 = A - B
     $$

3. **Diagonalization**:  
   Any symmetric idempotent matrix can be diagonalized. Its diagonal entries are the eigenvalues $0$ or $1$.

4. **Projection in Linear Models**:  
   In regression analysis, the hat matrix $H$ is idempotent:

   $$
   H = X(X^TX)^{-1}X^T, \quad H^2 = H
   $$

5. **Data Transformation**:  
   Idempotent matrices are used to project data points onto subspaces.

Reference:

1. [The Matrix Cookbook](https://www.math.uwaterloo.ca/~hwolkowi/matrixcookbook.pdf)

<hr>

</span>
