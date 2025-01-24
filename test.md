### Partial Derivatives

In calculus, a **partial derivative** of a function of multiple variables is its derivative with respect to one of those variables, with the other variables held constant. This is different from an ordinary derivative, where the function depends on a single variable.

Partial derivatives are crucial in multivariable calculus because they help us understand how a function changes as each of its variables changes. They are widely used in various fields such as physics, engineering, economics, and machine learning.

Let $f(x, y)$ be a function of two variables $x$ and $y$. The partial derivatives of $f$ with respect to $x$ and $y$ are denoted by $f_x$ and $f_y$, respectively, and are defined as:

$$
 f_x = \frac{\partial f}{\partial x} = \lim_{\Delta x \to 0} \frac{f(x + \Delta x, y) - f(x, y)}{\Delta x}
$$

$$
 f_y = \frac{\partial f}{\partial y} = \lim_{\Delta y \to 0} \frac{f(x, y + \Delta y) - f(x, y)}{\Delta y}
$$

In simple terms, $f_x$ measures the rate of change of $f$ with respect to $x$ while keeping $y$ constant, and $f_y$ measures the rate of change of $f$ with respect to $y$ while keeping $x$ constant.

**Notation** <br>

- $f_x$ or $\frac{\partial f}{\partial x}$: Partial derivative with respect to $x$.
- $f_y$ or $\frac{\partial f}{\partial y}$: Partial derivative with respect to $y$.

**Example** <br>

Consider the function $f(x, y) = x^2y + 3xy + y^3$.

1. **Partial Derivative with Respect to $x$**:

   $$
    f_x = \frac{\partial}{\partial x} (x^2y + 3xy + y^3)
   $$

   $$
    f_x = 2xy + 3y
   $$

2. **Partial Derivative with Respect to $y$**:
   $$
    f_y = \frac{\partial}{\partial y} (x^2y + 3xy + y^3)
   $$
   $$
    f_y = x^2 + 3x + 3y^2
   $$

> Partial derivatives give us the slope of the tangent line to the curve obtained by intersecting the surface $z = f(x, y)$ with a plane parallel to the respective coordinate plane.

### Higher-Order Partial Derivatives

Just like ordinary derivatives, we can take higher-order partial derivatives. For a function $f(x, y)$, the second-order partial derivatives are:

- $f_{xx} = \frac{\partial^2 f}{\partial x^2}$: Second partial derivative with respect to $x$.
- $f_{yy} = \frac{\partial^2 f}{\partial y^2}$: Second partial derivative with respect to $y$.
- $f_{xy} = \frac{\partial^2 f}{\partial y \partial x}$ or $f_{yx} = \frac{\partial^2 f}{\partial x \partial y}$: Mixed partial derivatives.

### Clairaut's Theorem

As mentioned earlier, for functions with continuous second-order partial derivatives, the mixed partial derivatives are equal:

$$
 f_{xy} = f_{yx}
$$

### Applications

Partial derivatives are used in numerous applications, including:

1. **Gradient**: The gradient of a function $f(x, y)$ is a vector that points in the direction of the steepest ascent. It is denoted by $\nabla f$ and is given by:

   $$
    \nabla f = \left( \frac{\partial f}{\partial x}, \frac{\partial f}{\partial y} \right)
   $$

2. **Tangent Planes**: The equation of the tangent plane to the surface $z = f(x, y)$ at the point \((x_0, y_0, z_0)\) is:

   $$
    z - z_0 = f_x(x_0, y_0)(x - x_0) + f_y(x_0, y_0)(y - y_0)
   $$

3. **Optimization**: In optimization problems, partial derivatives are used to find local maxima, minima, and saddle points of functions with several variables.

### Example Problems

1. **Find the Partial Derivatives**:
   For the function $g(x, y) = \sin(x) \cos(y)$:

   $$
   g_x = \frac{\partial g}{\partial x} = \cos(x) \cos(y)
   $$

   $$
   g_y = \frac{\partial g}{\partial y} = -\sin(x) \sin(y)
   $$

2. **Compute the Gradient**:
   For $h(x, y) = x^2 + y^2$:
   $$
   \nabla h = \left( \frac{\partial h}{\partial x}, \frac{\partial h}{\partial y} \right) = (2x, 2y)
   $$

### Visual Representation

Let's visualize partial derivatives with a simple 3D surface. Suppose we have a surface $z = f(x, y)$, and we slice it with planes parallel to the $x$- and $y$-axes:

- **Slice Parallel to $yz$-Plane**: Fix $x = x_0$. The curve is $z = f(x_0, y)$. The slope of this curve at $y = y_0$ is $f_y(x_0, y_0)$.
- **Slice Parallel to $xz$-Plane**: Fix $y = y_0$. The curve is $z = f(x, y_0)$. The slope of this curve at $x = x_0$ is $f_x(x_0, y_0)$.

In summary, partial derivatives help us understand how functions of multiple variables change with respect to each variable independently. They are the cornerstone of multivariable calculus and have vast applications in science, engineering, and beyond. If you have more questions or need further clarification on any part, feel free to ask!
