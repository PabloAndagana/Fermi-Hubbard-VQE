# Quantum Simulations: Fermi–Hubbard & Schwinger Models

Two quantum simulation examples using PennyLane and IBM simulators:

Fermi_Hubbard_VQE.py — Variational Quantum Eigensolver for the Fermi–Hubbard model, reaching 
$E_0 = -4.005$ with a Hamiltonian Variational Ansatz and ADAM optimizer.

Schwinger_Model.py — First- and second-order Trotter simulations of the Schwinger model in 
$1+1$ dimensions, analyzing fermion–antifermion pair creation and annihilation.

These scripts serve as testbeds for extending to more complex models like lattice QCD.

Requirements: Python 3.9+, PennyLane, Qiskit, NumPy, Matplotlib.
