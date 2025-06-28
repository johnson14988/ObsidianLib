A geodesic on a smooth manifold $M$ with an affine connection $\nabla$ is defined as a curve $\gamma(t)$ such that parallel transport along the curve preserves the tangent vector to the curve, so

$$
\nabla_{\dot{\gamma}} \dot{\gamma}=0
$$

at each point along the curve, where $\dot{\gamma}$ is the derivative with respect to $t$. More precisely, in order to define the covariant derivative of $\dot{\gamma}$ it is necessary first to extend $\dot{\gamma}$ to a continuously differentiable vector field in an open set. However, the resulting value of (1) is independent of the choice of extension.

Using local coordinates on $M$, we can write the geodesic equation (using the summation convention) as

$$
\frac{d^2 \gamma^\lambda}{d t^2}+\Gamma_{\mu \nu}^\lambda \frac{d \gamma^\mu}{d t} \frac{d \gamma^\nu}{d t}=0
$$

where $\gamma^\mu=x^\mu \circ \gamma(t)$ are the coordinates of the curve $\gamma(t)$ and $\Gamma_{\mu \nu}^\lambda$ are the Christoffel symbols of the connection $\nabla$. This is an ordinary differential equation for the coordinates. It has a unique solution, given an initial position and an initial velocity. Therefore, from the point of view of classical mechanics, geodesics can be thought of as trajectories of free particles in a manifold. Indeed, the equation $\nabla_{\dot{\gamma}} \dot{\gamma}=0$ means that the acceleration vector of the curve has no components in the direction of the surface (and therefore it is perpendicular to the tangent plane of the surface at each point of the curve). So, the motion is completely determined by the bending of the surface. This is also the idea of general relativity where particles move on geodesics and the bending is caused by gravity.