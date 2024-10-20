RPAF is a Local Density Approximation functional based on the uniform electron gas by using the renormalized random phase approximation (RPA) screened interaction.

For more details about the functional see (paper reference goes here).

An implementation of the RPAF functional for the [Quantum ESPRESSO](https://www.quantum-espresso.org/) package version 7.2 can be found **here**. Replace these files with the ones in the ```XClib``` directory of the Quantum ESPRESSO installation directory and compile with ```make all```.

To use the functional, use the flag ```input_dft = 'RPAF'``` (or ```input_dft = 'XC-001I-051I'``` with index notation) in the system namelist of the pw.x input files. For more details check the [input file description](https://www.quantum-espresso.org/Doc/INPUT_PW.html).

## Pseudopotentials

Below is a set of pseudopotentials for the RPAF functional generated with the [PSlibrary](https://dalcorso.github.io/pslibrary/) input files.

<tar.files>
