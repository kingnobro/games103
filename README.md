# games103

### Lab 1:  Angry Bunny

- Leapfrog Integration
- Velocity Update
- Rigid Body Collision Detection and Response by Impulse

[![LV6fP0.gif](https://s1.ax1x.com/2022/04/11/LV6fP0.gif)](https://imgtu.com/i/LV6fP0)



### Lab2: Cloth Simulation

- Implicit Cloth Solver
- Position-Based Dynamics (PBD)

[![LYJPED.gif](https://s1.ax1x.com/2022/04/16/LYJPED.gif)](https://imgtu.com/i/LYJPED)



### Lab3: Bouncy House

- Finite Element Method (FEM)
  $$
  [\textbf{f}_1\ \textbf{f}_2\ \textbf{f}_3]=-V^{\textrm{ref}} FS[\textbf{X}_{10}\ \textbf{X}_{20}\ \textbf{X}_{30}]
  $$
  where $V^{\textrm{ref}}$ is the volume of tetrahedron, $F$ is the deformation gradient, $S$ is the second Piola-Kirchhoff stress $S=\frac{\partial W}{\partial G}=2s_1G+s_0\textrm{tr(G)}I$

- $G=\frac{1}{2}(F^TF-I)$ is the Green Strain, $W(G)$ is St. Venant-Kirchhoff (StVK), $E=\int W(G)\ \textrm{dA}$

- Laplacian smoothing to eliminate high-frequency oscillation

[![Lc2Bzq.gif](https://s1.ax1x.com/2022/04/21/Lc2Bzq.gif)](https://imgtu.com/i/Lc2Bzq)

