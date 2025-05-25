# Problem Set 1

## Problem 1 (20 points equally distributed among parts a through d)

Recall the energy eigenfunctions for the particle-in-a-box from class have the form

$$
\psi_n(x) = \sqrt{\frac{2}{L}} \sin\left(\frac{n\pi}{L}x\right).
$$

- **(a)** Are the energy eigenfunctions given by $\psi_n(x)$ also eigenfunctions of the momentum operator, $\hat{p} = -i\hbar \frac{d}{dx}$? It will probably be helpful to justify your answer mathematically and with a sentence or two of explanation.  
  *Answer:*

- **(b)** Assuming the length of the box is $L = 10 \times 10^{-10} \: \text{m}$, what is the momentum expectation value of the ground-state of the particle in a box? You can use the formula below to compute this expectation value, and you may use Wolfram Alpha or other tools to evaluate the final integrals.

$$
\langle p \rangle = \langle \psi_1(x)| \hat{p} | \psi_1(x) \rangle = -i \hbar \int_0^L \psi_1^*(x) \, \frac{d}{dx} \, \psi_1(x) \, dx
$$

- **(c)** Assuming the length of the box is $L = 10 \times 10^{-10} \: \text{m}$ and the mass of the electron is $9.109 \times 10^{-31} \: \text{kg}$, what is the energy expectation value of the ground-state of the particle in a box? You can use the formula below to compute this expectation value. You should **not need** to use Wolfram Alpha to compute the integrals in this case.

$$
E_1 = \frac{1^2 \pi^2 \hbar^2}{2mL^2}
$$

- **(d)** For the ground state wavefunction of a particle in a box, the momentum expectation value is zero. But what about the *expectation value of the square of the momentum*, i.e. $\langle p^2 \rangle$? Is it zero or nonzero? Use this expression to explain why or why not:

$$
\langle p^2 \rangle = \langle \psi_1(x)| \hat{p}^2 | \psi_1(x) \rangle = -\hbar^2 \int_0^L \psi_1^*(x) \, \frac{d^2}{dx^2} \, \psi_1(x) \, dx
$$

## Problem 2 (20 points equally distributed among parts a through d)

Let us again consider a quantum particle in a box, with box length $L = 10 \times 10^{-10}$ m.

- **(a)** What is the *wavelength* of the particle in the ground state?

- **(b)** What is the *wavelength* of the particle in the second excited state?

- **(c)** What is the *momentum* of the particle in the second excited state? You can use the relationship $p = \frac{h}{\lambda}$, where $h$ is Planck’s constant.

- **(d)** What is the *kinetic energy* of the particle in the second excited state? You may use either the quantum mechanical formula for $E_n$ or the classical mechanics formula $E = \frac{p^2}{2m}$.

## Problem 3 (20 points equally distributed among parts a through d)

Let’s examine the time evolution of a quantum particle in a box. Suppose the initial state of a particle is the following linear combination of two eigenstates:

$$
\Psi(x,0) = \frac{1}{\sqrt{2}} \left[ \psi_1(x) + \psi_2(x) \right]
$$

- **(a)** What is the wavefunction at a later time $t$?

- **(b)** What is the probability density $|\Psi(x,t)|^2$?

- **(c)** Plot $|\Psi(x,t)|^2$ at $t = 0$ and at some later time $t = t_1$ such that the wavefunction has noticeably changed. You can use Python or any other tool. Label your axes.

- **(d)** Is the probability density $|\Psi(x,t)|^2$ time-independent or time-dependent? Explain why this happens in terms of the energy eigenfunctions and time evolution.

## Problem 4 (20 points equally distributed among parts a through d)

This problem explores how quantum mechanics explains the color of light emitted by hydrogen atoms. Use the Bohr model of the hydrogen atom and the following energy level equation:

$$
E_n = -\frac{13.6 \, \text{eV}}{n^2}, \quad n = 1, 2, 3, \dots
$$

- **(a)** What is the energy (in eV) of the photon emitted when an electron transitions from $n=3$ to $n=2$?

- **(b)** What is the wavelength (in nm) of this photon? Use $E = \frac{hc}{\lambda}$.

- **(c)** What part of the electromagnetic spectrum does this correspond to (e.g., infrared, visible, ultraviolet)?

- **(d)** What color does this correspond to in visible light, and how does that explain what we see when looking at hydrogen’s emission spectrum?


