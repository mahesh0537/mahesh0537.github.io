<!-- ## Gaussian Units
 -->
mode dark
- [Maxwell's Equation](#maxwells-equation)
  - [In the case of a vacuum](#in-the-case-of-a-vacuum)
  - [Contunuity Equation](#contunuity-equation)
  - [The Maxwell's Equations in Macroscopic Midia](#the-maxwells-equations-in-macroscopic-midia)
  - [Boundary Conditions at Interfaces between Different Media](#boundary-conditions-at-interfaces-between-different-media)

# Maxwell's Equation

$$\begin{equation}\vec{\nabla} \cdot \vec{D}  = \rho\end{equation}$$ 
$$\begin{equation}\vec{\nabla} \times \vec{H}  - \frac{\partial \vec{D}}{\partial t} = \vec{J}\end{equation}$$
$$\begin{equation}\vec{\nabla} \times \vec{E}  + \frac{\partial \vec{B}}{\partial t} = 0\end{equation}$$
$$\begin{equation}\vec{\nabla} \cdot \vec{B}  = 0 \end{equation}$$

## In the case of a vacuum
$$\begin{equation}\vec{D} = \epsilon_0 \vec{E}\end{equation}$$
$$\begin{equation}\vec{B} = \mu_0 \vec{H}\end{equation}$$
$$\begin{equation}C^{-2} = \epsilon_0\mu_0\end{equation}$$
$$\begin{equation}\vec{\nabla}\cdot\vec{E} = \frac{\rho}{\epsilon_0}\end{equation}$$
$$\begin{equation}\vec{\nabla}\times\vec{B} - \frac{1}{C^2}\frac{\delta \vec{E}}{\delta t} = \mu_0\vec{J}\end{equation}$$

## Contunuity Equation
Taking the divergence of the  equation $(2)$ and replacing $\vec{\nabla}\cdot\frac{\delta\vec{D}}{\delta t}$ with $\frac{\delta \rho}{\delta t}$ by using equation $(1)$ gives
$$\begin{equation}\frac{\delta \rho}{\delta t} + \vec{\nabla}\cdot\vec{J} = 0\end{equation}$$


## The Maxwell's Equations in Macroscopic Midia

The other aspect is that for macroscopic observations the detailed behavior of the fields, with their drastic variations in space over atomic distances, is not relevant. What is relevant is the average of a field or a source over a volume large compared to the volume occupied by a single atom or molecule. We call such averaged quantities the macroscopic fields and macroscopic sources.


$$\begin{equation} D_{\alpha} = \epsilon_0 E_{\alpha} + \left[ P_{\alpha} - \sum_{\beta} \frac{\delta Q_{\alpha \beta}}{\delta X_\beta} \right] \end{equation}$$
$$\begin{equation} H_{\alpha} = \frac{1}{\mu_0} B_{\alpha} + \left[ -M_\alpha + .... \right] \end{equation}$$
Magnetic Dipoles

$$\begin{equation} D_\alpha(\vec{x}, t) = \int d^3\vec{x}^, \int dt^, \epsilon_{\alpha \beta}(\vec{x}^, , t)E_\beta(\vec{x} - \vec{x}^,, t - t^,) \end{equation}$$
$t - t^,$ is resopnse time, system takes time to respond to the change in the field.

$\vec{x} - \vec{x}^,$ Non local response

Transforming the equation $(13)$ using the Fourier transform gives
$$f(\^{k}, w) = \int d^3x\int dt \int F(x, t) e^{-i(\^{k}\vec{x} - wt)}$$

Now we get 
$$\begin{equation} D_\alpha (\^{k}, w) = \epsilon_{\alpha \beta}(\^{k}, w)E_\beta(\^{k}, w) \end{equation}$$


## Boundary Conditions at Interfaces between Different Media 