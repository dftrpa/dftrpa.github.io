# Random Phase Approximation Functional (RPAF)

RPAF is a Local Density Approximation (LDA) functional based on the uniform electron gas (UEG).

For more details about the functional see <paper `reference goes here>.

An implementation of the RPAF functional for [Quantum ESPRESSO](https://www.quantum-espresso.org/) package version 7.2 can be found here. Simply replace these files with the ones in the XClib directory of the Quantum ESPRESSO installation directory.

To use the functional, use the flag _input_dft = 'RPAF'_ (or _input_dft = 'XC-001I-051I'_ in index notation) in the system namelist of the pw.x program.

A set of pseudopotentials for the RPAF functioanl generated with the [PSlibrary](https://dalcorso.github.io/pslibrary/) input files are provided below.

<tar.files>
