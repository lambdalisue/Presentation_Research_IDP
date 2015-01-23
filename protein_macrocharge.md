### Intra-Protein interactions & Phase Separations
!(images/macrocharge/1AO6_cartoon.png)<<height:225px;transparent>> 
!(images/macrocharge/1OVA_cartoon.png)<<height:225px;transparent>> 
!(images/macrocharge/1W6Z_cartoon.png)<<height:225px;transparent>> 
!(images/macrocharge/3V03_cartoon.png)<<height:225px;transparent>>

How do we model many protein-protien interactions.
Can we *predict* aggregates? Phase separations lead to sudden 
fundamental changes in liquid structure and local density.
!(images/macrocharge/example_phase_sep.jpg) <<height:225px;transparent>> 
!(images/macrocharge/phase_sep2.jpg) <<height:225px;transparent>> 

&& Human serum albumin, Ovalbumin, Lysozyme, Bovine Serum Albumin respectively.

====*

## Protein-Protein interactions 

|### Important terms:
Volume exclusion, *Electrostatics*, 
Non-specific interactions (London/dispersion forces)

|### Second-order effects?
Non spherical geometries, Polarization,
Internal conformational energies, Solvent effects

====*<<transition:none>>

## Experimental Measurements
Second virial coeffiecent $B_{2}$, measurement of 
protein solutions using light scattering at different pH.
!(images/macrocharge/exp_B22_1OVA.png) <<height:600px;>>

====*<<transition:none>>

## Matching experiments
Theroetical predictions of the second virial coeffiecent $B_{2}$
considering only excluded volume and reduced electrostatics.
!(images/macrocharge/fit_B22_1OVA.png) <<height:600px;>>

=====

## Virial Coefficients

An equation of state expanded in powers of density $\rho$
## $\frac{P}{k_B T} = \rho + B_2(T) \rho^2 + B_3(T) \rho^3 + \ldots$
$B_2$ is the pairwise interaction of _two_ molecules
$B_3$ is the pairwise interaction of _three_ molecules

For rotationally invariant molecules*
##$B_2 = -\frac{1}{2} \int_0^\infty (e^{-U(r)/k_B T} - 1) 4\pi r^2 dr$

&& *Rotationally invariant calculation intergrates over all oritentations