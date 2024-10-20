RPAF is a Local Density Approximation functional based on the uniform electron gas by using a renormalized random phase approximation (RPA) screened interaction.

For more details about the functional see <paper `reference goes here>.

An implementation of the RPAF functional for the [Quantum ESPRESSO](https://www.quantum-espresso.org/) package version 7.2 can be found <here>. Replace these files with the ones in the ```XClib``` directory of the Quantum ESPRESSO installation directory and compile with ```make all```.

To use the functional, use the flag _input_dft = 'RPAF'_ (or _input_dft = 'XC-001I-051I'_ in index notation) in the system namelist of the pw.x input files. For more details see <here>.

A set of pseudopotentials for the RPAF functioanl generated with the [PSlibrary](https://dalcorso.github.io/pslibrary/) input files are provided below.

<tar.files>
