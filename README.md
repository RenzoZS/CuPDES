# CuSIR

CuSIR is a Cuda based solver for a diffusive SIR model with spatial rate transmition dependence. 

It basically solves the following system of reaction-diffusion equations with any given initial condition in 2 dimensions:

$$
\begin{align}
\partial_t S &= -\beta_{\mathbf{r}} S I - \gamma I + D_I \nabla^2 I,\\
\partial_t I &= \beta_{\mathbf{r}} S I + D_I \nabla^2 S.
\end{align}
$$



