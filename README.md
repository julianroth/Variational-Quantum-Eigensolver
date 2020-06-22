# Variational Quantum Eigensolver

Implementation of Variational Quantum Eigensolvers in Q# by Christopher Kang, Robert Minneker and Julian Roth. This was
done as part of "CSE490Q Quantum Computing" at the University of Washington.

A report summarizing our work can be found in Group_Report.pdf.

The project consists of three modules. The first, NWChem_Experiments, implements a piece of sample code alongside NWChem YAML files to demonstrate Trotterization / Qubitization. The second, VQE, contains the first implementation of a Variational Quantum Eigensolver in Q#. Please refer to the Sample1.0 files for the most recent code and examples on implementation. Release1.0 has slightly outdated code with diagnostic features. Intro1 has legacy code that should not be used. The final is a Python script that allows the conversion of PSI4 to Broombridge, Microsoft's Quantum Chemistry file format. This is found in the psi4_to_broombridge folder.
