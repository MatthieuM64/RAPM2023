# Restricted active Potts model

Codes used in the scientific publication:</br>
M. Karmakar, S. Chatterjee, M. Mangeat, H. Rieger, and R. Paul, <i><a href='https://journals.aps.org/pre/abstract/10.1103/PhysRevE.108.014604'>Jamming and flocking in the restricted active Potts model</a></i>, Phys. Rev. E 108, 014604 (2023). Preprint available on <a href='https://arxiv.org/abs/2212.10251'>arXiv</a>.

## MPS=1

<a href='https://freefem.org/'>FreeFem++ code</a> for MPS=1 hardcore restriction in the 4-state active Potts model.</br>
Run: FreeFem++ -v 0 -nw RAPM4_MPS1.edp -parameter value.</br>
List of parameters: rho0, Pe, epsilon, L, dt, tmax, N, init, gamma (details as comments in the code).

## Hardcore restriction (MPS>1)

<a href='https://freefem.org/'>FreeFem++ code</a> for MPS>1 hardcore restriction in the 4-state active Potts model.</br>
Run: FreeFem++ -v 0 -nw RAPM4_hardcore.edp -parameter value.</br>
List of parameters: beta, rho0, epsilon, MPS, L, dt, tmax, N, init, gamma (details as comments in the code).

## Softcore restriction

<a href='https://freefem.org/'>FreeFem++ code</a> for softcore restriction in the 4-state active Potts model.</br>
Run: FreeFem++ -v 0 -nw RAPM4_softcore.edp -parameter value.</br>
List of parameters: beta, rho0, epsilon, u, L, dt, tmax, N, init, gamma (details as comments in the code).
