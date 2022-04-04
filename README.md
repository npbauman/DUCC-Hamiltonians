# DUCC-Hamiltonians
Library of DUCC Hamiltonians in various formats.

Directories are organized as follows:
[Molecule]/[Basis Set]/[Expansion Approximation]/[Number of Active Orbitals]/

In these directories are several files:
"[].json" : Input used to generate to DUCC Hamiltonian.
"out" : Output of the underlying SCF and CCSD calculation.
"out-info" : Contains basic information about the effective Hamiltonian, including the number of orbitals, number of frozen core orbitals (if any), the corresponding SCF energy, the adjusted repusion energy (adjusted for freezing core orbitals), and orbital energies for the effective Hamiltonian.
"out-xacc" : Hamiltonian in the format for the XACC program.
"out.yaml" : The Hamiltonian following the Broombridge Quantum Chemistry Schema.
"out-FCIDUMP" : Format similar to FCIDUMP, with block formating. Use to calculate FCI energies when possible using a program written by Jiri Pittner.
"out-FCIDUMP-FCI" : FCI output from the program written by Jiri Pittner.

The subdirectory labeled "[]files" contains the Hamiltonian output and other information about the DUCC calculation.

