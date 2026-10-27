# VOE Optimizers
In VQE (Variational Quantum Eigensolver), the following are optimizer names used to minimize the cost function, typically the expectation value of a Hamiltonian.

Description

Sequential Least Squares Quadratic Programming: A classical gradient-based optimizer that handles constraints.
Conjugate Gradient: An optimization method that uses gradient information to find a minimum efficiently.
Simultaneous Perturbation Stochastic Approximation: A stochastic optimizer that estimates gradients using only a small number of objective-function evaluations, useful for noisy quantum hardware.
Analytic Quantum Gradient Descent: A gradient-based optimizer designed for quantum algorithms, using analytic gradients when available.

Workflow in VQE
(a) The quantum circuit prepares a parameterized quantum state.
(b) The expectation value of the Hamiltonian is calculated.
(c) The optimizer updates the circuit parameters to minimize the energy.
(d) This process repeats until convergence or a stopping condition is reached.
