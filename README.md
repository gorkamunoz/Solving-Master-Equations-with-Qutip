Master Equations Solving with Qutip
=

This notebook solves the dynamics of three level atom using the [QutiP](http://qutip.org/) toolbox. We consider dissipation
from state b and c to a, with strength gamma_1. The system is driven with strength Omega. We solve the evolution for three different 
cases:
- **Time independent Hamiltonian:** the drive is considered constant.
- **Time dependent Hamiltonian - On-Off Drive:** we consider that the drive is turned on at time T.
- **Time dependent Hamiltonian - Gaussian Pulse:** we consider that the drive is a Gaussian pulse.
