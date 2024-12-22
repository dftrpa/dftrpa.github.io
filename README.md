RPAF, short for Random Phase Approximation (RPA) based Functional, is a local density approximation functional based on the uniform electron gas with an RPA-renormalized screened interaction.

RPAF is distributed under the GNU General Public License. We would appreciate it if any work using the functional contains the reference: [M. Benites, A. Rosado, and E. Manousakis, Phys. Rev. B 110, 195151 (2024).](https://journals.aps.org/prb/abstract/10.1103/PhysRevB.110.195151).

An implementation of the RPAF for the [Quantum ESPRESSO](https://www.quantum-espresso.org/) package version 7.2 can be found [here](rpaf.tar.gz). Replace these files with the ones in the ```XClib``` directory of the Quantum ESPRESSO installation directory and compile with ```make all```.

To use the functional for self-consistent calculations, add the flag ```input_dft = 'RPAF'``` (or ```input_dft = 'XC-001I-015I'```) in the system namelist of the pw.x input files. For more details check the [input file description](https://www.quantum-espresso.org/Doc/INPUT_PW.html).

## Pseudopotentials

A ready-to-use set of pseudopotentials for the RPAF can be found below. These pseudopotentials were generated with the [PSlibrary](https://dalcorso.github.io/pslibrary/) input files.

- us_high_precision.tar
- us_low_precision.tar
- paw_high_precision.tar
- paw_low_precision.tar
