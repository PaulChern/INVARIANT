# L-INVARIANTS
### Phase field / Landau model builder:
- Displacement and magnetic modes analysis
- INVARIANT generator (couplings among distortion, strain and magnetic)
- Modulate modes in supercell, generate initial Domain walls (DWs) structures for Density Functional Theory (DFT) codes
- Landau model builder, Generate DFT training sets by phonon and magnetic frozen-in.
- Heisenberg model builder
- Finite Element Method (FEM), Minimization, molecular dynamics (MD), monte Carlo (MC), and Finite Differences nonlinear solver on large scale continuous model
- Generate Fortran source code from mathematica
- openmp parallelization
- dynamics under external electric field
- Nudged Elastic Bands (NEB) and Growing String Method (GSM) to explore the phase transition, dynamics, and domain wall structures
- Mollwide projection
- Examples: Boracite (To be added: Perovskite, Spinel, Rutile, Pyrochlore)
### Todo:
- interface with GTpack (http://gtpack.org/)
- implement k dot p model builder
- interface to exact diagnalization method
- adding Atomistic Green's Function (AGF) method to study scattering and ultrafast non-equilibrium dynamics
- including electron phonon coupling (EPC) by fitting phonon dependent Tight-Binding (TB) model from DFT molecular dynamics (MD).
