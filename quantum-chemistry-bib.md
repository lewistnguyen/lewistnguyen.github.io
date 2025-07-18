---
layout: page
title: quantum chemistry bibliography
---

This is a list of papers and other resources relevant to quantum chemistry and related topics. They are sorted by resource type (papers, books, videos, tutorials, etc.) and by topic if necessary. This bibliography does not only include items that I already read or am reading but also what I plan to read but have not yet dedicated time to do so.

Last edited: June 29, 2025.

## Textbooks

1. McQuarrie, D. A.; Simon, J. D. *Physical Chemistry: A Molecular Approach*; University Science Books, 1997.
2. Atkins, P.; de Paula, J. *Physical Chemistry*, 8th ed.; Oxford University Press, 2006.
3. Griffiths, D. J; Schroeter, D. F. *Introduction to Quantum Mechanics*, 3rd ed.; Cambridge University Press, 2017.
3. McQuarrie, D. A. *Quantum Chemistry*, 2nd ed.; University Science Books, 2008.
4. Szabo, A.; Ostlund, N. S. *Modern Quantum Chemistry: Introduction to Advanced Electronic Structure Theory*; Dover Publications, 1996.
5. Cramer, C. J. *Essentials of Computational Chemistry: Theories and Models*, 2nd ed.; John Wiley & Sons, 2004.
6. Jensen, F. *Introduction to Computational Chemistry*, 3rd ed.; John Wiley & Sons, 2017.

## Literature reviews & Perspectives

1. Bursch, M; Mewes, J.-M.; Hansen, A.; Grimme, S. Best-practice DFT protocols for basic molecular computational chemistry. *Angew. Chem. Int. Ed.* **2022**, *61* (42), e202205735. DOI: [https://doi.org/10.1002/anie.202205735](https://doi.org/10.1002/anie.202205735)
    - A practical guide to how to do DFT for molecular (i.e. finite size, not crystals) systems to yield the best results.
2. Grimme, S.; Hansen, A.; Brandenburg, J. G.; Bannwarth, C. Dispersion-corrected mean-field electronic structure methods. *Chem. Rev.* **2016**, *116* (9), 5105–5154. DOI: (https://doi.org/10.1021/acs.chemrev.5b00533)[https://doi.org/10.1021/acs.chemrev.5b00533]
    - A discussion of latest methods to correct for long-range interaction, including dispersion-corrected functionals, semiempirical corrections, and others. Authored by Stefan Grimme and colleagues at the University of Bonn. Grimme himself was integral in the development of some of the most popular semiempirical correction schemes these days.
3. Slater, J. C. Note on Hartree's method. *Phys. Rev.* **1930**, *35*, 210. DOI: (https://doi.org/10.1103/PhysRev.35.210.2)[https://doi.org/10.1103/PhysRev.35.210.2]

## Original papers

### Foundations of Quantum Chemistry

1. Dirac, P. A. M. Quantum mechanics of many-electron systems. *Proc. R. Soc. Lond. A* **1929**, *123*, 714–733. DOI: [https://doi.org/10.1098/rspa.1929.0024](https://doi.org/10.1098/rspa.1929.0024)
    - The first paper to introduce the concept of a many-electron wavefunction, and also the paper in which the famous Dirac quote describing the entire field of computational chemistry to date is found: "The underlying physical laws necessary for the mathematical theory of a large part of physics and the whole of chemistry are thus completely known, and the difficulty is only that the exact application of these laws leads to equations much too complicated to be soluble."
2. Fock, V. Näherungsmethode zur Lösung des quantenmechanischen Mehrkörperproblems. *Z. Phys.* **1930**, *61*, 126–148. DOI: [ https://doi.org/10.1007/BF01340294]( https://doi.org/10.1007/BF01340294)
    - The first paper to introduce the Hartree-Fock method, which is the basis of most quantum chemistry methods today. Written in German, so I might have to brush up a bit on my German to read it.
3. Brillouin, L. Les champs "self-consistents" de Hartree et de Fock.
    - Paper is in French and impossible to find a PDF online but it's cited in later literature by Slater and others so it's useful for now to leave it here and go for a search later.

### Density Functional Theory (DFT)

1. Hohenberg, P.; Kohn, W. Inhomogeneous electron gas. *Phys. Rev.* **1964**, *136*, B864. DOI: [https://doi.org/10.1103/PhysRev.136.B864](https://doi.org/10.1103/PhysRev.136.B864)
    - First cornerstone paper of DFT with the proofs of the two Hohenberg-Kohn theorems.
2. Kohn, W.; Sham, L. J. Self-consistent equations including exchange and correlation effects. *Phys. Rev.* **1965**, *140*, A1133. DOI: [https://doi.org/10.1103/PhysRev.140.A1133](https://doi.org/10.1103/PhysRev.140.A1133)
    - Second cornerstone paper of DFT with the Kohn-Sham formulation which is the workhorse behind almost all existing DFT applications.
3. Perdew, J. P.; Burke, K.; Ernzerhof, M. Generalized gradient approximation made simple. *Phys. Rev. Lett.* **1997**, *77*, 3865. DOI: [https://doi.org/10.1103/PhysRevLett.77.3865](https://doi.org/10.1103/PhysRevLett.77.3865)
    - Introducing the PBE functional, one of the most commonly used functionals of the *generalized gradient approximation* (GGA) family in modern DFT.
4. Adamo, C.; Ernzerhof, M.; Scuseria, G. E. The meta-GGA functional: Thermochemistry with a kinetic energy density dependent exchange-correlation functional. *J. Chem. Phys.* **2000**, *112*, 2643–2649. DOI: [https://doi.org/10.1063/1.480838](https://doi.org/10.1063/1.480838)
    - Discussing the meta-GGA functional, which is a more advanced functional family that includes kinetic energy density in addition to electron density and its gradient.

