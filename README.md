# Random Phase Approximation Functional (RPAF)

RPAF is a Local Density Approximation (LDA) functional based on the uniform electron gas (UEG).
For more details about the functional see <paper>.
We have implemented the functional on Quantum ESPRESSO under the _GNU General Public Licence_. The necessary files to  use the RPAF functional can be downloaded here.
To use the functional, use the flag _input_dft = 'RPAF'_ (or _input_dft = 'XC-001I-051I'_ in index notation) in the system namelist of the pw.x program.
