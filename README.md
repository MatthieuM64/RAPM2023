# RAPM2023
Restricted active Potts model

Codes used in the scientific publications:</br>
M. Karmakar, S. Chatterjee, M. Mangeat, H. Rieger, and R. Paul, <a href="https://journals.aps.org/pre/abstract/10.1103/PhysRevE.108.014604" target="_blank">Jamming and flocking in the restricted active Potts model</a>, Phys. Rev. E 108, 014604 (2023). Preprint available on arXiv: https://arxiv.org/abs/2212.10251.

<b>MPS=1</b></br>
FreeFem++ code (https://freefem.org/) for MPS=1 hardcore restriction in the 4-state active Potts model.</br>
Run: FreeFem++ -v 0 -nw RAPM4_MPS1.edp -parameter value.</br>
List of parameters: rho0, Pe, epsilon, L, dt, tmax, N, init, gamma (details as comments in the code).

<b>Hardcore (MPS>1)</b></br>
FreeFem++ code (https://freefem.org/) for MPS>1 hardcore restriction in the 4-state active Potts model.</br>
Run: FreeFem++ -v 0 -nw RAPM4_hardcore.edp -parameter value.</br>
List of parameters: beta, rho0, epsilon, MPS, L, dt, tmax, N, init, gamma (details as comments in the code).

<b>Softcore</b></br>
FreeFem++ code (https://freefem.org/) for softcore restriction in the 4-state active Potts model.</br>
Run: FreeFem++ -v 0 -nw RAPM4_softcore.edp -parameter value.</br>
List of parameters: beta, rho0, epsilon, u, L, dt, tmax, N, init, gamma (details as comments in the code).
