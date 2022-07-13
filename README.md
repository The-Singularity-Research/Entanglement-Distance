# Entanglement-Distance
Convert entanglement to edge weights/distances
---
This will take a quantum surface code/circuit with arbitrary controlled-U gates 
(see [Cirq](https://quantumcomputing.stackexchange.com/questions/5521/how-to-add-control-to-gates-in-cirq) and [Qiskit](https://qiskit.org/documentation/stubs/qiskit.circuit.library.CU3Gate.html)) and then
compute the [operator norm distance](https://numpy.org/doc/stable/reference/generated/numpy.linalg.norm.html) 
from each controlled-U to a CNOT gate. This distance will be normalized and converted
to an edge weight on a graph describing the entanglement of the qudits effectively converting entanglement
measures into Euclidean or conformal distances in an entangled system of qudits/particles. 
