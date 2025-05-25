# Useful Formulae

## 1. Particle in a 1D Box

### Hamiltonian:
$$
\hat{H} = -\frac{\hbar^2}{2m} \frac{d^2}{dx^2}
$$
where $m$ is the mass of the particle, and $\hbar$ is the reduced Planck constant.

### Boundary Conditions:

- The potential $V(x) = 0$ inside the box $(0 \leq x \leq L)$.
- $V(x) \to \infty$ outside the box.

### Energy Eigenfunctions:
$$
\psi_n(x) = \sqrt{\frac{2}{L}} \sin\left(\frac{n \pi x}{L}\right), \quad n = 1, 2, 3, \dots
$$

### Energy Eigenvalues:
$$
E_n = \frac{n^2 \pi^2 \hbar^2}{2mL^2}, \quad n = 1, 2, 3, \dots
$$

## 2. Harmonic Oscillator

### Hamiltonian:
$$
\hat{H} = -\frac{\hbar^2}{2\mu} \frac{d^2}{dx^2} + \frac{1}{2}  k x^2
$$
where $\mu$ is the reduced mass and $k$ is the force constant.

Define the angular frequency:
$$
\omega = \sqrt{\frac{k}{\mu}}.
$$

### Energy Eigenfunctions:
$$
\psi_n(x) = \left(\frac{\alpha}{\pi}\right)^{1/4} \frac{1}{\sqrt{2^n n!}} H_n\left(\sqrt{\alpha} x\right) e^{-\frac{\alpha x^2}{2}}, \quad n = 0, 1, 2, \dots
$$
where $H_n(x)$ are Hermite polynomials and $\alpha = \frac{\mu \omega}{\hbar}$. The first few Hermite polynomials are:

$$
\begin{aligned}
H_0(y) &= 1 \\
H_1(y) &= 2y \\
H_2(y) &= 4y^2 - 2 \\
H_3(y) &= 8y^3 - 12y \\
H_4(y) &= 16y^4 - 48y^2 + 12 \\
H_5(y) &= 32y^5 - 160y^3 + 120y
\end{aligned}
$$

### Energy Eigenvalues:
$$
E_n = \left(n + \frac{1}{2}\right) \hbar \omega, \quad n = 0, 1, 2, \dots
$$

## 3. Rigid Rotor (2D)

### Hamiltonian:
$$
\hat{H} = -\frac{\hbar^2}{2I} \frac{d^2}{d\phi^2}
$$
where $I = \mu r^2$ is the moment of inertia, and $\phi$ is the angular coordinate.

### Energy Eigenfunctions:
$$
\psi_m(\phi) = \frac{1}{\sqrt{2\pi}} e^{im\phi}, \quad m = 0, \pm 1, \pm 2, \dots
$$

### Energy Eigenvalues:
$$
E_m = \frac{\hbar^2 m^2}{2I}, \quad m = 0, \pm 1, \pm 2, \dots
$$

### Angular Momentum Eigenvalues:
$$
L_m = \hbar m \quad m = 0, \pm 1, \pm 2, \dots
$$
These are both the z-component and total angular momentum for the 2D rigid rotor.

