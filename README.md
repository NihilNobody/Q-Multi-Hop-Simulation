[CPUD-Multi-Hop-README-3.pdf](https://github.com/user-attachments/files/23673023/CPUD-Multi-Hop-README-3.pdf)


CPUD Cross-System Portfolio
This repository provides a concise, self-contained evaluation portfolio demonstrating reproducible CPUD-based metrics across representative quantum and biological systems.
 It includes system-level fidelity trends, ΔPurity evolution, exponential decay fits, a multi-system taxonomy matrix, and a cross-domain comparison of CPUD vs tomography behavior.
 No simulation code, derivations, or internal mechanics are included by design.


Contents:

This repository contains the following:

Portfolio PDF





Visualization Outputs






Summary Data Table






Definitions:




Fidelity (Fid):
 Hop-to-hop state overlap indicator used to track coherence retention under CPUD-modeled transitions.




ΔPurity:
 Change in state purity across hops, extracted from the same internal estimator that provides CPUD scaling.




CPUD Exponential Fit (a_cpud):
 Effective decay or reinforcement coefficient describing CPUD scaling over multi-hop propagation.





Tomography Exponential Fit (a_tomo):
 Parallel coefficient extracted from a distinct tomography-based reference estimator.




Aggregate Fidelity Difference:
 Aggregate deviation between CPUD-predicted behavior and tomography-derived behavior across all hops for each system.
 Used as a cross-method consistency indicator.



 

Methodology Snapshot:



All systems are processed through a unified evaluation interface using:





Multi-hop propagation (3-hop fixed across systems)






Independent CPUD estimator and independent tomography baseline






ΔPurity and fidelity extracted per-hop






Exponential decay coefficients fitted from the generated trajectories






Bootstrapped confidence-style measures for internal consistency (used in selection)






This provides a standardized comparison across quantum (transmon, Majorana) and biological (FMO, radical-pair) coherence systems.
This is not intended for replication or open-source distribution.
 
Its purpose is to provide:



Compact evaluation-ready snapshot of CPUD scaling behavior




Cross-domain structural alignment (taxonomy matrix)




Consistent multi-system demonstrations




Evidence of internal coherence and stability across heterogeneous physical systems




For technical review without exposing methods




Omissions:

To prevent dissemination of modeling logic, the following are deliberately excluded:




Simulation source code





Mathematical derivations





CPUD estimator internals





Tomography baseline implementation





Raw datasets





Runtime configuration files



Model-specific parameters



